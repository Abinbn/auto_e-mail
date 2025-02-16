[![](https://visitcount.itsvg.in/api?id=Abinbn&label=Views&icon=5&pretty=false)](https://visitcount.itsvg.in)
# auto_e-mail 
It is a learning curve for me. I learned how to include the mailto feature in the website for feedback and queries.
When the button is pressed it opens the Gmail app with a pre-set Recipient, Body and Subject

### Link which helps to send mail
```
mailto:example@gmail.com?subject=Just%20to%20Say%20hello&body=hai%20I%20am%20a%20huge%20fan
```
# Explaining the Link

The link can be divided into 3 parts

1. Recipient
    ```
    mailto:example@gmail.com
    ```
2. Subject
    ```
    subject=Just%20to%20Say%20hello
    ```


3. Body
    ```
    body=hai%20I%20am%20a%20huge%20fan
    ```
    
# Other link elements
The link contains other elements too if we breakdown the link it looks like this 
   `mailto` `:` `example@gmail.com` `?` `subject` `=` `Just%20to%20Say%20hello` `&body=` `hai%20I%20am%20a%20huge%20fan`
    
In the subject and body between each word, the space is maintained by adding `%20`.

# In the mail it looks like this. 

![image](https://github.com/Abinbn/auto_e-mail/assets/82628577/dab4099c-d427-48c1-ab08-ae580542dfba)

# In the bottom Left of the page when hovering the button or link you can view the format 

![image](https://github.com/Abinbn/auto_e-mail/assets/82628577/d170cc92-e59b-4736-ac50-397345422878)

# In case of form
If you need to collect data by adding pre-submitted text such as `Name``Phone Number` `Address` etc you should add;
```
%0D%0A
```
The link looks like this 
```
Name%0D%0APhone%20number:%0D%0AAddress:
```

