# 13  E-Commerce Back End
## User Story

AS A manager at an internet retail company.
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

 ## Description: 

E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.
As this Application allow user to retrieve, update, delete or create data for products, their tags, and their categories.

## Table of Contents:

* [Mock-Up](Mock-Up)
* [Usage](#usage)
* [Installation](#installation)
* [Deployment](deployment)
* [License](#license)
* [Questions](questions)

## Mock-Up

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia Core:

![In Insomnia Core, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia Core:

![In Insomnia Core, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./Assets/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia Core:

![In Insomnia Core, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./Assets/13-orm-homework-demo-03.gif)


## Usage:

 The database create 3 tables that are joined where needed through Sequelize in the routes files. The tables themselves are created and modeled through the models present in the models folders and again make use of Sequelize syntax.

This database contains the following four models, including the requirements listed for each model:

* `Category`
   * `id`
   * `category_name`

* `Product`
   * `id`
   * `product_name`
   * `price`
   * `stock`
   * `category_id`

* `Tag`
   * `id`
   * `tag_name`

* `ProductTag`
   * `id`
   * `product_id`
   * `tag_id`
## Installation:

  * Connects to a MySQL database using the [MySQL2](https://www.npmjs.com/package/mysql) and [Sequelize](https://www.npmjs.com/package/sequelize) packages.

  * Stores sensitive data, like a user’s MySQL username, password, and database name, using environment variables through the [dotenv](https://www.npmjs.com/package/dotenv) package.  

  ### Deployment: 

The following links show the web application's appearance and functionality: 

* A walkthrough video demonstrating the functionality of the application and all of the acceptance criteria being met.

  [Demo video link Part-1](https://drive.google.com/file/d/1siSVZ3jlANPjw4ZyT8cGcmU9Y-OhDef5/view)

  [Demo video link Part-2](https://drive.google.com/file/d/1fSCD5DvrHDHm769JwtVeuM9zbDINvYBC/view)

* The URL of the GitHub repository:

https://github.com/kajalpatel20/E-Commerce-Back-End

## License:
 APACHE 2.0

  [![Github License](https://img.shields.io/badge/license-APACHE 2.0-blue.svg)]
## Questions:

The repo for this project can be found here: 

https://github.com/kajalpatel20/E-Commerce-Back-End

For any questions or to report issues, email me at: kajalpatel20@gmail.com
