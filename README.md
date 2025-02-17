# Unsplash
Spice up the Zimbra with random images from unsplash.com.

### Installing
To show random image on login screen: Open the following file using nano/vi on your server /opt/zimbra/jetty/webapps/zimbra/public/login.jsp and append before `</body>` the following css:

         <style>
         .LoginScreen {
             background-color    : #777 !important;
             background-image    : url('https://source.unsplash.com/random/featured/?nature') !important;
             background-position : center;
             background-repeat   : no-repeat;
             background-size     : cover;
         }
         </style>

### Bonus zimlet
This Zimlet shows random image in the top of the Zimbra UI after the user is logged in.

      mkdir /opt/zimbra/zimlets-deployed/_dev/tk_barrydegraaff_unsplash
      mkdir /opt/zimbra/zimlets-deployed/_dev/tk_barrydegraaff_unsplash
      wget https://raw.githubusercontent.com/Zimbra-Community/unsplash/master/tk_barrydegraaff_unsplash/tk_barrydegraaff_unsplash.xml -O /opt/zimbra/zimlets-deployed/_dev/tk_barrydegraaff_unsplash/tk_barrydegraaff_unsplash.xml
      wget https://raw.githubusercontent.com/Zimbra-Community/unsplash/master/tk_barrydegraaff_unsplash/tk_barrydegraaff_unsplash.css -O /opt/zimbra/zimlets-deployed/_dev/tk_barrydegraaff_unsplash/tk_barrydegraaff_unsplash.css


### Screenshots

![alt text](https://github.com/Zimbra-Community/unsplash/raw/master/2019-05-29-095906_1920x1080_scrot.png)
![alt text](https://github.com/Zimbra-Community/unsplash/raw/master/2019-05-29-095919_1920x1080_scrot.png)
![alt text](https://github.com/Zimbra-Community/unsplash/raw/master/2019-05-29-095926_1920x1080_scrot.png)
![alt text](https://github.com/Zimbra-Community/unsplash/raw/master/2019-05-29-095929_1920x1080_scrot.png)
![alt text](https://github.com/Zimbra-Community/unsplash/raw/master/2019-05-29-095933_1920x1080_scrot.png)
![alt text](https://github.com/Zimbra-Community/unsplash/raw/master/2019-05-29-100014_1920x1080_scrot.png)
![alt text](https://github.com/Zimbra-Community/unsplash/raw/master/2019-05-29-100026_1920x1080_scrot.png)


![alt text](https://github.com/Zimbra-Community/unsplash/raw/master//2019-05-29-103548_1920x1080_scrot.png)
![alt text](https://github.com/Zimbra-Community/unsplash/raw/master//2019-05-29-103558_1920x1080_scrot.png)
![alt text](https://github.com/Zimbra-Community/unsplash/raw/master//2019-05-29-103606_1920x1080_scrot.png)
