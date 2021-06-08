# google-docs-clone

### To Run Server:
1) Open server folder

2) To install node packages run:
``` bash
npm i
```
3) Now run server.js file by
``` bash
node server.js
```
4) In server.js on line 13 IP Address and port no are given of client app.
If client app is running on different address and port,
Then change it according.


### To Run Client App

1) Open client app
2) To install packages run 
``` bash
npm i
```
3) Now run app by:
``` bash
npm start
```
4) Now in "src/TextEditor.js" line 29 IP Address and port no are given of server.
If server is running on different address and port,
Then change it according.


### Important Points to Note:

<li> Make sure mongoDB is running 
<li> In url after "/documents/" the string is Id to that document
<li> Specific documents can be accessed by Id directly passing in url
<li> Same doc can be accessed from diff devices if they are connected to same server and both have same Id.
