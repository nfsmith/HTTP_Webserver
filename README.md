# HTTP_Webserver
By: Nick Smith

This webserver, coded in C++, handles HTTP/1.0 and HTTP/1.1 GET requests. It supports file types with extensions .htm, .html, .txt, .gif, .jpg, and .jpeg. The server sends the client the file it requests if the file is found in the root directory and the file type is supported. The server also handles multiple simultaneous requests.

## Usage

+ Compile the server using the command "g++ -std=c++11 -o webserver webserver.cpp". This will create the executable file "webserver".
+ In the file 'ws.conf', replace the file path in quotes after 'DocumentRoot' with the filepath of the 'www' folder, or the files you'd like to host
+ Run this file using the command "./webserver". The server should now be running. Press enter in the terminal to end the server and close connections.
