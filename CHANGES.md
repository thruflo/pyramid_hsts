## 1.3.0

Fix compatibility with Pyramid 1.10 and drop support for Pyramid older than 1.4.

## 1.2.1

Default `hsts.max_age` to 18 weeks, as per https://hstspreload.appspot.com

## 1.2

Append `preload` token to the HSTS header value by default and provide
`hsts.preload` setting to switch it on/off.

## 1.1.4

Add `;` in between max age and sub domains parts of the header value.

## 1.1.3

Allow protocol header to be configured with `HSTS_PROTOCOL_HEADER` environment
variable.

## 1.1.2

Also secure ``request.host_url``.

## 1.1

Update docs and strip out unnecessary settings.

## 1.0

Extracted into standalone package from `pyramid_weblayer.hsts`.
