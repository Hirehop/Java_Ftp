# Java_Ftp
### 1.Description: 
This project use TCP Socket to realize FTP Server and Client, Console/Command with Windows;  
If you wanna it run in Linux, you can change The `runCommand` function in `FtpUserServiceImpl` and change working Directory in server/client code.  

### 2.Developing IDE
`MyEclipse 2017`

### 3.Structure of the projects
![](https://img-blog.csdnimg.cn/20200605235700537.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyMjkyODMx,size_16,color_FFFFFF,t_70)

### 4.The way deal with the end of the socket transferring
`EOT`: ASCII=4 &nbsp;->&nbsp;  Control Character &nbsp;->&nbsp; End Of Transfer  
`ENQ`: ASCII=5 &nbsp;->&nbsp;  Control Character &nbsp;->&nbsp; Existence of the file  

### 5.The way deal with the `.properties` file
|-ResourceBundle  
&nbsp;&nbsp;&nbsp;&nbsp;|-PropertyResourceBundle  
<br/>
<br/>
<br/>
#### >>>`Welcome`<<<
