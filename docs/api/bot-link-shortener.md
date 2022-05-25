---
sidebar_position: 1
---

# Generating short URLs

To generate a short URL, simply pass in a `url` query parameter to your Shorty installation:

    http://example.com/?url=http://www.google.com

This will return a shortened URL such as:

    http://example.com/9xq

When a user opens the short URL they will be redirected to the long URL location.

By default, Shorty will generate an HTML response for all saved URLs.
You can alter the response format by passing in a `format` query parameter.

    http://example.com/?url=http://www.google.com&format=text

The possible formats are `html`, `xml`, `text`, and `json`.
