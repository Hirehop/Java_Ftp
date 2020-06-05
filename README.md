# Java_Ftp
### Description: 
This project use TCP Socket to realize FTP Server and Client, Console/Command with Windows;
If you wanna it run in Linux, you can change The `runCommand` function in `FtpUserServiceImpl` and change working Directory in server/client code.

### Developing IDE
`MyEclipse 2017`

### Structure of the projects
![](https://img-blog.csdnimg.cn/20200605235700537.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyMjkyODMx,size_16,color_FFFFFF,t_70)

### The way deal with the end of the socket transferring
`EOT`:ASCII=4  ->  Control Character -> END OF FILE
`ENQ`:ASCII=5  ->  Control Character -> Existence of the file

### The way deal with the `.properties` file
|-ResourceBundle
  |-PropertyResourceBundle


#### >>>`Welcome`<<<
