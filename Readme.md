## Running the Program:
Open the Pokemon folder with Visual Studio Code
Open up two Terminals in Visual Studio Code

In the first terminal type "cd api" and hit enter
Then type "npm install" and hit enter
After the packages have finished installing type "node index.js" and hit enter
Assuming everything worked properly, in the terminal you should see:
"Connected to `bydgdkgmf8rlba5`!
Listening on localhost:8080"

Select the second Terminal and type "cd app" and hit enter
Then type "npm install" and hit enter
After the packages have finished installing type "npm start" and hit enter
Assuming everything worked properly, in the terminal you should see:
"Local: 		http://localhost:3000        
  On Your Network:  http://192.168.56.1:3000"
And it should automatically open up a webpage to "http://localhost:3000"    
     
## Primary Functions: 
Upon loading the webpage, It will "GET" a collection of Pokemon that it displays on a table

Each Row on the table that displays the collection of Pokemon has an Edit and Delete button

The Edit button allows the user to change the text fields into input boxes and clicking Confirm will
"PUT" the changes to the given Pokemon

The Delete button allows the user to "DELETE" the given Pokemon

At the top of the page is an Add New Pokemon Button and upon clicking it the user is presented
with four input boxes and clicking confirm while those input boxes are properly filled will "POST"
a new Pokemon to the collection. 
 

## Notable Elements:
The Table present on the webpage will automatically sort itself based on Pokedex number 
after any given render update except while the user is editing

Next to the text for "Type 1" and "Type 2" an associated Symbol for the given type will appear
This changes dynamically based on a given type and updates after editing as well.
