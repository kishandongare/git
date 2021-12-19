
# git installation command 

>> kishan@kishan25:~$ sudo apt-get install git

>> kishan@kishan25:~$ sudo add-apt-repository ppa:git-core/ppa

>> kishan@kishan25:~$ sudo apt-get install git

>> kishan@kishan25:~$ git --version

# git command to commit

>> kishan@kishan25:~$ git config --global user.name kishandongare

>> kishan@kishan25:~$ git config --global user.email kishan.tech25@gmail.com

>> kishan@kishan25:~$ cd hellow (project directory)

>> kishan@kishan25:~/hellow$ git init

>> kishan@kishan25:~/hellow$ git add .

>> kishan@kishan25:~/hellow$ git commit -m "first commit"

>> kishan@kishan25:~/hellow$git remote add origin git@github.com:kishandongare/kkkk.git

>> kishan@kishan25:~/hellow$git branch -M main

>> create ssh key(authentication)

>> kishan@kishan25:~/hellow$ ssh-keygen (for left just press enter enter)

>> kishan@kishan25:~/hellow$ cat /home/kishan/.ssh/id_rsa.pub (check downloaded key enter and copy all)

>> upload key in settting>SSH and GPG keys>New SSH key

>> kishan@kishan25:~/hellow$ git push -u origin main

>> git push --force origin main (if not work above)

>> kishan@kishan25:~/hellow$ git status

# create a new repository on the command line(By GitHub)

>> echo "# kkkk" >> README.md

>> git init

>> git add README.md

>> git commit -m "first commit"

# Git Large File Storage - https://git-lfs.github.com.
>> git branch -M main

>> git remote add origin git@github.com:kishandongare/kkkk.git

>> git push -u origin main


# push an existing repository from the command line(By GitHub)

>> git remote add origin git@github.com:kishandongare/kkkk.git

>> git branch -M main

>> git push -u origin main


