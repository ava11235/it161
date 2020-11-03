

# Publishing your website #
When you are ready to publish your website, you will need to upload your files to a web server. 
There are many web hosting providers to chose from. Always do your own research.  

Two hosting solutions to consider are Dreamhost (paid) and GitHub (free, but more limited than Dreamhost).

# The details: #

## What is a web server? ##

A web server is a computer configured with web server software to which you will upload your website's files such as HTML, CSS and JavaScript files.
The web server is connected to the internet and whenever a browser makes an HTTP request, the web server accepts the requests, processes it, and sends it back to the browser.
For more details see [this](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_web_server) article.

In addition to web hosting plan on a web server, you will need a domain. 
The domain is a human-friendly address mapping to an IP address. You can register domain names on many places, including the web hosting company you have chosen, such as Dreamhost.  For more details on domain names, see [this](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name) article.


## General steps to uploading your files to a web server ##

Two of the options you can chose from when you are ready to upload your files to a web server.

1. SFTP with a client such as FileZilla. See a FileZilla SFTP client step tby step guide [here.](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Upload_files_to_a_web_server)
2. GitHub allows you to publish websites on it for free. See step by step guide [here.](https://pages.github.com/)
3. The web interface of the web hosting provider. Directions will very from provider to provides. You can find the documentation on their website.

For more details see this article [this](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Upload_files_to_a_web_server) article. 

## Dreamhost ##

Dreamhost is a great paid option. It can host simple websites, as well as websites built with PHP and with a MySQL database back end.  In addition, Dreamhost is great for running Wordpress sites. 
**Important** Unless you are planning to host a WordPress site, **uncheck** the Wordpress 1 click install when setting up your hosting.
For this class you will not be working with Wordpress. It is easy to install WordPress later if needed.  If you forget to uncheck Wordpress, you will need to contact DreamHost tech support, who will help you uninstall it, but it is a lot easier to uncheck it.

https://www.dreamhost.com/hosting/shared/

Here is a tutorial on uploading your website to Dreamhost. Scroll down to Scroll down to the section Uploading website files in an FTP client)
https://help.dreamhost.com/hc/en-us/articles/215613657-How-do-I-upload-my-site-to-DreamHost-

Login Panel: When you sign up with Dreamhost, Dreamhost will create your login with your email and password. You will be logging in to Dreamhost via the panel to manage your domains and hosting: https://panel.dreamhost.com/

However, you will need a different login credentials for FTP.  Those will be  emailed to you by Dreamhost. Keep an eye for Dreamhost messages after you have setup and paid for your account. 

Due to DNS propagatio it can take up to 24 hours for your domain to be available for viewing. You will see a "Coming soon" message until your domain is ready.


## GitHub Pages ##

Github pages is a great free solution for hosting static web pages. You can host more than one website by creating a repository for each website.
and adding index.html to each repository.
https://pages.github.com/


## FileZilla SFTP client ## 
One of the ways to upload files to a web server is by using an FTP client such as FileZilla.
https://filezilla-project.org/download.php?platform=win64


## Learning Outcomes
Upon successful completion of the material covered in this section, students will be able host their website on a webserver and display it on the internet.

 
