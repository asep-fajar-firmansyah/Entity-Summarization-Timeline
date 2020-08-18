# Entity-Summarization
## Docker Ubuntu cases
### 1. UnicodeDecodeError: 'ascii' codec can't decode byte 0xe2 in position 13: ordinal not in range(128)
This case is caused by language packaage is not installed. 
Solution: 
```
apt-get install language-pack-en-base
```

And then, adding UTF-8 to .bashrc
```
export LC_CTYPE=en_US.UTF-8
```

Don't forget to reload .bashrc afterwards:
```
source ~/.bashrc
```

## Anaconda
### 1. Change python versin on anaconda
To change python version on anaconda, you can follow this instruction on this link:
https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands
