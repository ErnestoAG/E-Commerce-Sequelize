# E-Commerce-Sequelize

## Description

Through the E-Commerce back end component, users can create a database to store inventory data using Sequelize. Users can view, add, update, and delete entries that represent products, categories, and tags using their corresponding routes.
   
Here is the link to a video walkthrough: https://www.loom.com/share/9ef819632da042e2a4f3c02d9703e2c8?sid=eb27517e-67ad-4b59-a6ab-270fcc1242fe
 
## Installation

If you are deploying the application from a local environment, you need to run "npm install" on the console to install dependencies. You can define seeds for the database using the seeds folder, which you can insert into your database by running the command "npm run seeds." Then use "npm server.JS" to open the server and send requests using Insomnia or other applications. You will need some environment variables which you can set up using a .env file.

## Usage

To see all entries, you can use the api routes with the GET command, there are 3 routes: api/products, api/categories, and api/tags. To see a specific entry, add the id value at the end of the route with a slash. For adding, modifying, and deleting entries, you need to specify their ids. Remember to use POST, PUT, and DELETE commands for each request when required. To add new entries using post, keep in mind that the product JSON object needs a product name, a price, stock, category id, and an array of tag ids. Category and tag JSON objects require names. 

## Credits

This application wouldn't have been possible without the help of the class content and the support of the TAs.

## License

Refer to LICENSE in the repo, it should be MIT License.
