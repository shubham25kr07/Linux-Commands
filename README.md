# Linux-Commands 

#        INSTALL MYSQL IN UBUNTU 

WRITE THE FOLLOWINGS COMMANDS IN TERMINAL(ctrl+alt+T):-    

1) sudo apt update

2) sudo apt install mysql-server

3) sudo mysql

4) Enter password: (your system password)

5) mysql> ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'P_A_S_S_W_O_R_D';  
          // P_A_S_S_W_O_R_D --- your new password for root
          
6) mysql> FLUSH PRIVILEGES;

7) mysql> exit

NOW, TO OPEN MYSQL IN TERMINAL(Ctrl+alt+T)  WRITE:-

1) mysql -u root -p

2) Enter password: P_A_S_S_W_O_R_D

3) mysql> 


