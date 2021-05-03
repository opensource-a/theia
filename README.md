# theia
userdata for EC2
```
mkdir theia
cd theia
sudo docker run --init -dit -p 10443:10443 -e token=mysecrettoken -v "$(pwd):/home/project:cached" theiaide/theia-https:latest
```
