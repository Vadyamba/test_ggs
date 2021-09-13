##  Basic work with files

- Create directory test1

```console
mkdir test
```

- Create file test1.txt inside the test1 directory.

```console
touch test1/test1.txt
```


-   Create copy of folder test1 with name test2.

```console
cp -avr test1 test2
```
  

-    Delete file test1.txt inside test2 directory.

```console
rm /test2/test1.txt
```


-    Rename test2 folder into directory_without_file

```console
mv test2 directory_without_fil e
```


-    Insert 'test1' text into test1/test1.txt file.

```console
echo "test1" >> test1/test1.txt
```


-    print the text from the test1/test1.txt file.

```console
less test1/test1.txt
```


-    Insert 'test2' into the end of test1/test1.txt file.

```console
echo "test2" >> test1/test1.txt
```


-    print the text from the test1/test1.txt file.

```console
less test1/test1.txt
```


- check the size of test1 directory

```console
du -sh test_ggc
```

## Permissions

-   Create test directory and block access for all to it.

```console
mkdir test3
chmod 000 test3
```


-   Try to remove that directory.

```console
rmdir test3
```


-    Create simple script which prints current date. Try to execute it.

```console
wsefr
```

## Log checking

-  Count lines in the file test.txt.


- Show last 3 lines from the test.txt file. 


-  Hom many uniq IP addresses accessed the website ? 


-  IP address with most requests.


-  Top 3 IP addresses by amount of POST requests.


-  Which IP addresses received 403 error ? 


- Task with * . Write script to show which pages Google checked from the website 

## Replace

Replace IP address with most requests on 127.0.0.1 in test.txt file 
