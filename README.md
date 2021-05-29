# Welcome to mohican

## What's mohican?
Mohican is a free, open-source web server made for UNIX systems.

Features:
* Mohican can process http requests.
* Mohican can connect to other web-servers.
* Mohican uses config file to get information.
* Mohican is controlled by command line.
* Mohican writes information into logs.

## List of commands
### Start mohican web server
```
$ sudo ./mohican.sh start
```

### Create new config
```
$ sudo ./mohican.sh create config
```

### Get status
```
$ sudo ./mohican.sh status
```

### Reload mohican web server

#### Reload hard
```
$ sudo ./mohican.sh reload hard
```

#### Reload soft
```
$ sudo ./mohican.sh reload soft
```

### Stop mohican web server

#### Stop hard
```
$ sudo ./mohican.sh stop hard
```

#### Stop soft
```
$ sudo ./mohican.sh stop soft
```

## Before start
### You need to install boost library
```
$ sudo apt-get install libboost-all-dev
```
