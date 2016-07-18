# alpine-pkg-R

[![CircleCI](https://img.shields.io/circleci/project/FundingCircle/alpine-pkg-R/master.svg)](https://circleci.com/gh/FundingCircle/alpine-pkg-R)

The [R project][r-project], compiled as an Alpine Linux package. This package is
forked from the [Alpine Linux package (currently in
testing)](http://git.alpinelinux.org/cgit/aports/tree/testing/R/APKBUILD).

## Releases

See the [releases page][releases] for the latest download links.

## Installing

The current installation method for these packages is to pull them in using
`wget` or `curl` and install the local file with `apk`:

    apk --no-cache add ca-certificates openssl wget
    wget -q -O /etc/apk/keys/fundingcircle.rsa.pub https://raw.githubusercontent.com/FundingCircle/alpine-pkg-R/master/fundingcircle.rsa.pub
    wget https://github.com/FundingCircle/alpine-pkg-R/releases/download/3.3.1-r0/R-3.3.1-r0.apk
    apk add R-3.3.1-r0.apk

[r-project]: http://www.r-project.org/
[releases]: https://github.com/FundingCircle/alpine-pkg-R/releases/
