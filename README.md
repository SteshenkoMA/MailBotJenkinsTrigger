# MailBotJenkinsTrigger
A program that:

1) connects to MS Exchange server (EWS)
2) reads inbox letters with specific subject
3) parses the json request
4) if request contains Jenkins tasks, it triggers these tasks at Jenkins server

Main libs:
а) ews-java-api
б) jenkins-cli
