Docker OWASP Bricks
===================
![alt text](http://sechow.com/bricks/images/bricks.jpg "Bricks")
Docker container for [OWASP Bricks](http://sechow.com/bricks/)

Bricks is a web application security learning platform built on PHP and MySQL. The project focuses on variations of commonly seen application security issues. Each 'Brick' has some sort of security issue which can be leveraged manually or using automated software tools. The mission is to 'Break the Bricks' and thus learn the various aspects of web application security.

Bricks is a completely free and open source project brought to you by OWASP. The [complete documentation](http://sechow.com/bricks/docs/) and [instruction videos](https://www.youtube.com/OWASPBricks) can also be accessed or downloaded for free. Bricks are classified into three different sections: login pages, file upload pages and content pages.


How to start
============

Just run docker container:

```docker run -d -P 80:80 citizenstig/owaspbricks```

And setup database via Web.
