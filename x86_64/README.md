### install
Run as shell
```
wget https://raw.githubusercontent.com/BonusCloud/BonusCloud-Node/master/x86_64/install.sh -O install.sh&&sudo bash install.sh
```
### remove
```
wget https://raw.githubusercontent.com/BonusCloud/BonusCloud-Node/master/x86_64/install.sh -O install.sh&&sudo bash install.sh remove
```

The system passed the test
- ubuntu-18.04.02 4.15.0-45-generic [Download](https://www.ubuntu.com/download/server)
- debian-9.9 4.9.168-1 (2019-04-12) [Download](https://www.debian.org/distrib/)

### bound
```
curl -H "Content-Type: application/json" -d '{"bcode":"xxxx-xxxxxxxx","email":"xxxx@xxxx"}' http://localhost:9017/bound
```
or use APP

