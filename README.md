# dns-bl-check

Check a host against multiple DNS blocklist providers. This is currently a work
in progress.

[![PyPI - Version](https://img.shields.io/pypi/v/dns-bl-check.svg)](https://pypi.org/project/dns-bl-check)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/dns-bl-check.svg)](https://pypi.org/project/dns-bl-check)

-----

**Table of Contents**

- [Features](#installation)
- [Installation](#installation)
- [License](#license)

## Features

The following are intended features of this project.

- Check against DNSBLs (RBLs):
    - IP addresss based lists
    - DNS based lists
- Differential checks against public DNS firewalls (DNS filtering resolvers):
    - [CleanBrowsing](https://cleanbrowsing.org/filters/)
    - [Cloudflare 1.1.1.1 for Families](https://one.one.one.one/family/)
    - [Comodo Secure DNS](https://www.comodo.com/secure-dns/)
    - [Control D](https://controld.com/free-dns)
    - [dns0.eu](https://www.dns0.eu/)
    - [NextDNS](https://nextdns.io/)
    - [Norton DNS](https://nortondns.com/)
    - [OpenDNS](https://www.opendns.com/setupguide/)
    - [Quad9](https://www.quad9.net/)
    - [UltraDNS Public](https://vercara.com/ultra-dns-public)

## Installation

```console
pip install dns-bl-check
```

## License

`dns-bl-check` is distributed under the terms of the [ISC](https://spdx.org/licenses/ISC.html) license.
