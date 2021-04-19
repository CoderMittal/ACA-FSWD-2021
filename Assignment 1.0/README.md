# CMD Commands learnt by me
### Change directory
This command helps to change the current directory(Folder).Type cd followed by the location of the folder you want to go and then press Enter Key.
* Command **cd..** take you one folder back of the current directory.
* Command **cd\\** takes you the top of directory tree.
### View content in a directory
This command shows you all the files and folder contained inside the directory.Just type command *dir* and then press Enter Key.
### Make new Directory
This command helps to make a directory.Just use command **mkdir File_Name** and then press Enter key.
### Rename a File or Folder
This command helps to rename a file or directory.Use Command **ren Old_Filename New_Filename** and then press Enter key.
### Copy a File
This command Helps you to copy a file from one location to another.Use command **copy location\filename.ext location\filename.ext** and then press Enter Key.
### Copy a Folder
This command Helps you to copy a folder from one location to another.Use command **xcopy /s /i location\filename.ext location\filename.ext** and then press Enter Key.
* The "/s" ensures all non-empty directory and subdirectories are copied.
* The "/i" creates new folder incase newlocation is not created.
### Delete the file
Deletes the files from a folder.Can also delete all files from Folder.Type command **del Filename** and then press Enter.
* To delete hidden files also use "/h" parameter.
### Delete the folder
Deletes a folder.Type command **rd Foldername** and then press Enter.
### Help from CMD
To know about various command of CMD just type **help** and then press Enter.
<br><br><br>
# Various Terms

## Client-Side
A client refers to application which is present on local devices(like Laptop,Tablet,etc.) of the user.Client-side is place where operations given are from device of the user and the result is dispalyed to the user.
In Web development,languages like HTML,CSS and JavaScript is used to make interface for the users like web pages on the browser.


## Server-Side
Similar to Client-side is also the place where various functions are performed but this time on the server.Whenever a client request any service all the required data is passed from server to the client and then it is accessible to the client.Example,Whenever you login to any social flatform,then you(client) gives your data like id,password,etc which is then used to by the server to verify is it you and then take actions accordingly.


## HTTP Protocols
HTTP forms the foundation of any data exchange performed on the World Wide Web.This allows fetching of resources like HTML docs,videos,ads,images,etc.HTTP Protocols is client-Server protols which means the client(usually Web browser) initiates a request from browser,then the request results in a respond which is reconstructed from various sub-sections and then is received by the client.Clients **"Requests"** which is then sent by server as **"Responds"**.
Between client and server there are **Proxy** which performs different operations.


## HTTP *v/s* HTTPS
HTTP | HTTPS
------------ | -------------
It is unsecured | It is secured
It uses Port 80 | It uses Port 443
No SSL certificate is required | SSL certificate is required
It doesn't requires domain validation | It requires at least domain validation and certain certificate
Data is not Encrypted | Data is Encrypted

# Library *v/s* FrameWorks
Library Provides inbuilt Functions/objects/modules which can be used in application code which makes code efficient.Library helps in code reuse,code developed earlier by someone else.
We have the control in libraries i.e we call out what method or function we want to use.

FrameWorks provides user with the template or skeleton of unimplemented functions which tells users what to write in making a application.It can be assumed as fill up the blanks.
In frameworks the control is with frameworks i.e frameworks call us.