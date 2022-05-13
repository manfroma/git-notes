# git notes

clone 
    - Copy a remote rposititory
add
    - Track your files and changes in git
commit
    - Save your files in git
    - commint messages are mostly written in 
push 
    - Upload git comit to a remot repo / e.g. github
pull 
    - Download changes from remote repo to your machine
    the opposit of push. 



init
add
commit -m 'my first comit'
remote add origin git@githu.com:username/reponame.git
push -u origin master
 

# cloning an existing repository

1. clone repo

clone git@github.com:user-name/repo-name

- files will be downloaded
- git:(master)
- .git is a hidden folder (blue = folder), recorded all changes. 
    ls -la      // show hiden folders
- 

2. status 

- modified files: 
- untraked files: 

3. add .

- . add everything 
- add file-to-track.txt 
- added and ready to be commited 

4. commit -m "Message behind the comming being made" 

- response with number of files added &// modified 
- commint is only saved locally not on remote repository (git-hub)
- 

5. push origin master 

- origin : location of git repository (origin = where it comes from)
- master : a branch we would like to push to


6. create an ssh key 

ssh-keygen -t rsa -b 4096 -C 'email-address-used-on-git@some.com'

- .put is public key should be put on git-hub. 
- cat key.pub
    - Starts with ***ssh-rsa*** and ends with an ***email address***
- copy a key
    - pbcopy < ~/key.pub 
        - ~ it's in a home directory. 



# creating from file system

1. init
    - initialize a git repository 
2. status
    - therw 

add 'file-name'

3. commit -m 'message' 

4.  git push origin master 

- Error: origin is not a git repository. 

5. remote add origin git@.....git

6. git push -u origin master 

