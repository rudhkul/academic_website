Thank you Cushen and Flip for this wonderful theme.

All you need to do is download the files in a folder on your PC.

Just change the permission of all the downloaded files by 'sudo chmod -R 777 .'

First, create a github repository -- username.github.io. Let the username be your github username.

Then link your github repo with downloaded files.

First, compile the downloaded website files by,

hugo server

You can load your website locally on PC by opening browser and going on -- http://localhost:1313/

Later, run this command in your website folder:

git submodule add -b master git@github.com:<USERNAME>/<USERNAME>.github.io.git public
  
Now just run this command -- './deploy.sh'

Everything should run fine.

Enjoy!
