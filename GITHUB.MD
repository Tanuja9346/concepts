### ssh authentication

1. upload the public key in github server.
2. create a file called config in .ssh folder inside user directory.

one account
Host github.com
 Hostname github.com
 User git
 Identityfile ~/daws74

another account#
Host github.com-t
 Hostname github.com
 User git
 Identityfile ~/daws74

 ~ = user directory u/users/cheri.

 ##this line tells ur referring to another github account

git remote add origin git@github.com-t:Tanuja9346/concepts.git.

# here we saw two things i.e already existing folder how to converted it as git using "git init" command
 and create a repo in github server
 connect local and central repo through git remote add orgin < make sure connect through ssh>
  this is more flexible bcz no need to give username and pswrd again and again so u can easily push and pull.




