# HTML Renderer

This repo provides a single-file HTML page that will render any content given to it in URL parameter.

It can be used directly from this repo, without hosting:

```text
https://asidko.github.io/html-render/?title=<page_title>&content=<hex_encoded_html_to_show
```

For example, this request will create a magnet link to a torrent:

https://asidko.github.io/html-render/?title=Download%20link&content=3c6120687265663d226d61676e65743a3f78743d75726e3a627469683a3336343862616638353064353933303531306331663137326235333432303065626235343936653626646e3d5562756e74752b32342e3034223e26233132393532323b20596f7572206d61676e6574206c696e6b3c2f613e

<img width="686" alt="image" src="https://github.com/asidko/html-render/assets/22843881/efaaf54b-cb40-42d0-8aa1-9fe94c9c06e6">
