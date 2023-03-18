# Solution of find me

1- setup foxy proxy for firefox( or any other proxy)
<img align="center" width="300" height="300" src="./images/1.png">
2- start burpsuite and go to intercept and turn it 
3- turn on proxy
4- login using username:test and password=test!
5- go to burpsuite and forward the first request to get the first part of the flag from the redirect url
<img align="center" width="300" height="300" src="./images/2.png">
6-  re forward the second request to get the second part
<img align="center" width="300" height="300" src="./images/3.png">
7- decode the 2 parts using cyber or cmd
<img align="center" width="300" height="300" src="./images/4.png">