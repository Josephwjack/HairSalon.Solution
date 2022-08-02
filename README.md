# Eau Claire's Hair Salon

#### By Joseph Jack

## Description

_Eau Claire's Hair Salon is an MVC application built using C#. The application allows the user to add both stylists and their individual clients and search client by stylist. All user input is stored in a database which can be edited.

## Logistics

|                    | Minimum Product Features |
| ------------------ | ------------------------ |
| :heavy_check_mark: | Claire can add stylists and clients|
| :heavy_check_mark: | There has to be atleast one stylist added before a client may be added|
| :heavy_check_mark: | Claire can edit existing stylists and clients|
| :heavy_check_mark: | Claire can also delete existing stylists and clients|

## Setup/Installation Requirements

<details>
<summary><strong>Initial Setup</strong></summary>
<ol>
<li> Clone this projects repository into your local directory following these instructions. URL: https://www.linode.com/docs/development/version-control/how-to-install-git-and-clone-a-github-repository/ .
<li>Open a shell program and navigate to your desktop.
<li>Clone the repository for this project using the "git clone" command and including the copied URL.
<li>While still in the shell program, navigate to the root directory of the newly created file named "HairSalon.Solution".
<li>From the root directory, navigate to the "HairSalon" directory.
<li>Move onto "SQL Workbench" instructions below to re-create database necessary to run this project.
<br>
</details>

<details>
<summary><strong>SQL Workbench Configuration</strong></summary>
<ol>
<li>Create an appsetting.json file in the "HairSalon" directory of the project*  
   <pre>HairSalon.Solution
   └── HairSalon
    └── appsetting.json</pre>
<li> Insert the following code** : <br>

<pre>{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=hair_salon;uid=root;pwd=[YOUR-PASSWORD-HERE];"
  }
}</pre>
<small>*note: you must include your password in the code block section labeled "YOUR-PASSWORD-HERE".</small><br>
<small>**note: if you plan to push this cloned project to a public-facing repository, remember to add the appsettings.json file to your .gitignore before doing so.</small>

<li>Once "appsettings.json" file has been created, navigate back to SQL Workbench.
<li>Import the database named "joseph_jack.sql" from the root directory of the project.<br><br>
How to Import a Database:
<ol> 
  <li>Open SQL Workbench.
  <li>Navigate to "Administration" tab in SQL Workbench.
  <li>Click "Data Import/Restore".
  <li>Select the radio button "Import from Self-Contained File" and include file path to the sql file of this project you cloned to your machine.
  <li>In "Default Schema to be Imported to" click "New".
  <li>Name the schema "hair_salon" then click "OK".
  <li>Once named, switch to "Import Progress" tab and click "Start Import".
  
</details>

<details>
<summary><strong>To Run</strong></summary>
Navigate to:  
   <pre>HairSalon.Solution
   └── <strong>HairSalon</strong></pre>

Run ```$ dotnet restore``` in the console.<br>
Run ```$ dotnet run``` in the console
</details>
<br>

## Technology used

## <a href="https://en.wikipedia.org/wiki/C_Sharp_%28programming_language%29">C#</a>
## <a href="https://en.wikipedia.org/wiki/.NET_Core">.NET Core</a>
## <a href="https://docs.microsoft.com/en-us/dotnet/framework/data/adonet/ef/language-reference/entity-sql-language">Entity</a>
## <a href="https://www.mysql.com/products/workbench/">MySQL Workbench</a>


## Known Bugs

* Any known issues


## License

* MIT

## Copyright

&copy; Joseph Jack 2022

