# Entity-Summarization
## Docker Ubuntu cases
### 1. UnicodeDecodeError: 'ascii' codec can't decode byte 0xe2 in position 13: ordinal not in range(128)
This case is caused by language packaage is not installed. 
Solution: 
```
apt-get install language-pack-en-base
```