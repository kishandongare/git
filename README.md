# git
>> kishan@kishan25:~$ sudo apt-get install git
>> kishan@kishan25:~$ sudo add-apt-repository ppa:git-core/ppa
>> kishan@kishan25:~$ sudo apt-get install git
>> kishan@kishan25:~$ git --version
>> kishan@kishan25:~$ git config --global user.name kishandongare
>> kishan@kishan25:~$ git config --global user.email kishan.tech25@gmail.com
>> kishan@kishan25:~$ cd hellow
>> kishan@kishan25:~/hellow$ git init
>> kishan@kishan25:~/hellow$ git add .
>> kishan@kishan25:~/hellow$ git commit -m "first commit"
>> kishan@kishan25:~/hellow$ git status
# create ssh key(authentication)
>> kishan@kishan25:~/hellow$ ssh-keygen (for left just press enter enter)
>> kishan@kishan25:~/hellow$ cat /home/kishan/.ssh/id_rsa.pub (check downloaded key enter and copy all)
# upload key in settting>SSH and GPG keys>New SSH key
>>kishan@kishan25:~/hellow$ git push -u origin main



