Cryptography Project
The complete project Presentation is available here: 
https://drive.google.com/file/d/1YwjJLCz2ddRsHbLYXA8Ff7t-hQd6gW5f/view?usp=sharing
-------------------------------------------------
Title: Smart Contract using BlockChain

-------------------------------------------------
Team Details:
1. Aniruddh Gupta --- 2017A7PS0149H
2. Tabish Javed   --- 2017A7PS0151H
3. Shikhar Tayal  --- 2017A7PS1392H

-------------------------------------------------
How to run the code: 
-------------------------------------------------
1. Open BlockChain folder and open BlockChain.cbp 
2. Run main.cpp
3. Our program is designed for 6 (user0 to user5) users
   Each will have Rs-100 at the start of program
4. They have the following ID(or password) to authenticate the transaction

user	ID
----------
user0	0
user1	1
user2	2
user3	3
user4	4
user5	5

5. On pressing 1, we enter the TRANSFER menu
- We have to give input in the following syntax
 "useri userj user_id x" (where 0<= i <=5, 0<= j <=5 and j!=i , 0<= user_id <=5 , x is the money to be transferred)
 This transfers Rs-'x' from 'useri' to 'userj' if 'user_id' is correct 

-If we type correct id for a user and transaction is successful, it will show Block mined is successfull along with its hashed value and date-time of mining.

-If we type wrong id, transaction will be unsuccessful.

-If we attempts to transfer more money that what is available in a user's wallet, transaction will be unsuccessful

6. We can also see  transaction history for any user.
For that we have to type 2 to enter TRANSACTION HISTORY menu
After that we can type 'useri' to view all transcations of 'useri' (where 0<= i <=5)

7. To exit the program, we can press 0
