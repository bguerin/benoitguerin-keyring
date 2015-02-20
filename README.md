benoitguerin-keyring
============================

This project contains the [Debian](https://www.debian.net/) packaging of my public key used to sign
my personnal packages and [repository](http://bguerin.github.io/debian/).

## Usage

Either manually
```
wget -O- https://github.com/bguerin/benoitguerin-keyring/raw/master/keyrings/benoitguerin-keyring.gpg | sudo apt-key add -
```

or "automatically"
```
echo "deb http://bguerin.github.io/debian wheezy main" > /etc/apt/sources.list.d/bguerin.list
apt-get update
apt-get install benoitguerin-keyring
```

## CI
[![Build Status Images](https://travis-ci.org/bguerin/benoitguerin-keyring.svg)](https://travis-ci.org/bguerin/benoitguerin-keyring)

## License

This is all under [GPL-2](http://www.gnu.org/licenses/gpl-2.0.html)
