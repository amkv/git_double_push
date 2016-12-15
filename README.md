# git_push_2_repositories

make a copy of your config file in the .git folder
```
cd .git
cp config config_g
```

change the url variable in config_g
```
url =  https://github.com/your_login/project.git
```
go back

```
cd ../
```

and clone 
```
git clone https://github.com/amkv/git_push_2_repositories.git
```

move sh_push script to your project folder
```
mv git_push_2_repositories/sh_push .
```
change permissions
```
chmode 755 sh_push
```
run
```
./sh_push
```
