# Docker-Wordmove

## What's inside?
* wordmove
* rsync
* mysql-client-5.5
* END RUBYOPT="-KU -E utf-8:utf-8"

## How to use
For example, to access wordmove in separated shell use the follow command:
`docker run -ti --rm --volumes-from apache_with_wp -v $PWD:/home -v ~/.ssh/:/root/.ssh mfuezesi/wordmove bash`
