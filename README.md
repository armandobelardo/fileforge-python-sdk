<!-- Begin Title, generated by Fern  -->
# Fileforge Python Library

[![fern shield](https://img.shields.io/badge/%F0%9F%8C%BF-SDK%20generated%20by%20Fern-brightgreen)](https://github.com/fern-api/fern)

The Fileforge Python Library provides convenient access to the Fileforge API from applications written in Python.
<!-- End Title  -->

<!-- Begin Installation, generated by Fern  -->
# Installation

```sh
pip install --upgrade fileforge
```
<!-- End Installation  -->

<!-- Begin Usage, generated by Fern  -->
# Usage

```python
from fileforge.client import Fileforge

client = Fileforge(
    api_key="YOUR_API_KEY",
    api_key="YOUR_API_KEY",
)
```
<!-- End Usage  -->

<!-- Begin Async Usage, generated by Fern  -->
# Async Client

```python
from fileforge.client import AsyncFileforge

client = AsyncFileforge(
    api_key="YOUR_API_KEY",
    api_key="YOUR_API_KEY",
)
```
<!-- End Async Usage  -->

<!-- Begin Status, generated by Fern  -->
# Beta Status

This SDK is in beta, and there may be breaking changes between versions without a major 
version update. Therefore, we recommend pinning the package version to a specific version. 
This way, you can install the same version each time without breaking changes.
<!-- End Status  -->

<!-- Begin Contributing, generated by Fern  -->
# Contributing

While we value open-source contributions to this SDK, this library is generated programmatically. 
Additions made directly to this library would have to be moved over to our generation code, 
otherwise they would be overwritten upon the next generated release. Feel free to open a PR as
 a proof of concept, but know that we will not be able to merge it as-is. We suggest opening 
an issue first to discuss with us!

On the other hand, contributions to the README are always very welcome!
<!-- End Contributing  -->

