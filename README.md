# Insight-pyclient

This module allows to interact with the Bitpay's [Insight-API](https://github.com/bitpay/insight-api).

# Usage

In order to use the api, an instance of InsightApi must pe instantiated. It takes as parameter the location of the API
(with a slash at the end), example: "http://local.lan/api".

The module allows (or will) access to all the APIs methods. For more details about the content or whatever, you can go
see the origin documentation. The code is also documented so you can go there for more details. The following content
will just list the prototypes callable methods.

## Block

* `Block get_block(Sting hash)`