Changelog
=========

0.2.1 (????-??-??)
------------------

* Shipping `dist/` instead of `src/`.
* Making a browser build lean by not relying on `querystring` or `Buffer`.


0.2.0 (2019-03-12)
------------------

* First public version
* Support for `client_credentials`, `password` and `refresh_token`.
* Will automatically attempt to refresh tokens if it knows an access token is
  expired.