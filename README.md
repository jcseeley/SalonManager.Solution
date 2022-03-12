# Salon Stylist/Client Manager

#### By Jase Seeley

#### A web application to keep track of your hair stylists and their clients.

## Technologies Used
* C#
* .NET
* ASP.NET Core MVC
* Entity Core
* SQL
* MySQLWorkbench
* Razor
* CSHTML
* CSS
* Bootstrap

## Description

A user friendly web application for salon owners to manage stylists and their clients. Follow the provided links to add, remove, and edit stylists at your salon. Navigate to an individual stylist page to add, remove, and edit their clients. Easily switch a client from one stylist to another.

## Setup/Installation Requirements

* Clone this repository to your desktop.
* Open MySQLWorkbench and click "Local instance 3306".
* Expand the window to uncover any hidden buttons.
* Under the "Administration" tab, click "Data Import/Restore".
* Select "Import from Self-Contained file".
* To the right of the form field, click the box with ".." in it and navigate to the top level of this directory. Select the "jase_seeley.sql" file.
* Under "Default Target Schema", click the "New..." button, enter a name for your schema, and click "OK".
* Click the "Start Import" button.
* When the import is complete, navigate to the "Schemas" tab.
* 
* Navigate to the "HairSalon" project directory in your terminal.
* Enter "dotnet restore" to install the required packages.
* Enter "dotnet build" to build the project.
* To use the application, enter "dotnet run" and visit "http://localhost:5000/" in your browser.
* When finished, press "CTRL + C" in your terminal to close the application.

## Known Bugs

* No known bugs at this time.

## License

MIT

Copyright (c) 2022 Jase Seeley  