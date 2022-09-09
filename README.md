"# ESP8266TcpSocket" 
Send USB-TTL to ESP8266 this AT command:

AT //check esp
AT+CWLAP //list wifi
AT+CWMODE? //learn mode
AT+CWJAP="myWifi","myPassword" //connect to wifi
AT+CIPSTART="TCP","192.168.43.241",8001" //connect your server and use IP adress
AT+CIPSEND=10 //10 char send
AT+CIPCLOSE // disconnect server

For tcp server:
https://foxlearn.com/articles/chat-tcp-ip-client-server-in-csharp-98.html


