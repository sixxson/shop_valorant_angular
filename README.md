# shop_valorant_angular
web e-commerce

Install Angular Framework:

Download and install the Angular Framework by following the instructions on the official Angular website: angular.io.
Replace Source File:

Replace the default src file in your Angular project with the provided file.
Install json-server:

Install json-server globally by running the following npm command:
bash
Copy code
npm install -g json-server
Start json-server:

Navigate to the directory containing your JSON data file.
Start json-server by running the following command, replacing data.json with your JSON file's name:
bash
Copy code
json-server --watch data.json
This command starts a local server hosting your JSON data at http://localhost:3000.

Run the Angular Project:

Open a terminal and navigate to your Angular project directory.
Start the Angular project by running:
bash
Copy code
ng serve
Accessing Data:

Your Angular application can now make HTTP requests to http://localhost:3000 to fetch and manipulate data from your JSON file.
Ensure that you have Node.js and npm installed before following these steps. If not, download Node.js from the official website: nodejs.org. Also, make sure your JSON data file (data.json) is available in the correct directory before starting json-server.
