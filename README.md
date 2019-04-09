# MailBotJenkinsTrigger
A program that:

1) connects to MS Exchange server (EWS)
2) reads inbox letters with specific subject
3) parses the json request
4) if request contains Jenkins tasks, it triggers these tasks at Jenkins server

Main libs:

а) ews-java-api    
б) jenkins-cli    

More info read in "MailBot-v1.docx" (ru)

![diagram](https://user-images.githubusercontent.com/13558216/55802065-1dc2f180-5ae0-11e9-87ba-bfcad95b3eb4.png)
