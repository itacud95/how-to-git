# how-to-git

## create repo 
1. Create new repo: https://github.com/new
2. Set repository name
3. Check: 'add readme file'
4. 'Create repository'

## clone repo
goto desired directory
```
cd dev/
```

Clone github repo link
example:
```
git clone <repo-link>
```

## git ssh keys
1. open terminal and run `ssh-keygen`
2. press enter when asked for file
3. press enter when asked for password
4. press enter again to confirm
5. look for output `Your public key has been saved in <filename>`
6. run command `cat <filename>`
7. copy output of command
```
ssh-keygen
Generating public/private ed25519 key pair.

<set filename>
Enter file in which to save the key (/home/jk/.ssh/id_ed25519): my-temp-key
```
1. go to keys setting: https://github.com/settings/keys
2. 'New SSH key'
3. set name
4. copy output from ssh file