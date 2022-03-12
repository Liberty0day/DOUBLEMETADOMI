# DOUBLEMETADOMI

## Metasploit Installer

THANKS : https://github.com/Dewalt-arch/pimpmykali  I was inspired by this script for the installation of metasploit5

NOTE: This script work with the version kali-rolling

SHOW:
### Distributor ID::: Kali Description::: Kali GNU/Linux Rolling Release::: 2021.4 Codename::: kali-rolling
```
echo $(lsb_release -idrc | sed 's/:/:::/g')
```
NOTE: This page is under construction!

## The Process

1. Select installation type local or remote, msf5 or msf6
2. Execute install for local and wait
3. For remote give user, passwd, ip of your kali and execute install


## Preliminaries
You need install this tools :

- zsh
- expect 
- wget

## Start
Enable ssh in your kali
```
service ssh restart
```
Now execute the script
```
zsh ./dmd.sh
```

## Example

### DOUBLEMETADOMI LOCAL MENU

```
----[ DOUBLEMETADOMI Version 0.0.0

[ 1 ] LOCAL  INSTALL MSF5 
[ 2 ] LOCAL  INSTALL MSF6 
[ 3 ] LOCAL  INSTALL MSF5 AND MSF6
[ 4 ] REMOTE INSTALL MSF5
[ 5 ] REMOTE INSTALL MSF6
[ 6 ] REMOTE INSTALL MSF5 AND MSF6

[ ? ] Give me your choice ]-------

```
### DOUBLEMETADOMI REMOTE MENU
```
----[ DOUBLEMETADOMI Version 0.0.0

[ ! ] Give your kali password

kali
```
### DOUBLEMETADOMI REMOTE MENU

```
----[ DOUBLEMETADOMI Version 0.0.0

[ ! ] Give kali user name
    
kali

[ ! ] Give your kali password
    
kali

[ ! ] Give the ip address of your kali
    
0.0.0.0
```


## VIDEO
  
[![IMAGE ALT TEXT HERE](https://i9.ytimg.com/vi/P_Ws-LLcreM/mqdefault.jpg?v=622bf9ec&sqp=CMDLsZEG&rs=AOn4CLCbgSIrkXFBBkOJRMsfPa7xKYYb5A)](https://www.youtube.com/watch?v=P_Ws-LLcreM)
