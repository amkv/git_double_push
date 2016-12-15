# git_push_2_repositories

make a copy of your config file in .git folder
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

clone 
```
git clone
```

change permissions
```
chmode 755 sh_push
```
run
```
./sh_push
```
