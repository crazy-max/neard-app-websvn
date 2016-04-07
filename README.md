This a sub-repo of [Neard project](https://github.com/crazy-max/neard) involving WebSVN app bundles.

## Installation

* Download and install [Neard](https://github.com/crazy-max/neard).
* If you already have installed Neard, stop it.
* Download [a WebSVN bundle](#download).
* Extract archive in `neard\apps\websvn\`. Directory structure example :

```
[-] neard
 | [-] apps
 |  | [-] websvn 
 |  |  | [-] websvn2.3.3
 |  |     | neard.conf
```

* Edit the `neard.conf` file and replace the key `websvnVersion` with the correct version. (eg. `websvnVersion="2.3.3"`)
* Edit the `alias/websvn.conf` file and replace the lines with the correct version. (Not necessary since Neard 1.0.18)
* Start Neard.

## Download

![](https://raw.github.com/crazy-max/neard-app-websvn/master/img/star-20160403.png) : Default bundle on Neard.

|                  | WebSVN release date | Neard release | Download |
| -----------------|:---------------------:|:-------------:|:--------:|
| **WebSVN 2.3.3** ![](https://raw.github.com/crazy-max/neard-app-websvn/master/img/star-20160403.png) | 2011/06/27 | [r1](https://github.com/crazy-max/neard-app-websvn/releases/tag/r1) | [neard-websvn-2.3.3-r1.zip](https://github.com/crazy-max/neard-app-websvn/releases/download/r1/neard-websvn-2.3.3-r1.zip) |

## Sources

* http://www.websvn.info/

## Issues

Issues must be reported on [Neard repository](https://github.com/crazy-max/neard/issues).<br />
Please read [Found a bug?](https://github.com/crazy-max/neard#found-a-bug) section before reporting an issue.
