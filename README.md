# PierresTreats.Solution :cupcake:	:pie:	:lollipop:	
#### Pierre's Sweet & Savory Treats application - 11/6/21 


#### By Gabriel Ayala

## Technologies Used :floppy_disk:
* _C#_
* _Entity_
* Identity
* _.Net 5 SDK_
* _REPL_
* _MySQL_
* _MySQL Workbench_
* _Razor_
* _ASP.NET Core_
* _Git_
* _Css_



## Description :page_with_curl:
_A web application using C# that allows the authorized, signed in, users to view, add, update, and delete treats and flavors to pierre's website. Users not signed in will only have access to view treat/flavor items and their details._

## Setup/Installation Requirements :triangular_ruler:

* _Clone github repo: https://github.com/Gabeaya/VendorOrder.Solution.git_
* _Navigate the directory: (cd top name directory)_
* _Open in Vs code: code ._
* _Run: dotnet restore PierresSweets_
* _The line above will install necessary dependencies._
* _Next we will need a connection string: create a file within the main directory titled, "appsettings.json."_
* _Add the following within our new file: {
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=[YOUR-DATABASE-NAME-HERE];uid=[YOUR-USERNAME-HERE];pwd=[YOUR-PASSWORD-HERE];"
    }
}_
* _IMPORTANT NOTE: Do not iclude the brackets when entering your username or password._

* _Run: dotnet ef database update._

* _Run: dotnet run in order to use the application in the browser._


## License :clipboard:
MIT &copy; 2021 _Gabriel Ayala_
## Contact Information :mailbox:

_Gabriel Ayala:
gabeayala100@gmail.com_