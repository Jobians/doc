---
sidebar_position: 1
---

# Generating short URLs

To generate a short URL, simply pass in a `url` query parameter to our Link Shortener Api:

    https://url.jobians.top/?url=https://www.money.com

This will return a shortened URL such as:

    https://url.jobians.top/5jq

When a user opens the short URL they will be redirected to the long URL location.

By default, Shorty will generate an HTML response for all saved URLs.
You can alter the response format by passing in a `format` query parameter.

    https://url.jobians.top/?url=http://www.money.com&format=text

The possible formats are `html`, `xml`, `text`, and `json`.
