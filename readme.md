# File Store Bot

<p align ="center">
   <a href ="https://nodejs.org">
     <img src = "https://forthebadge.com/images/badges/uses-js.svg">
        </p>
   </a>
       

[![HITECH](https://img.shields.io/badge/LKHITECH-Channel-red?style=for-the-badge&logo=telegram)](https://telegram.dog/lkhitech)




Bot generates sharable link inside telegram for documents and make files public via inline search<br><br><br><br>
<center><img src ="https://telegra.ph/file/d2a35663b79c09cdc138c.png" alt = "FileStoreBot"/></center>

<a href="https://heroku.com/deploy?template=https://github.com/kjeymax/File-Store-Bot">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
<br><br>

<br>
<b>Required details</b> <br>


<code>TOKEN</code> - Get bot token from bot father

<code>DOMAIN</code> - Same as app name that you enter in heroku

<code>ADMIN</code> - your account id(if you cant find it use bots like [@getidsbot](https://t.me/getidsbot) )

<code>BOTUSERNAME</code> - your bot username without '@'

<code>DB_URL</code> - create an account on https://www.mongodb.com/cloud/atlas , database name - mediaFile ,collection name - fileBackup.Click connect and choose 'connect your application'.Copy the link and replace "< password >" with password of user having acess to db and replace "myFirstDatabase" to "mediaFile"

<code>LOG_CHANNEL</code> - create a private channel and get channel ID (if you cant get channel id forward any message from channel to [@getidsbot](https://t.me/getidsbot) it may look something like -1001234567899)  
<hr>

<h1>Here are some of the admin commands and usage</h1>


1.How to ban and unban users


<code>/ban</code> userID

<code>/unban</code> userID

(Get userID from log channel)


<h2>How to remove files from bot</h2>


you can remove files 3 ways

 ⚫ Remove individual files with file_id

 ⚫ Remove all files send by a user

 ⚫ Remove all files send to the bot


    Remove individual files with file_id

<code>/rem</code> file_id

(This will remove files one by one as you give file_id,Get file_id from log channel)


    Remove all files send by a user

<code>/remall</code> userID

(You can remove all files send by a particular user if user is sending abusive contents or spam ,Get the userID from log channel)


    Remove all files send to b0t

<code>/clear</code>

(This will remove all files send to the bot permenantly)


<h2>Send message to users</h2>

<code>/send</code> your message to be broadcasted

(You can broadcast text messages to your users ,the message will be send from last joined user to first joined user to reduce spam.Try not to send too many messages at a single time if you have a large number of users)


<h2>How to know total bot users</h2>

<code>/stats</code>

(You will get total users started your bot,Real time data will be updated after a succesfull broadcast)



<b>If you wish to support me follow me on github as a token of support</b>

