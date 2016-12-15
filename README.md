# git_double_push

This simple script helps you to push your projects files to 2 git repositories, 
the script simply changes the config file name after first push, then change second config file name and push again.

make a copy of your config file in the .git folder
```
cd .git
cp config config_g
```

change the url variable in config_g
```
url =  https://github.com/your_login/your_project.git
```
go back and clone

```
cd ../
git clone https://github.com/amkv/git_double_push.git
```

move sh_push script to your project folder
```
mv git_double_push/sh_push .
```
change permissions
```
chmode 755 sh_push
```
launch
```
./sh_push
```
or

```
./sh_push "text to commit"
```
