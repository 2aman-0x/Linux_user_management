## Linux User Account Management

- __Topics__  
```useradd```  
```userdel```  
```usermod```  
```groupadd```  
```groupdel```  

- __Files__  
``` /etc/passwd```  
``` /etc/group```  
``` /etc/shadow```

### How to Create a USER?
- ```useradd user_name```
- ```useradd -g group_name -s /bin/bash -c "description" -m -d /home/user_name user_name```

### How to check user information or USER created or not?
- ```id <user_name>```
- ```less /etc/group```

### How to delete user?

- ```user del <name_of_user>```
- ```user del -r``` (Will remove home directory)
- ```user del -f``` (force delete even if the user is logged in)

