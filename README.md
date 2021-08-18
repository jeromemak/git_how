#this is a git tutorial
###git creation
- git init -> this creats an empty repo
- git add . -> adds all file to ur temp repo
- git commit -m "name of commit" -> saves screen shot with a message
- git push origin master -> push the commit to the connected remote

###remote repo
- git clone url
- git remote add origin url
- git remote -v -> shows all connections
- git push -u origin master -> upstring to set push default


###generating ssh key
- ssh-keygen -t rsa -b 4096 -C "ctmakab@connect.ust.hk"
- then leave empty for passcode
-  ls | grep key -> search for the key
- key and key.pub -> key use math to gen key.pub -> put it in github to prof is u
-  cat key.pub -> show the key
- pbcopy < ~/Users/jeromemak/.ssh/id_rsa/key -> copy the key
   


