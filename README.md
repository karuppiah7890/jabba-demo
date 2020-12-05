# jabba-demo

This is a demo of how to get started with Jabba

```bash
$ curl -sL https://github.com/shyiko/jabba/raw/master/install.sh | bash && . ~/.jabba/jabba.sh
$ jabba
$ jabba ls-remote
$ jabba install openjdk@1.11.0-2
$ jabba ls
$ jabba use openjdk@1.11.0-2
$ jabba link
$ jabba alias -h
$ jabba alias default openjdk@1.11.0-2
$ echo "openjdk@1.15.0-1" > .jabbarc
$ jabba use
$ java --version
openjdk 15.0.1 2020-10-20
OpenJDK Runtime Environment (build 15.0.1+9-18)
OpenJDK 64-Bit Server VM (build 15.0.1+9-18, mixed mode, sharing)
```

To avoid any possible confusions, I got rid of the brew installation of OpenJDK

