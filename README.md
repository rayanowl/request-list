# REQUEST LIST / COMMANDS

Request List for Students &amp; Projects

Visual Studio Code and Postman are used.

# "Explanation"

*db.json file contains students and their projects. 
Filtering was applied for students and projects,
New items were created, 
A specified feature was deleted and updated.

# "Notice"

*When the PUT command is used, it has been observed that all the remaining features are deleted, except for that item. 
Therefore, the PATCH command is used for update.

# "Stages"

-Download Postman-
https://www.postman.com/downloads/

-Download Json-server-
1. Open Command Promt
2. Write cd Desktop
3. Create a folder; To Do: mkdir foldername
4. Write cd foldername
5. Write mkdir db.json
6. And write npm i -g json-server
7. Write code . and add list to your file.

-Create Request on Postman-
 1. Write json-server --watch db.json and your localhost will be out.
 2. Create a Collection
 3. Create Requests (GET,PUT,PATCH,DELETE,POST)
 4. Enter your local host. 
 
 *Get: Gets all of your list.
 
 *Post: Add a new item to list. For example: write /users and send. A new item with id will be created.
 
 *Put: It will update the items you selected, but data will be lost. 
 
 *Patch: It only updates the items you selected. No data loss.
 
 For Put & Patch : come to Body, select raw and change Text to JSON. 
 raw section: write "description" : "IOS App" and click send.
 
 *Delete: For example: write /users/id number
 
 *Get for filtering: For example: Come to Params, write the parameters you want to display and click send. 
 Or you can write like this: /users?school=BAU
