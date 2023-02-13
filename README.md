
## ♠︎ 𝐑𝐞𝐪𝐮𝐞𝐬𝐭 L𝐢𝐬𝐭𝐬 & C𝐨𝐦𝐦𝐚𝐧𝐝𝐬 

***Created request for students &amp; projects***

***Visual Studio Code and Postman are used.***


### ♥︎ ᴇxᴘʟᴀɴᴀᴛɪᴏɴ

*db.json file contains students and their projects. Filtering was applied for students and projects, new items were created, specified feature was deleted and updated.*


### ♥︎ ɴᴏᴛɪᴄᴇ

*When the PUT command is used, it has been observed that all the remaining features are deleted, except for that item. 
Therefore, the PATCH command is used for update.*


### ♥︎ sᴛᴀɢᴇs

***♦︎ Download Postman***
https://www.postman.com/downloads/

***♦︎ Download Json Server***

    ♣︎ Open Command Prompt
    ♣︎ Write cd Desktop
    ♣︎ Create a folder; To Do: mkdir foldername
    ♣︎ Write cd foldername
    ♣︎ Write mkdir db.json
    ♣︎ And write npm i -g json-server
    ♣︎ Write code . and add list to your file.


***♦︎ Create Request on Postman***

    ♣︎ Write json-server --watch db.json and your localhost will be out.
    ♣︎ Create a Collection
    ♣︎ Create Requests (GET,PUT,PATCH,DELETE,POST)
    ♣︎ Enter your local host.
 
 
 ## ♠︎ 𝐍𝐨𝐭𝐞𝐛𝐨𝐨𝐤
 
 ***♥︎ Get: Gets all of your list.***
 
 ***♥︎ Post: Add a new item to list. For example: write /users and send. A new item with id will be created.***
 
 ***♥︎ Put: It will update the items you selected, but data will be lost.***
 
 ***♥︎ Patch: It only updates the items you selected. No data loss.***
 
 ***♥︎ For Put & Patch : come to Body, select raw and change Text to JSON. 
 raw section: write "description" : "IOS App" and click send.***
 
 ***♥︎ Delete: For example: write /users/id number***
 
 ***♥︎ Get for filtering: For example: Come to Params, write the parameters you want to display and click send. 
 Or you can write like this: /users?school=BAU***
