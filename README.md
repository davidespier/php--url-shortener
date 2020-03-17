![url-shortener](http://davidespier.com/img/appweb/shorturl.png)

# URL-SHORTENER
Save your images in the cloud.  Project made with javascript and firebase.

## Requirements

- Php 5.6.
- Mysql.

(You can use usbwebserver, xampp or hosting web)


## Installation

1. Upload file (/database) in your database.

2. Update (/config) files config, register and login, access data from the database.

3. Add your domain in this line of code.

               
   Line 111 (/anonymous.php).

        <a id='num' href='index.php?url=".$shorturl."'>http://your-domain/index.php?url=".$shorturl."</a>";


   Line 33 (/config/func/func.php)
   
        <a id='num' href='index.php?url=".$shorturl."'>http://your-domain/index.php?url=".$shorturl."</a>";
       
        
4. Run

## Website project

http://davidespier.com/pages/urlshortener/main.php


## Authors

 *Developed and designed by*  **David Espier**


[Personal website](https://davidespier.com)

[Alexa skills](https://www.amazon.es/s?k=davidespier&i=alexa-skills)
        
[Other projects](https://github.com/davidespier?tab=repositories)



## License


[MIT License](https://choosealicense.com/licenses/mit/) © davidespier.com
