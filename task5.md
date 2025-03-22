# Task 5

## Install Maven
```bash
sudo apt install maven
```
![image](https://github.com/user-attachments/assets/a1c7b760-d02d-403d-8213-48898f1ce463)



## Configure Jenkins
 - In Jenkins go to `configure jenkins` > `tools`
 - Locate JDK section
 - Uncheck `Install Automatically`
 - Name `Java 17`
 - Go to terminal and enter the command and get the java 17 path:

```bash
update-java-alternatives --list 
```

 - paste the java path in `JAVA_HOME`
![WhatsApp Image 2025-03-22 at 2 18 33 PM(1)](https://github.com/user-attachments/assets/c9071f30-8335-400f-99a3-156d96771e0d)


## Fork The Repo and build the pipeline
![WhatsApp Image 2025-03-22 at 2 18 33 PM](https://github.com/user-attachments/assets/c8641a8e-2759-4a48-9f28-ce1c438d38ca)
