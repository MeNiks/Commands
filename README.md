# Commands

### Zip
```
zip -r folder.zip folder
```

### Unzip
```
unzip -d folder_unzip folder.zip
```
```
-d - Destination folder
```
```
tar -xvf myfile.tar // To unzip tar
```
```
tar -xzvf myfile.tar.gz // To unzip tar.gz
```
```
tar -xvf myfile.tar -C somedirectory // -c to extract to some directory
```
```
gunzip jdk-7u80-linux-x64.tar.gz // This will remove gz final file will be jdk-7u80-linux-x64.tar
```

### Move/Rename
```
1. mv /home/abc.txt /home/new_location/
move abc.txt to new location
```
```
2. mv -v /home/wordpress/* /home/new_location/
Move all files inside wordpress to new location

```
### Remove
```
rm file.zip - //Delete zip file
```
```
rm -R directory - //Recursively delete all files inside directory
```

### List Files
```
ls -1lh - // -1 Listing vertically -l File Information h - Human readable file sizes
```

### Remove Directory
```
rm file.zip - //Delete zip file
```
```
rm -R directory - //Recursively delete all files inside directory
```

### Export Path
```
export PATH=$PATH:/home/abc/soft/temp/jdk1.7.0_80/bin
```
```
export JAVA_HOME=/home/abc/soft/temp/jdk1.7.0_80
```
