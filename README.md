# BankingManagement
A Banking transaction management system to simulate the common functions of a bank account

COMPILE-
gcc data.c -o data   

gcc server.c -o server

gcc client.c -o client

RUN-
./data    ---  only used to add the initial data/records into files.

./server  ---  first in one terminal

./client  ---  in the other terminal

CLIENT-
1.You have three options : Normal User login, Joint User login, Admin login.

2.Login with your credentials.

3.If successful you get different options then you choose one of them to perform its action.

SERVER-
1.The server checks the login credentials entered by the client.

2.Performs the actions chosen by the client.

3.Implements suitable write and read locks when required.
