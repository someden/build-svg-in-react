# Import SVG vs Inline SVG vs Img SVG


## Import SVG

https://github.com/someden/build-svg-in-react/blob/a7d599b074837dbfcf8378a0f0ba8392503c8f39/src/ImportSVG.js#L1-L5

After build it will be like a bunch of `React.createElement` functions:
https://github.com/someden/build-svg-in-react/blob/93e9f42f2f5fe630d3e22ff5b0b2ea2f52f2b0a4/build-with-import-svg/static/js/main.6c56403f.js#L3

And a separate SVG file, which is pretty useless: [build-with-import-svg/static/media/logo.6ce24c58023cc2f8fd88fe9d219db6c6.svg](https://github.com/someden/build-svg-in-react/blob/main/build-with-import-svg/static/media/logo.6ce24c58023cc2f8fd88fe9d219db6c6.svg)


## Inline SVG

https://github.com/someden/build-svg-in-react/blob/a7d599b074837dbfcf8378a0f0ba8392503c8f39/src/InlineSVG.js#L1-L11

After build it will be like a bunch of `React.createElement` functions but renamed as `jsx`:
https://github.com/someden/build-svg-in-react/blob/93e9f42f2f5fe630d3e22ff5b0b2ea2f52f2b0a4/build-with-inline-svg/static/js/main.1a98a94c.js#L3


## Img SVG

https://github.com/someden/build-svg-in-react/blob/a7d599b074837dbfcf8378a0f0ba8392503c8f39/src/ImgSVG.js#L1-L5

After build it will be like a path to SVG file and a single `React.createElement` function for `img` tag, also renamed as `jsx`:
https://github.com/someden/build-svg-in-react/blob/93e9f42f2f5fe630d3e22ff5b0b2ea2f52f2b0a4/build-with-img-svg/static/js/main.d155cbdc.js#L3
