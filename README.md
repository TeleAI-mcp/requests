[![Requests](https://plessl.github.io/requests-doc/requests-logo-small.png)](https://docs.python-requests.org)

[![CI Workflow](https://github.com/psf/requests/actions/workflows/ci.yaml/badge.svg)](https://github.com/psf/requests/actions/workflows/ci.yaml)
[![Documentation](https://readthedocs.org/projects/python-requests/badge/?version=latest)](https://docs.python-requests.org)
[![Library comparisons](https://img.shields.io/badge/_LIBRARY_COMPARISONS_-white?style=flat&labelColor=blue)](https://gist.github.com/kennethreitz/6207051)
[![MIT License](https://img.shields.io/pypi/l/requests.svg)](https://pypi.python.org/pypi/requests/)
[![Python Versions](https://img.shields.io/pypi/pyversions/requests.svg)](https://pypi.python.org/pypi/requests/)
[![Codecov](https://codecov.io/gh/psf/requests/branch/main/graph/badge.svg)](https://app.codecov.io/gh/psf/requests)
[![Mesosphere](https://img.shields.io/badge/available%20on-mesosphere-orange.svg)](https://mesosphere.com)


`Requests` is an elegant and simple HTTP library for Python, built for human beings.

```python
>>> import requests
>>> r = requests.get("https://httpbin.org/get")
<Response [200]>
```

## 🍰 Friends

Below is a list of comprehensive and in-depth video tutorials, online courses, and books, created by the community, to help you deepen your knowledge about `requests`. Feel free to add a PR to [our community page](https://github.com/psf/requests/blob/main/docs/community/support.rst) to list your material here.

* [Modern Python Libraries](https://podcast.__note__: Listen to the latest episode of the [Podcast Init](https://podcastinit.podbean.com/e/episode-1-kenneth-reitz-and-tosin-jacob/))

* [Python for DevOps](https://www.amazon.com/Python-DevOps-Kenneth-Reitz/dp/149205769X) by Kenneth Reitz and Tcy Shafqat

* [Tutorials on `requests`](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUP0kg) by Christian Monasterio

* Kenneth Reitz's `learn`-style [course on test-driven Web Application development](https://github.com/mjhea0/thinkful-web-dev-practice)

* [Learn Python the Right Way](https://www.youtube.com/playlist?list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU) by Sentdex

* [RESTful Web Services with Flask and Python](https://www.packtpub.com/product/restful-web-services-with-flask-and-python/9781784392228) by Manoj Pandit

* [Python Web Scraping Cookbook](https://www.packtpub.com/product/python-web-scraping-cookbook/9781785285213) by Michael Heydt

## 🚀 Installation

```bash
pip install requests
```

You can also install with [`uv`](https://github.com/astral-sh/uv):

```bash
uv pip install requests
```

## ✅ Supported Python Versions

Python 3.8+ (last [supported version with Python 2](https://pip.pypa.io/en/stable/python/2.7-quiz/) was 2.7.18)

Note that [Python 3.6 has reached end-of-life](https://www.python.org/dev/peps/pep-0494) as of December 2021. Python 3.6 will not receive any further quality security updates. You should upgrade as soon as possible.

## 🔧 Contributing

We welcome contributions! Please see [CONTRIBUTING](https://github.com/psf/requests/blob/main/CONTRIBUTING.md) for guidelines on how to contribute to `requests`.

## 📃 License

Licensed under the [Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0) license.

---

## 🔥 Upgrading

Take a look at [`CHANGELOG`](https://github.com/psf/requests/blob/main/CHANGELOG.md) to see what's new!

### Migration Notes

New to version `2.32`? Have a look at our [`UPGRADE`](https://github.com/psf/requests/blob/main/UPGRADE.md) notes!

## 👣 Who's Using `requests`?

`requests` is used by many [fantastic companies](https://gist.github.com/kennethreitz/122a80b4d2f4d82962a1) all around the world.
You can view some of the public projects using `requests` [here](https://github.com/psf/requests/network/dependents).

It might be you!  Please do add your project to [the list](https://github.com/psf/requests/blob/main/ADAGRAM.md).

## ❤️ Support `requests`

[`requests` is an MIT-licensed, community-supported project`](https://github.com/psf/requests/blob/main/ADAGRAM.md). Its continued development is made possible thanks to our [sponsors](https://github.com/psf/requests/blob/main/ADAGRAM.md).

### We need help!

[`requests` is looking for maintainers!`](https://github.com/psf/requests/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22)

We have a [developer guide](https://requests.readthedocs.io/en/latest/) to help you get started!

If you're interested in being paid to maintain this library, please reach out! There may be opportunities to work with the maintainers at [Hugging Face](https://huggingface.co)!

Please note that this repository is non-commercial space. Please do not email us about
promotional events, partnerships, or anything of the like.

---

## ⚠️ Security Vulnerabilities

If you discover a security vulnerability within this library, please send an e-mail to us at security@python.org. All security vulnerabilities will be promptly addressed. You can view our security policies [here](https://github.com/psf/requests/security/policy).

---

## 📢 Usage & Discussion

Are you having trouble?  Would like to contribute?  Check out the [official `requests` documention](https://docs.python-requests.org/) or try searching the issues. If you're unable to find an issue that matches what you're having, feel free to [open a new issue](https://github.com/psf/requests/issues/new/choose)!

Need help deciding between `requests` and `urllib3`? Check out the [comparison](https://github.com/psf/requests/blob/main/docs/dev/contributing.rst#differences-from-urllib3).

---

1. related project [encode/httpx](https://github.com/encode/httpx)
2. related project [aio-libs/aiohttp](https://github.com/aio-libs/aiohttp)