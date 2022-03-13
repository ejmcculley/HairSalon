# _EauClairesSalon_

#### By _**Erin McCulley**_

#### _Beginners Web Development_

## Technologies Used

* _C#_
* _ASP.NET Core_
* _Entity_
* _MySQL Workbench_
* _Razor_
* _Markdown_
* _Git / Github_
* _Terminal_

## Description

_Pierre referred you to their friend Claire! They want you to build an employee management tool for their hair salon. They should be able to add new stylists, and assign clients to a specific stylist._

## Setup/Installation Requirements

_To clone this repository:_

1. Click on the green "Code" button above this file list.
2. Copy the HTTPS link (this is the default option).
3. Open your local Terminal.
4. Navigate to the local directory where you want the cloned directory to go.
5. In your Terminal type "git clone" (without the quotes) then paste the URL you copied above. 
6. Press 'enter' and the cloned directory should be copied to your current working directory.

_To install C# and .NET:_

1. In your Terminal, navigate to HairSalon.Solution/HairSalon and type 'dotnet build' and 'dotnet watch run' to launch the web application.
2. Start by adding a new stylist, then you can fill out details for the stylist, and add clients to their roster. 

_To set up MySQL Workbench:_

1. Download and install MySQL Workbench [here](https://www.mysql.com/products/workbench/).
2. Create an appsettings.json file !!! Add this file to your .gitignore !!! by adding: */appsettings.json to your .gitignore file.
3. Add appsettings.json file in your main project directory. Enter the following into your appsettings.json file

{
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=[YOUR-DATABASE-HERE];uid=root;pwd=[YOUR-PASSWORD-HERE];"
    }
}

_To Import Database_

1. In the Navigator -> Administration window, select Data Import / Restore
2. In Import Options, select Import from Self-Contained File
3. Navigate to file that was just created
4. Under Default Schema to be Imported To, select the New button
  - Enter the name of your database
  - Click OK
5. Go to Import Progress tab and click Start Import at the bottom right corner
6. Reopen  Navigator -> Schemas tab, right click and Refresh All


## Known Bugs

* Having trouble after the client is added. The client and stylist show up in the database, but the object isn't being built properly.

## License
MIT License

Copyright (c) [2021] [Erin McCulley]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.