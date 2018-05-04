# Telosys 3 MVC PHP Template

A [Telosys](https://telosys.org) template of a PHP MVC application, able to perform CRUD (Create, Read, Update, Delete) operations. No data is persisted.  
This template is part of a Bundle (see the Telosys 3 Persistence PHP Template and Telosys 3 REST API PHP Template).
## Requirements

- PHP.

## Dependencies

- Twig 2.

NOTE : Twig 2.x requires PHP 7. If you do not use PHP 7, then set the twig version to 1.x in the composer.json file.

## Usage

1. Download the template.  
2. Check that your model is ready (DSL/Database).
3. Generate the code with Telosys.  
4. Navigate to the generated code's root folder.  
5. Install the dependencies with the following command : `composer install`  

## Getting started
 
1. Host the generated application on a webserver.
2. Open the hosted application with your web browser.

NOTE : This application will not persist any data unless you use a persistence solution (i.e : the Telosys 3 Persistence PHP Template).

## License

This project uses the [LGPL v3 License](https://www.gnu.org/licenses/lgpl-3.0.en.html).
