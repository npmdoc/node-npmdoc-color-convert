# api documentation for  [color-convert (v1.9.0)](https://github.com/qix-/color-convert#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-color-convert.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-color-convert) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-color-convert.svg)](https://travis-ci.org/npmdoc/node-npmdoc-color-convert)
#### Plain color conversion functions

[![NPM](https://nodei.co/npm/color-convert.png?downloads=true)](https://www.npmjs.com/package/color-convert)

[![apidoc](https://npmdoc.github.io/node-npmdoc-color-convert/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-color-convert_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-color-convert/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-color-convert/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-color-convert/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Heather Arthur",
        "email": "fayearthur@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/qix-/color-convert/issues"
    },
    "dependencies": {
        "color-name": "^1.1.1"
    },
    "description": "Plain color conversion functions",
    "devDependencies": {
        "chalk": "^1.1.1",
        "xo": "^0.11.2"
    },
    "directories": {},
    "dist": {
        "shasum": "1accf97dd739b983bf994d56fec8f95853641b7a",
        "tarball": "https://registry.npmjs.org/color-convert/-/color-convert-1.9.0.tgz"
    },
    "files": [
        "index.js",
        "conversions.js",
        "css-keywords.js",
        "route.js"
    ],
    "gitHead": "f8b2cf64544c551f22b74947d511f0e97c4e6ef1",
    "homepage": "https://github.com/qix-/color-convert#readme",
    "keywords": [
        "color",
        "colour",
        "convert",
        "converter",
        "conversion",
        "rgb",
        "hsl",
        "hsv",
        "hwb",
        "cmyk",
        "ansi",
        "ansi16"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "harth",
            "email": "fayearthur@gmail.com"
        },
        {
            "name": "moox",
            "email": "m@moox.io"
        },
        {
            "name": "qix",
            "email": "i.am.qix@gmail.com"
        }
    ],
    "name": "color-convert",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/qix-/color-convert.git"
    },
    "scripts": {
        "pretest": "xo",
        "test": "node test/basic.js"
    },
    "version": "1.9.0",
    "xo": {
        "rules": {
            "default-case": 0,
            "no-inline-comments": 0,
            "operator-linebreak": 0
        }
    }
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module color-convert](#apidoc.module.color-convert)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi16.ansi256 (args)](#apidoc.element.color-convert.ansi16.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi16.apple (args)](#apidoc.element.color-convert.ansi16.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi16.cmyk (args)](#apidoc.element.color-convert.ansi16.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi16.gray (args)](#apidoc.element.color-convert.ansi16.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi16.hcg (args)](#apidoc.element.color-convert.ansi16.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi16.hex (args)](#apidoc.element.color-convert.ansi16.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi16.hsl (args)](#apidoc.element.color-convert.ansi16.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi16.hsv (args)](#apidoc.element.color-convert.ansi16.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi16.hwb (args)](#apidoc.element.color-convert.ansi16.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi16.keyword (args)](#apidoc.element.color-convert.ansi16.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi16.lab (args)](#apidoc.element.color-convert.ansi16.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi16.lch (args)](#apidoc.element.color-convert.ansi16.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi16.rgb (args)](#apidoc.element.color-convert.ansi16.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi16.xyz (args)](#apidoc.element.color-convert.ansi16.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi256.ansi16 (args)](#apidoc.element.color-convert.ansi256.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi256.apple (args)](#apidoc.element.color-convert.ansi256.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi256.cmyk (args)](#apidoc.element.color-convert.ansi256.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi256.gray (args)](#apidoc.element.color-convert.ansi256.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi256.hcg (args)](#apidoc.element.color-convert.ansi256.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi256.hex (args)](#apidoc.element.color-convert.ansi256.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi256.hsl (args)](#apidoc.element.color-convert.ansi256.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi256.hsv (args)](#apidoc.element.color-convert.ansi256.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi256.hwb (args)](#apidoc.element.color-convert.ansi256.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi256.keyword (args)](#apidoc.element.color-convert.ansi256.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi256.lab (args)](#apidoc.element.color-convert.ansi256.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi256.lch (args)](#apidoc.element.color-convert.ansi256.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi256.rgb (args)](#apidoc.element.color-convert.ansi256.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>ansi256.xyz (args)](#apidoc.element.color-convert.ansi256.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>apple.ansi16 (args)](#apidoc.element.color-convert.apple.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>apple.ansi256 (args)](#apidoc.element.color-convert.apple.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>apple.cmyk (args)](#apidoc.element.color-convert.apple.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>apple.gray (args)](#apidoc.element.color-convert.apple.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>apple.hcg (args)](#apidoc.element.color-convert.apple.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>apple.hex (args)](#apidoc.element.color-convert.apple.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>apple.hsl (args)](#apidoc.element.color-convert.apple.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>apple.hsv (args)](#apidoc.element.color-convert.apple.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>apple.hwb (args)](#apidoc.element.color-convert.apple.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>apple.keyword (args)](#apidoc.element.color-convert.apple.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>apple.lab (args)](#apidoc.element.color-convert.apple.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>apple.lch (args)](#apidoc.element.color-convert.apple.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>apple.rgb (args)](#apidoc.element.color-convert.apple.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>apple.xyz (args)](#apidoc.element.color-convert.apple.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>cmyk.ansi16 (args)](#apidoc.element.color-convert.cmyk.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>cmyk.ansi256 (args)](#apidoc.element.color-convert.cmyk.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>cmyk.apple (args)](#apidoc.element.color-convert.cmyk.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>cmyk.gray (args)](#apidoc.element.color-convert.cmyk.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>cmyk.hcg (args)](#apidoc.element.color-convert.cmyk.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>cmyk.hex (args)](#apidoc.element.color-convert.cmyk.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>cmyk.hsl (args)](#apidoc.element.color-convert.cmyk.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>cmyk.hsv (args)](#apidoc.element.color-convert.cmyk.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>cmyk.hwb (args)](#apidoc.element.color-convert.cmyk.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>cmyk.keyword (args)](#apidoc.element.color-convert.cmyk.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>cmyk.lab (args)](#apidoc.element.color-convert.cmyk.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>cmyk.lch (args)](#apidoc.element.color-convert.cmyk.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>cmyk.rgb (args)](#apidoc.element.color-convert.cmyk.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>cmyk.xyz (args)](#apidoc.element.color-convert.cmyk.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>gray.ansi16 (args)](#apidoc.element.color-convert.gray.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>gray.ansi256 (args)](#apidoc.element.color-convert.gray.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>gray.apple (args)](#apidoc.element.color-convert.gray.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>gray.cmyk (args)](#apidoc.element.color-convert.gray.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>gray.hcg (args)](#apidoc.element.color-convert.gray.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>gray.hex (args)](#apidoc.element.color-convert.gray.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>gray.hsl (args)](#apidoc.element.color-convert.gray.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>gray.hsv (args)](#apidoc.element.color-convert.gray.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>gray.hwb (args)](#apidoc.element.color-convert.gray.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>gray.keyword (args)](#apidoc.element.color-convert.gray.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>gray.lab (args)](#apidoc.element.color-convert.gray.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>gray.lch (args)](#apidoc.element.color-convert.gray.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>gray.rgb (args)](#apidoc.element.color-convert.gray.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>gray.xyz (args)](#apidoc.element.color-convert.gray.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hcg.ansi16 (args)](#apidoc.element.color-convert.hcg.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hcg.ansi256 (args)](#apidoc.element.color-convert.hcg.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hcg.apple (args)](#apidoc.element.color-convert.hcg.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hcg.cmyk (args)](#apidoc.element.color-convert.hcg.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hcg.gray (args)](#apidoc.element.color-convert.hcg.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hcg.hex (args)](#apidoc.element.color-convert.hcg.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hcg.hsl (args)](#apidoc.element.color-convert.hcg.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hcg.hsv (args)](#apidoc.element.color-convert.hcg.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hcg.hwb (args)](#apidoc.element.color-convert.hcg.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hcg.keyword (args)](#apidoc.element.color-convert.hcg.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hcg.lab (args)](#apidoc.element.color-convert.hcg.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hcg.lch (args)](#apidoc.element.color-convert.hcg.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hcg.rgb (args)](#apidoc.element.color-convert.hcg.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hcg.xyz (args)](#apidoc.element.color-convert.hcg.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hex.ansi16 (args)](#apidoc.element.color-convert.hex.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hex.ansi256 (args)](#apidoc.element.color-convert.hex.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hex.apple (args)](#apidoc.element.color-convert.hex.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hex.cmyk (args)](#apidoc.element.color-convert.hex.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hex.gray (args)](#apidoc.element.color-convert.hex.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hex.hcg (args)](#apidoc.element.color-convert.hex.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hex.hsl (args)](#apidoc.element.color-convert.hex.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hex.hsv (args)](#apidoc.element.color-convert.hex.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hex.hwb (args)](#apidoc.element.color-convert.hex.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hex.keyword (args)](#apidoc.element.color-convert.hex.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hex.lab (args)](#apidoc.element.color-convert.hex.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hex.lch (args)](#apidoc.element.color-convert.hex.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hex.rgb (args)](#apidoc.element.color-convert.hex.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hex.xyz (args)](#apidoc.element.color-convert.hex.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsl.ansi16 (args)](#apidoc.element.color-convert.hsl.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsl.ansi256 (args)](#apidoc.element.color-convert.hsl.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsl.apple (args)](#apidoc.element.color-convert.hsl.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsl.cmyk (args)](#apidoc.element.color-convert.hsl.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsl.gray (args)](#apidoc.element.color-convert.hsl.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsl.hcg (args)](#apidoc.element.color-convert.hsl.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsl.hex (args)](#apidoc.element.color-convert.hsl.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsl.hsv (args)](#apidoc.element.color-convert.hsl.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsl.hwb (args)](#apidoc.element.color-convert.hsl.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsl.keyword (args)](#apidoc.element.color-convert.hsl.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsl.lab (args)](#apidoc.element.color-convert.hsl.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsl.lch (args)](#apidoc.element.color-convert.hsl.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsl.rgb (args)](#apidoc.element.color-convert.hsl.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsl.xyz (args)](#apidoc.element.color-convert.hsl.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsv.ansi16 (args)](#apidoc.element.color-convert.hsv.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsv.ansi256 (args)](#apidoc.element.color-convert.hsv.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsv.apple (args)](#apidoc.element.color-convert.hsv.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsv.cmyk (args)](#apidoc.element.color-convert.hsv.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsv.gray (args)](#apidoc.element.color-convert.hsv.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsv.hcg (args)](#apidoc.element.color-convert.hsv.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsv.hex (args)](#apidoc.element.color-convert.hsv.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsv.hsl (args)](#apidoc.element.color-convert.hsv.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsv.hwb (args)](#apidoc.element.color-convert.hsv.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsv.keyword (args)](#apidoc.element.color-convert.hsv.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsv.lab (args)](#apidoc.element.color-convert.hsv.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsv.lch (args)](#apidoc.element.color-convert.hsv.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsv.rgb (args)](#apidoc.element.color-convert.hsv.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hsv.xyz (args)](#apidoc.element.color-convert.hsv.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hwb.ansi16 (args)](#apidoc.element.color-convert.hwb.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hwb.ansi256 (args)](#apidoc.element.color-convert.hwb.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hwb.apple (args)](#apidoc.element.color-convert.hwb.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hwb.cmyk (args)](#apidoc.element.color-convert.hwb.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hwb.gray (args)](#apidoc.element.color-convert.hwb.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hwb.hcg (args)](#apidoc.element.color-convert.hwb.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hwb.hex (args)](#apidoc.element.color-convert.hwb.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hwb.hsl (args)](#apidoc.element.color-convert.hwb.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hwb.hsv (args)](#apidoc.element.color-convert.hwb.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hwb.keyword (args)](#apidoc.element.color-convert.hwb.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hwb.lab (args)](#apidoc.element.color-convert.hwb.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hwb.lch (args)](#apidoc.element.color-convert.hwb.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hwb.rgb (args)](#apidoc.element.color-convert.hwb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>hwb.xyz (args)](#apidoc.element.color-convert.hwb.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>keyword.ansi16 (args)](#apidoc.element.color-convert.keyword.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>keyword.ansi256 (args)](#apidoc.element.color-convert.keyword.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>keyword.apple (args)](#apidoc.element.color-convert.keyword.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>keyword.cmyk (args)](#apidoc.element.color-convert.keyword.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>keyword.gray (args)](#apidoc.element.color-convert.keyword.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>keyword.hcg (args)](#apidoc.element.color-convert.keyword.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>keyword.hex (args)](#apidoc.element.color-convert.keyword.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>keyword.hsl (args)](#apidoc.element.color-convert.keyword.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>keyword.hsv (args)](#apidoc.element.color-convert.keyword.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>keyword.hwb (args)](#apidoc.element.color-convert.keyword.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>keyword.lab (args)](#apidoc.element.color-convert.keyword.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>keyword.lch (args)](#apidoc.element.color-convert.keyword.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>keyword.rgb (args)](#apidoc.element.color-convert.keyword.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>keyword.xyz (args)](#apidoc.element.color-convert.keyword.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lab.ansi16 (args)](#apidoc.element.color-convert.lab.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lab.ansi256 (args)](#apidoc.element.color-convert.lab.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lab.apple (args)](#apidoc.element.color-convert.lab.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lab.cmyk (args)](#apidoc.element.color-convert.lab.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lab.gray (args)](#apidoc.element.color-convert.lab.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lab.hcg (args)](#apidoc.element.color-convert.lab.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lab.hex (args)](#apidoc.element.color-convert.lab.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lab.hsl (args)](#apidoc.element.color-convert.lab.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lab.hsv (args)](#apidoc.element.color-convert.lab.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lab.hwb (args)](#apidoc.element.color-convert.lab.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lab.keyword (args)](#apidoc.element.color-convert.lab.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lab.lch (args)](#apidoc.element.color-convert.lab.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lab.rgb (args)](#apidoc.element.color-convert.lab.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lab.xyz (args)](#apidoc.element.color-convert.lab.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lch.ansi16 (args)](#apidoc.element.color-convert.lch.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lch.ansi256 (args)](#apidoc.element.color-convert.lch.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lch.apple (args)](#apidoc.element.color-convert.lch.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lch.cmyk (args)](#apidoc.element.color-convert.lch.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lch.gray (args)](#apidoc.element.color-convert.lch.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lch.hcg (args)](#apidoc.element.color-convert.lch.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lch.hex (args)](#apidoc.element.color-convert.lch.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lch.hsl (args)](#apidoc.element.color-convert.lch.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lch.hsv (args)](#apidoc.element.color-convert.lch.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lch.hwb (args)](#apidoc.element.color-convert.lch.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lch.keyword (args)](#apidoc.element.color-convert.lch.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lch.lab (args)](#apidoc.element.color-convert.lch.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lch.rgb (args)](#apidoc.element.color-convert.lch.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>lch.xyz (args)](#apidoc.element.color-convert.lch.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>rgb.ansi16 (args)](#apidoc.element.color-convert.rgb.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>rgb.ansi256 (args)](#apidoc.element.color-convert.rgb.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>rgb.apple (args)](#apidoc.element.color-convert.rgb.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>rgb.cmyk (args)](#apidoc.element.color-convert.rgb.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>rgb.gray (args)](#apidoc.element.color-convert.rgb.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>rgb.hcg (args)](#apidoc.element.color-convert.rgb.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>rgb.hex (args)](#apidoc.element.color-convert.rgb.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>rgb.hsl (args)](#apidoc.element.color-convert.rgb.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>rgb.hsv (args)](#apidoc.element.color-convert.rgb.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>rgb.hwb (args)](#apidoc.element.color-convert.rgb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>rgb.keyword (args)](#apidoc.element.color-convert.rgb.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>rgb.lab (args)](#apidoc.element.color-convert.rgb.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>rgb.lch (args)](#apidoc.element.color-convert.rgb.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>rgb.xyz (args)](#apidoc.element.color-convert.rgb.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>xyz.ansi16 (args)](#apidoc.element.color-convert.xyz.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>xyz.ansi256 (args)](#apidoc.element.color-convert.xyz.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>xyz.apple (args)](#apidoc.element.color-convert.xyz.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>xyz.cmyk (args)](#apidoc.element.color-convert.xyz.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>xyz.gray (args)](#apidoc.element.color-convert.xyz.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>xyz.hcg (args)](#apidoc.element.color-convert.xyz.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>xyz.hex (args)](#apidoc.element.color-convert.xyz.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>xyz.hsl (args)](#apidoc.element.color-convert.xyz.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>xyz.hsv (args)](#apidoc.element.color-convert.xyz.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>xyz.hwb (args)](#apidoc.element.color-convert.xyz.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>xyz.keyword (args)](#apidoc.element.color-convert.xyz.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>xyz.lab (args)](#apidoc.element.color-convert.xyz.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>xyz.lch (args)](#apidoc.element.color-convert.xyz.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.</span>xyz.rgb (args)](#apidoc.element.color-convert.xyz.rgb)
1.  object <span class="apidocSignatureSpan">color-convert.</span>ansi16
1.  object <span class="apidocSignatureSpan">color-convert.</span>ansi256
1.  object <span class="apidocSignatureSpan">color-convert.</span>apple
1.  object <span class="apidocSignatureSpan">color-convert.</span>cmyk
1.  object <span class="apidocSignatureSpan">color-convert.</span>gray
1.  object <span class="apidocSignatureSpan">color-convert.</span>hcg
1.  object <span class="apidocSignatureSpan">color-convert.</span>hex
1.  object <span class="apidocSignatureSpan">color-convert.</span>hsl
1.  object <span class="apidocSignatureSpan">color-convert.</span>hsv
1.  object <span class="apidocSignatureSpan">color-convert.</span>hwb
1.  object <span class="apidocSignatureSpan">color-convert.</span>keyword
1.  object <span class="apidocSignatureSpan">color-convert.</span>lab
1.  object <span class="apidocSignatureSpan">color-convert.</span>lch
1.  object <span class="apidocSignatureSpan">color-convert.</span>rgb
1.  object <span class="apidocSignatureSpan">color-convert.</span>xyz

#### [module color-convert.ansi16](#apidoc.module.color-convert.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>ansi256 (args)](#apidoc.element.color-convert.ansi16.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>apple (args)](#apidoc.element.color-convert.ansi16.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>cmyk (args)](#apidoc.element.color-convert.ansi16.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>gray (args)](#apidoc.element.color-convert.ansi16.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hcg (args)](#apidoc.element.color-convert.ansi16.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hex (args)](#apidoc.element.color-convert.ansi16.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hsl (args)](#apidoc.element.color-convert.ansi16.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hsv (args)](#apidoc.element.color-convert.ansi16.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hwb (args)](#apidoc.element.color-convert.ansi16.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>keyword (args)](#apidoc.element.color-convert.ansi16.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>lab (args)](#apidoc.element.color-convert.ansi16.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>lch (args)](#apidoc.element.color-convert.ansi16.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>rgb (args)](#apidoc.element.color-convert.ansi16.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>xyz (args)](#apidoc.element.color-convert.ansi16.xyz)

#### [module color-convert.ansi16.ansi256](#apidoc.module.color-convert.ansi16.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>ansi256 (args)](#apidoc.element.color-convert.ansi16.ansi256.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.ansi256.</span>raw (args)](#apidoc.element.color-convert.ansi16.ansi256.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi16.ansi256.</span>conversion

#### [module color-convert.ansi16.apple](#apidoc.module.color-convert.ansi16.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>apple (args)](#apidoc.element.color-convert.ansi16.apple.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.apple.</span>raw (args)](#apidoc.element.color-convert.ansi16.apple.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi16.apple.</span>conversion

#### [module color-convert.ansi16.cmyk](#apidoc.module.color-convert.ansi16.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>cmyk (args)](#apidoc.element.color-convert.ansi16.cmyk.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.cmyk.</span>raw (args)](#apidoc.element.color-convert.ansi16.cmyk.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi16.cmyk.</span>conversion

#### [module color-convert.ansi16.gray](#apidoc.module.color-convert.ansi16.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>gray (args)](#apidoc.element.color-convert.ansi16.gray.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.gray.</span>raw (args)](#apidoc.element.color-convert.ansi16.gray.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi16.gray.</span>conversion

#### [module color-convert.ansi16.hcg](#apidoc.module.color-convert.ansi16.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hcg (args)](#apidoc.element.color-convert.ansi16.hcg.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.hcg.</span>raw (args)](#apidoc.element.color-convert.ansi16.hcg.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi16.hcg.</span>conversion

#### [module color-convert.ansi16.hex](#apidoc.module.color-convert.ansi16.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hex (args)](#apidoc.element.color-convert.ansi16.hex.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.hex.</span>raw (args)](#apidoc.element.color-convert.ansi16.hex.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi16.hex.</span>conversion

#### [module color-convert.ansi16.hsl](#apidoc.module.color-convert.ansi16.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hsl (args)](#apidoc.element.color-convert.ansi16.hsl.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.hsl.</span>raw (args)](#apidoc.element.color-convert.ansi16.hsl.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi16.hsl.</span>conversion

#### [module color-convert.ansi16.hsv](#apidoc.module.color-convert.ansi16.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hsv (args)](#apidoc.element.color-convert.ansi16.hsv.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.hsv.</span>raw (args)](#apidoc.element.color-convert.ansi16.hsv.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi16.hsv.</span>conversion

#### [module color-convert.ansi16.hwb](#apidoc.module.color-convert.ansi16.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hwb (args)](#apidoc.element.color-convert.ansi16.hwb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.hwb.</span>raw (args)](#apidoc.element.color-convert.ansi16.hwb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi16.hwb.</span>conversion

#### [module color-convert.ansi16.keyword](#apidoc.module.color-convert.ansi16.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>keyword (args)](#apidoc.element.color-convert.ansi16.keyword.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.keyword.</span>raw (args)](#apidoc.element.color-convert.ansi16.keyword.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi16.keyword.</span>conversion

#### [module color-convert.ansi16.lab](#apidoc.module.color-convert.ansi16.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>lab (args)](#apidoc.element.color-convert.ansi16.lab.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.lab.</span>raw (args)](#apidoc.element.color-convert.ansi16.lab.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi16.lab.</span>conversion

#### [module color-convert.ansi16.lch](#apidoc.module.color-convert.ansi16.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>lch (args)](#apidoc.element.color-convert.ansi16.lch.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.lch.</span>raw (args)](#apidoc.element.color-convert.ansi16.lch.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi16.lch.</span>conversion

#### [module color-convert.ansi16.rgb](#apidoc.module.color-convert.ansi16.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>rgb (args)](#apidoc.element.color-convert.ansi16.rgb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.rgb.</span>raw (args)](#apidoc.element.color-convert.ansi16.rgb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi16.rgb.</span>conversion

#### [module color-convert.ansi16.xyz](#apidoc.module.color-convert.ansi16.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.</span>xyz (args)](#apidoc.element.color-convert.ansi16.xyz.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi16.xyz.</span>raw (args)](#apidoc.element.color-convert.ansi16.xyz.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi16.xyz.</span>conversion

#### [module color-convert.ansi256](#apidoc.module.color-convert.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>ansi16 (args)](#apidoc.element.color-convert.ansi256.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>apple (args)](#apidoc.element.color-convert.ansi256.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>cmyk (args)](#apidoc.element.color-convert.ansi256.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>gray (args)](#apidoc.element.color-convert.ansi256.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hcg (args)](#apidoc.element.color-convert.ansi256.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hex (args)](#apidoc.element.color-convert.ansi256.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hsl (args)](#apidoc.element.color-convert.ansi256.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hsv (args)](#apidoc.element.color-convert.ansi256.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hwb (args)](#apidoc.element.color-convert.ansi256.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>keyword (args)](#apidoc.element.color-convert.ansi256.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>lab (args)](#apidoc.element.color-convert.ansi256.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>lch (args)](#apidoc.element.color-convert.ansi256.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>rgb (args)](#apidoc.element.color-convert.ansi256.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>xyz (args)](#apidoc.element.color-convert.ansi256.xyz)

#### [module color-convert.ansi256.ansi16](#apidoc.module.color-convert.ansi256.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>ansi16 (args)](#apidoc.element.color-convert.ansi256.ansi16.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.ansi16.</span>raw (args)](#apidoc.element.color-convert.ansi256.ansi16.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi256.ansi16.</span>conversion

#### [module color-convert.ansi256.apple](#apidoc.module.color-convert.ansi256.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>apple (args)](#apidoc.element.color-convert.ansi256.apple.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.apple.</span>raw (args)](#apidoc.element.color-convert.ansi256.apple.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi256.apple.</span>conversion

#### [module color-convert.ansi256.cmyk](#apidoc.module.color-convert.ansi256.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>cmyk (args)](#apidoc.element.color-convert.ansi256.cmyk.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.cmyk.</span>raw (args)](#apidoc.element.color-convert.ansi256.cmyk.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi256.cmyk.</span>conversion

#### [module color-convert.ansi256.gray](#apidoc.module.color-convert.ansi256.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>gray (args)](#apidoc.element.color-convert.ansi256.gray.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.gray.</span>raw (args)](#apidoc.element.color-convert.ansi256.gray.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi256.gray.</span>conversion

#### [module color-convert.ansi256.hcg](#apidoc.module.color-convert.ansi256.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hcg (args)](#apidoc.element.color-convert.ansi256.hcg.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.hcg.</span>raw (args)](#apidoc.element.color-convert.ansi256.hcg.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi256.hcg.</span>conversion

#### [module color-convert.ansi256.hex](#apidoc.module.color-convert.ansi256.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hex (args)](#apidoc.element.color-convert.ansi256.hex.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.hex.</span>raw (args)](#apidoc.element.color-convert.ansi256.hex.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi256.hex.</span>conversion

#### [module color-convert.ansi256.hsl](#apidoc.module.color-convert.ansi256.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hsl (args)](#apidoc.element.color-convert.ansi256.hsl.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.hsl.</span>raw (args)](#apidoc.element.color-convert.ansi256.hsl.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi256.hsl.</span>conversion

#### [module color-convert.ansi256.hsv](#apidoc.module.color-convert.ansi256.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hsv (args)](#apidoc.element.color-convert.ansi256.hsv.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.hsv.</span>raw (args)](#apidoc.element.color-convert.ansi256.hsv.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi256.hsv.</span>conversion

#### [module color-convert.ansi256.hwb](#apidoc.module.color-convert.ansi256.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hwb (args)](#apidoc.element.color-convert.ansi256.hwb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.hwb.</span>raw (args)](#apidoc.element.color-convert.ansi256.hwb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi256.hwb.</span>conversion

#### [module color-convert.ansi256.keyword](#apidoc.module.color-convert.ansi256.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>keyword (args)](#apidoc.element.color-convert.ansi256.keyword.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.keyword.</span>raw (args)](#apidoc.element.color-convert.ansi256.keyword.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi256.keyword.</span>conversion

#### [module color-convert.ansi256.lab](#apidoc.module.color-convert.ansi256.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>lab (args)](#apidoc.element.color-convert.ansi256.lab.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.lab.</span>raw (args)](#apidoc.element.color-convert.ansi256.lab.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi256.lab.</span>conversion

#### [module color-convert.ansi256.lch](#apidoc.module.color-convert.ansi256.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>lch (args)](#apidoc.element.color-convert.ansi256.lch.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.lch.</span>raw (args)](#apidoc.element.color-convert.ansi256.lch.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi256.lch.</span>conversion

#### [module color-convert.ansi256.rgb](#apidoc.module.color-convert.ansi256.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>rgb (args)](#apidoc.element.color-convert.ansi256.rgb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.rgb.</span>raw (args)](#apidoc.element.color-convert.ansi256.rgb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi256.rgb.</span>conversion

#### [module color-convert.ansi256.xyz](#apidoc.module.color-convert.ansi256.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.</span>xyz (args)](#apidoc.element.color-convert.ansi256.xyz.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.ansi256.xyz.</span>raw (args)](#apidoc.element.color-convert.ansi256.xyz.raw)
1.  object <span class="apidocSignatureSpan">color-convert.ansi256.xyz.</span>conversion

#### [module color-convert.apple](#apidoc.module.color-convert.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>ansi16 (args)](#apidoc.element.color-convert.apple.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>ansi256 (args)](#apidoc.element.color-convert.apple.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>cmyk (args)](#apidoc.element.color-convert.apple.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>gray (args)](#apidoc.element.color-convert.apple.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>hcg (args)](#apidoc.element.color-convert.apple.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>hex (args)](#apidoc.element.color-convert.apple.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>hsl (args)](#apidoc.element.color-convert.apple.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>hsv (args)](#apidoc.element.color-convert.apple.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>hwb (args)](#apidoc.element.color-convert.apple.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>keyword (args)](#apidoc.element.color-convert.apple.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>lab (args)](#apidoc.element.color-convert.apple.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>lch (args)](#apidoc.element.color-convert.apple.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>rgb (args)](#apidoc.element.color-convert.apple.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>xyz (args)](#apidoc.element.color-convert.apple.xyz)

#### [module color-convert.apple.ansi16](#apidoc.module.color-convert.apple.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>ansi16 (args)](#apidoc.element.color-convert.apple.ansi16.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.ansi16.</span>raw (args)](#apidoc.element.color-convert.apple.ansi16.raw)
1.  object <span class="apidocSignatureSpan">color-convert.apple.ansi16.</span>conversion

#### [module color-convert.apple.ansi256](#apidoc.module.color-convert.apple.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>ansi256 (args)](#apidoc.element.color-convert.apple.ansi256.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.ansi256.</span>raw (args)](#apidoc.element.color-convert.apple.ansi256.raw)
1.  object <span class="apidocSignatureSpan">color-convert.apple.ansi256.</span>conversion

#### [module color-convert.apple.cmyk](#apidoc.module.color-convert.apple.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>cmyk (args)](#apidoc.element.color-convert.apple.cmyk.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.cmyk.</span>raw (args)](#apidoc.element.color-convert.apple.cmyk.raw)
1.  object <span class="apidocSignatureSpan">color-convert.apple.cmyk.</span>conversion

#### [module color-convert.apple.gray](#apidoc.module.color-convert.apple.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>gray (args)](#apidoc.element.color-convert.apple.gray.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.gray.</span>raw (args)](#apidoc.element.color-convert.apple.gray.raw)
1.  object <span class="apidocSignatureSpan">color-convert.apple.gray.</span>conversion

#### [module color-convert.apple.hcg](#apidoc.module.color-convert.apple.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>hcg (args)](#apidoc.element.color-convert.apple.hcg.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.hcg.</span>raw (args)](#apidoc.element.color-convert.apple.hcg.raw)
1.  object <span class="apidocSignatureSpan">color-convert.apple.hcg.</span>conversion

#### [module color-convert.apple.hex](#apidoc.module.color-convert.apple.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>hex (args)](#apidoc.element.color-convert.apple.hex.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.hex.</span>raw (args)](#apidoc.element.color-convert.apple.hex.raw)
1.  object <span class="apidocSignatureSpan">color-convert.apple.hex.</span>conversion

#### [module color-convert.apple.hsl](#apidoc.module.color-convert.apple.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>hsl (args)](#apidoc.element.color-convert.apple.hsl.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.hsl.</span>raw (args)](#apidoc.element.color-convert.apple.hsl.raw)
1.  object <span class="apidocSignatureSpan">color-convert.apple.hsl.</span>conversion

#### [module color-convert.apple.hsv](#apidoc.module.color-convert.apple.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>hsv (args)](#apidoc.element.color-convert.apple.hsv.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.hsv.</span>raw (args)](#apidoc.element.color-convert.apple.hsv.raw)
1.  object <span class="apidocSignatureSpan">color-convert.apple.hsv.</span>conversion

#### [module color-convert.apple.hwb](#apidoc.module.color-convert.apple.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>hwb (args)](#apidoc.element.color-convert.apple.hwb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.hwb.</span>raw (args)](#apidoc.element.color-convert.apple.hwb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.apple.hwb.</span>conversion

#### [module color-convert.apple.keyword](#apidoc.module.color-convert.apple.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>keyword (args)](#apidoc.element.color-convert.apple.keyword.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.keyword.</span>raw (args)](#apidoc.element.color-convert.apple.keyword.raw)
1.  object <span class="apidocSignatureSpan">color-convert.apple.keyword.</span>conversion

#### [module color-convert.apple.lab](#apidoc.module.color-convert.apple.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>lab (args)](#apidoc.element.color-convert.apple.lab.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.lab.</span>raw (args)](#apidoc.element.color-convert.apple.lab.raw)
1.  object <span class="apidocSignatureSpan">color-convert.apple.lab.</span>conversion

#### [module color-convert.apple.lch](#apidoc.module.color-convert.apple.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>lch (args)](#apidoc.element.color-convert.apple.lch.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.lch.</span>raw (args)](#apidoc.element.color-convert.apple.lch.raw)
1.  object <span class="apidocSignatureSpan">color-convert.apple.lch.</span>conversion

#### [module color-convert.apple.rgb](#apidoc.module.color-convert.apple.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>rgb (args)](#apidoc.element.color-convert.apple.rgb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.rgb.</span>raw (args)](#apidoc.element.color-convert.apple.rgb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.apple.rgb.</span>conversion

#### [module color-convert.apple.xyz](#apidoc.module.color-convert.apple.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.</span>xyz (args)](#apidoc.element.color-convert.apple.xyz.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.apple.xyz.</span>raw (args)](#apidoc.element.color-convert.apple.xyz.raw)
1.  object <span class="apidocSignatureSpan">color-convert.apple.xyz.</span>conversion

#### [module color-convert.cmyk](#apidoc.module.color-convert.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>ansi16 (args)](#apidoc.element.color-convert.cmyk.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>ansi256 (args)](#apidoc.element.color-convert.cmyk.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>apple (args)](#apidoc.element.color-convert.cmyk.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>gray (args)](#apidoc.element.color-convert.cmyk.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hcg (args)](#apidoc.element.color-convert.cmyk.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hex (args)](#apidoc.element.color-convert.cmyk.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hsl (args)](#apidoc.element.color-convert.cmyk.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hsv (args)](#apidoc.element.color-convert.cmyk.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hwb (args)](#apidoc.element.color-convert.cmyk.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>keyword (args)](#apidoc.element.color-convert.cmyk.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>lab (args)](#apidoc.element.color-convert.cmyk.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>lch (args)](#apidoc.element.color-convert.cmyk.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>rgb (args)](#apidoc.element.color-convert.cmyk.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>xyz (args)](#apidoc.element.color-convert.cmyk.xyz)

#### [module color-convert.cmyk.ansi16](#apidoc.module.color-convert.cmyk.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>ansi16 (args)](#apidoc.element.color-convert.cmyk.ansi16.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.ansi16.</span>raw (args)](#apidoc.element.color-convert.cmyk.ansi16.raw)
1.  object <span class="apidocSignatureSpan">color-convert.cmyk.ansi16.</span>conversion

#### [module color-convert.cmyk.ansi256](#apidoc.module.color-convert.cmyk.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>ansi256 (args)](#apidoc.element.color-convert.cmyk.ansi256.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.ansi256.</span>raw (args)](#apidoc.element.color-convert.cmyk.ansi256.raw)
1.  object <span class="apidocSignatureSpan">color-convert.cmyk.ansi256.</span>conversion

#### [module color-convert.cmyk.apple](#apidoc.module.color-convert.cmyk.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>apple (args)](#apidoc.element.color-convert.cmyk.apple.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.apple.</span>raw (args)](#apidoc.element.color-convert.cmyk.apple.raw)
1.  object <span class="apidocSignatureSpan">color-convert.cmyk.apple.</span>conversion

#### [module color-convert.cmyk.gray](#apidoc.module.color-convert.cmyk.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>gray (args)](#apidoc.element.color-convert.cmyk.gray.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.gray.</span>raw (args)](#apidoc.element.color-convert.cmyk.gray.raw)
1.  object <span class="apidocSignatureSpan">color-convert.cmyk.gray.</span>conversion

#### [module color-convert.cmyk.hcg](#apidoc.module.color-convert.cmyk.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hcg (args)](#apidoc.element.color-convert.cmyk.hcg.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.hcg.</span>raw (args)](#apidoc.element.color-convert.cmyk.hcg.raw)
1.  object <span class="apidocSignatureSpan">color-convert.cmyk.hcg.</span>conversion

#### [module color-convert.cmyk.hex](#apidoc.module.color-convert.cmyk.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hex (args)](#apidoc.element.color-convert.cmyk.hex.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.hex.</span>raw (args)](#apidoc.element.color-convert.cmyk.hex.raw)
1.  object <span class="apidocSignatureSpan">color-convert.cmyk.hex.</span>conversion

#### [module color-convert.cmyk.hsl](#apidoc.module.color-convert.cmyk.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hsl (args)](#apidoc.element.color-convert.cmyk.hsl.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.hsl.</span>raw (args)](#apidoc.element.color-convert.cmyk.hsl.raw)
1.  object <span class="apidocSignatureSpan">color-convert.cmyk.hsl.</span>conversion

#### [module color-convert.cmyk.hsv](#apidoc.module.color-convert.cmyk.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hsv (args)](#apidoc.element.color-convert.cmyk.hsv.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.hsv.</span>raw (args)](#apidoc.element.color-convert.cmyk.hsv.raw)
1.  object <span class="apidocSignatureSpan">color-convert.cmyk.hsv.</span>conversion

#### [module color-convert.cmyk.hwb](#apidoc.module.color-convert.cmyk.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hwb (args)](#apidoc.element.color-convert.cmyk.hwb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.hwb.</span>raw (args)](#apidoc.element.color-convert.cmyk.hwb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.cmyk.hwb.</span>conversion

#### [module color-convert.cmyk.keyword](#apidoc.module.color-convert.cmyk.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>keyword (args)](#apidoc.element.color-convert.cmyk.keyword.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.keyword.</span>raw (args)](#apidoc.element.color-convert.cmyk.keyword.raw)
1.  object <span class="apidocSignatureSpan">color-convert.cmyk.keyword.</span>conversion

#### [module color-convert.cmyk.lab](#apidoc.module.color-convert.cmyk.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>lab (args)](#apidoc.element.color-convert.cmyk.lab.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.lab.</span>raw (args)](#apidoc.element.color-convert.cmyk.lab.raw)
1.  object <span class="apidocSignatureSpan">color-convert.cmyk.lab.</span>conversion

#### [module color-convert.cmyk.lch](#apidoc.module.color-convert.cmyk.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>lch (args)](#apidoc.element.color-convert.cmyk.lch.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.lch.</span>raw (args)](#apidoc.element.color-convert.cmyk.lch.raw)
1.  object <span class="apidocSignatureSpan">color-convert.cmyk.lch.</span>conversion

#### [module color-convert.cmyk.rgb](#apidoc.module.color-convert.cmyk.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>rgb (args)](#apidoc.element.color-convert.cmyk.rgb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.rgb.</span>raw (args)](#apidoc.element.color-convert.cmyk.rgb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.cmyk.rgb.</span>conversion

#### [module color-convert.cmyk.xyz](#apidoc.module.color-convert.cmyk.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.</span>xyz (args)](#apidoc.element.color-convert.cmyk.xyz.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.cmyk.xyz.</span>raw (args)](#apidoc.element.color-convert.cmyk.xyz.raw)
1.  object <span class="apidocSignatureSpan">color-convert.cmyk.xyz.</span>conversion

#### [module color-convert.gray](#apidoc.module.color-convert.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>ansi16 (args)](#apidoc.element.color-convert.gray.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>ansi256 (args)](#apidoc.element.color-convert.gray.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>apple (args)](#apidoc.element.color-convert.gray.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>cmyk (args)](#apidoc.element.color-convert.gray.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>hcg (args)](#apidoc.element.color-convert.gray.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>hex (args)](#apidoc.element.color-convert.gray.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>hsl (args)](#apidoc.element.color-convert.gray.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>hsv (args)](#apidoc.element.color-convert.gray.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>hwb (args)](#apidoc.element.color-convert.gray.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>keyword (args)](#apidoc.element.color-convert.gray.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>lab (args)](#apidoc.element.color-convert.gray.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>lch (args)](#apidoc.element.color-convert.gray.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>rgb (args)](#apidoc.element.color-convert.gray.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>xyz (args)](#apidoc.element.color-convert.gray.xyz)

#### [module color-convert.gray.ansi16](#apidoc.module.color-convert.gray.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>ansi16 (args)](#apidoc.element.color-convert.gray.ansi16.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.ansi16.</span>raw (args)](#apidoc.element.color-convert.gray.ansi16.raw)
1.  object <span class="apidocSignatureSpan">color-convert.gray.ansi16.</span>conversion

#### [module color-convert.gray.ansi256](#apidoc.module.color-convert.gray.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>ansi256 (args)](#apidoc.element.color-convert.gray.ansi256.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.ansi256.</span>raw (args)](#apidoc.element.color-convert.gray.ansi256.raw)
1.  object <span class="apidocSignatureSpan">color-convert.gray.ansi256.</span>conversion

#### [module color-convert.gray.apple](#apidoc.module.color-convert.gray.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>apple (args)](#apidoc.element.color-convert.gray.apple.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.apple.</span>raw (args)](#apidoc.element.color-convert.gray.apple.raw)
1.  object <span class="apidocSignatureSpan">color-convert.gray.apple.</span>conversion

#### [module color-convert.gray.cmyk](#apidoc.module.color-convert.gray.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>cmyk (args)](#apidoc.element.color-convert.gray.cmyk.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.cmyk.</span>raw (args)](#apidoc.element.color-convert.gray.cmyk.raw)
1.  object <span class="apidocSignatureSpan">color-convert.gray.cmyk.</span>conversion

#### [module color-convert.gray.hcg](#apidoc.module.color-convert.gray.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>hcg (args)](#apidoc.element.color-convert.gray.hcg.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.hcg.</span>raw (args)](#apidoc.element.color-convert.gray.hcg.raw)
1.  object <span class="apidocSignatureSpan">color-convert.gray.hcg.</span>conversion

#### [module color-convert.gray.hex](#apidoc.module.color-convert.gray.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>hex (args)](#apidoc.element.color-convert.gray.hex.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.hex.</span>raw (args)](#apidoc.element.color-convert.gray.hex.raw)
1.  object <span class="apidocSignatureSpan">color-convert.gray.hex.</span>conversion

#### [module color-convert.gray.hsl](#apidoc.module.color-convert.gray.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>hsl (args)](#apidoc.element.color-convert.gray.hsl.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.hsl.</span>raw (args)](#apidoc.element.color-convert.gray.hsl.raw)
1.  object <span class="apidocSignatureSpan">color-convert.gray.hsl.</span>conversion

#### [module color-convert.gray.hsv](#apidoc.module.color-convert.gray.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>hsv (args)](#apidoc.element.color-convert.gray.hsv.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.hsv.</span>raw (args)](#apidoc.element.color-convert.gray.hsv.raw)
1.  object <span class="apidocSignatureSpan">color-convert.gray.hsv.</span>conversion

#### [module color-convert.gray.hwb](#apidoc.module.color-convert.gray.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>hwb (args)](#apidoc.element.color-convert.gray.hwb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.hwb.</span>raw (args)](#apidoc.element.color-convert.gray.hwb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.gray.hwb.</span>conversion

#### [module color-convert.gray.keyword](#apidoc.module.color-convert.gray.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>keyword (args)](#apidoc.element.color-convert.gray.keyword.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.keyword.</span>raw (args)](#apidoc.element.color-convert.gray.keyword.raw)
1.  object <span class="apidocSignatureSpan">color-convert.gray.keyword.</span>conversion

#### [module color-convert.gray.lab](#apidoc.module.color-convert.gray.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>lab (args)](#apidoc.element.color-convert.gray.lab.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.lab.</span>raw (args)](#apidoc.element.color-convert.gray.lab.raw)
1.  object <span class="apidocSignatureSpan">color-convert.gray.lab.</span>conversion

#### [module color-convert.gray.lch](#apidoc.module.color-convert.gray.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>lch (args)](#apidoc.element.color-convert.gray.lch.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.lch.</span>raw (args)](#apidoc.element.color-convert.gray.lch.raw)
1.  object <span class="apidocSignatureSpan">color-convert.gray.lch.</span>conversion

#### [module color-convert.gray.rgb](#apidoc.module.color-convert.gray.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>rgb (args)](#apidoc.element.color-convert.gray.rgb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.rgb.</span>raw (args)](#apidoc.element.color-convert.gray.rgb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.gray.rgb.</span>conversion

#### [module color-convert.gray.xyz](#apidoc.module.color-convert.gray.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.</span>xyz (args)](#apidoc.element.color-convert.gray.xyz.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.gray.xyz.</span>raw (args)](#apidoc.element.color-convert.gray.xyz.raw)
1.  object <span class="apidocSignatureSpan">color-convert.gray.xyz.</span>conversion

#### [module color-convert.hcg](#apidoc.module.color-convert.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>ansi16 (args)](#apidoc.element.color-convert.hcg.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>ansi256 (args)](#apidoc.element.color-convert.hcg.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>apple (args)](#apidoc.element.color-convert.hcg.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>cmyk (args)](#apidoc.element.color-convert.hcg.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>gray (args)](#apidoc.element.color-convert.hcg.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>hex (args)](#apidoc.element.color-convert.hcg.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>hsl (args)](#apidoc.element.color-convert.hcg.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>hsv (args)](#apidoc.element.color-convert.hcg.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>hwb (args)](#apidoc.element.color-convert.hcg.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>keyword (args)](#apidoc.element.color-convert.hcg.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>lab (args)](#apidoc.element.color-convert.hcg.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>lch (args)](#apidoc.element.color-convert.hcg.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>rgb (args)](#apidoc.element.color-convert.hcg.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>xyz (args)](#apidoc.element.color-convert.hcg.xyz)

#### [module color-convert.hcg.ansi16](#apidoc.module.color-convert.hcg.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>ansi16 (args)](#apidoc.element.color-convert.hcg.ansi16.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.ansi16.</span>raw (args)](#apidoc.element.color-convert.hcg.ansi16.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hcg.ansi16.</span>conversion

#### [module color-convert.hcg.ansi256](#apidoc.module.color-convert.hcg.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>ansi256 (args)](#apidoc.element.color-convert.hcg.ansi256.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.ansi256.</span>raw (args)](#apidoc.element.color-convert.hcg.ansi256.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hcg.ansi256.</span>conversion

#### [module color-convert.hcg.apple](#apidoc.module.color-convert.hcg.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>apple (args)](#apidoc.element.color-convert.hcg.apple.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.apple.</span>raw (args)](#apidoc.element.color-convert.hcg.apple.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hcg.apple.</span>conversion

#### [module color-convert.hcg.cmyk](#apidoc.module.color-convert.hcg.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>cmyk (args)](#apidoc.element.color-convert.hcg.cmyk.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.cmyk.</span>raw (args)](#apidoc.element.color-convert.hcg.cmyk.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hcg.cmyk.</span>conversion

#### [module color-convert.hcg.gray](#apidoc.module.color-convert.hcg.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>gray (args)](#apidoc.element.color-convert.hcg.gray.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.gray.</span>raw (args)](#apidoc.element.color-convert.hcg.gray.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hcg.gray.</span>conversion

#### [module color-convert.hcg.hex](#apidoc.module.color-convert.hcg.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>hex (args)](#apidoc.element.color-convert.hcg.hex.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.hex.</span>raw (args)](#apidoc.element.color-convert.hcg.hex.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hcg.hex.</span>conversion

#### [module color-convert.hcg.hsl](#apidoc.module.color-convert.hcg.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>hsl (args)](#apidoc.element.color-convert.hcg.hsl.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.hsl.</span>raw (args)](#apidoc.element.color-convert.hcg.hsl.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hcg.hsl.</span>conversion

#### [module color-convert.hcg.hsv](#apidoc.module.color-convert.hcg.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>hsv (args)](#apidoc.element.color-convert.hcg.hsv.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.hsv.</span>raw (args)](#apidoc.element.color-convert.hcg.hsv.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hcg.hsv.</span>conversion

#### [module color-convert.hcg.hwb](#apidoc.module.color-convert.hcg.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>hwb (args)](#apidoc.element.color-convert.hcg.hwb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.hwb.</span>raw (args)](#apidoc.element.color-convert.hcg.hwb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hcg.hwb.</span>conversion

#### [module color-convert.hcg.keyword](#apidoc.module.color-convert.hcg.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>keyword (args)](#apidoc.element.color-convert.hcg.keyword.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.keyword.</span>raw (args)](#apidoc.element.color-convert.hcg.keyword.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hcg.keyword.</span>conversion

#### [module color-convert.hcg.lab](#apidoc.module.color-convert.hcg.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>lab (args)](#apidoc.element.color-convert.hcg.lab.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.lab.</span>raw (args)](#apidoc.element.color-convert.hcg.lab.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hcg.lab.</span>conversion

#### [module color-convert.hcg.lch](#apidoc.module.color-convert.hcg.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>lch (args)](#apidoc.element.color-convert.hcg.lch.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.lch.</span>raw (args)](#apidoc.element.color-convert.hcg.lch.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hcg.lch.</span>conversion

#### [module color-convert.hcg.rgb](#apidoc.module.color-convert.hcg.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>rgb (args)](#apidoc.element.color-convert.hcg.rgb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.rgb.</span>raw (args)](#apidoc.element.color-convert.hcg.rgb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hcg.rgb.</span>conversion

#### [module color-convert.hcg.xyz](#apidoc.module.color-convert.hcg.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.</span>xyz (args)](#apidoc.element.color-convert.hcg.xyz.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.hcg.xyz.</span>raw (args)](#apidoc.element.color-convert.hcg.xyz.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hcg.xyz.</span>conversion

#### [module color-convert.hex](#apidoc.module.color-convert.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>ansi16 (args)](#apidoc.element.color-convert.hex.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>ansi256 (args)](#apidoc.element.color-convert.hex.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>apple (args)](#apidoc.element.color-convert.hex.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>cmyk (args)](#apidoc.element.color-convert.hex.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>gray (args)](#apidoc.element.color-convert.hex.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>hcg (args)](#apidoc.element.color-convert.hex.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>hsl (args)](#apidoc.element.color-convert.hex.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>hsv (args)](#apidoc.element.color-convert.hex.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>hwb (args)](#apidoc.element.color-convert.hex.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>keyword (args)](#apidoc.element.color-convert.hex.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>lab (args)](#apidoc.element.color-convert.hex.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>lch (args)](#apidoc.element.color-convert.hex.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>rgb (args)](#apidoc.element.color-convert.hex.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>xyz (args)](#apidoc.element.color-convert.hex.xyz)

#### [module color-convert.hex.ansi16](#apidoc.module.color-convert.hex.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>ansi16 (args)](#apidoc.element.color-convert.hex.ansi16.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.ansi16.</span>raw (args)](#apidoc.element.color-convert.hex.ansi16.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hex.ansi16.</span>conversion

#### [module color-convert.hex.ansi256](#apidoc.module.color-convert.hex.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>ansi256 (args)](#apidoc.element.color-convert.hex.ansi256.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.ansi256.</span>raw (args)](#apidoc.element.color-convert.hex.ansi256.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hex.ansi256.</span>conversion

#### [module color-convert.hex.apple](#apidoc.module.color-convert.hex.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>apple (args)](#apidoc.element.color-convert.hex.apple.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.apple.</span>raw (args)](#apidoc.element.color-convert.hex.apple.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hex.apple.</span>conversion

#### [module color-convert.hex.cmyk](#apidoc.module.color-convert.hex.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>cmyk (args)](#apidoc.element.color-convert.hex.cmyk.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.cmyk.</span>raw (args)](#apidoc.element.color-convert.hex.cmyk.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hex.cmyk.</span>conversion

#### [module color-convert.hex.gray](#apidoc.module.color-convert.hex.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>gray (args)](#apidoc.element.color-convert.hex.gray.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.gray.</span>raw (args)](#apidoc.element.color-convert.hex.gray.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hex.gray.</span>conversion

#### [module color-convert.hex.hcg](#apidoc.module.color-convert.hex.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>hcg (args)](#apidoc.element.color-convert.hex.hcg.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.hcg.</span>raw (args)](#apidoc.element.color-convert.hex.hcg.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hex.hcg.</span>conversion

#### [module color-convert.hex.hsl](#apidoc.module.color-convert.hex.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>hsl (args)](#apidoc.element.color-convert.hex.hsl.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.hsl.</span>raw (args)](#apidoc.element.color-convert.hex.hsl.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hex.hsl.</span>conversion

#### [module color-convert.hex.hsv](#apidoc.module.color-convert.hex.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>hsv (args)](#apidoc.element.color-convert.hex.hsv.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.hsv.</span>raw (args)](#apidoc.element.color-convert.hex.hsv.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hex.hsv.</span>conversion

#### [module color-convert.hex.hwb](#apidoc.module.color-convert.hex.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>hwb (args)](#apidoc.element.color-convert.hex.hwb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.hwb.</span>raw (args)](#apidoc.element.color-convert.hex.hwb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hex.hwb.</span>conversion

#### [module color-convert.hex.keyword](#apidoc.module.color-convert.hex.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>keyword (args)](#apidoc.element.color-convert.hex.keyword.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.keyword.</span>raw (args)](#apidoc.element.color-convert.hex.keyword.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hex.keyword.</span>conversion

#### [module color-convert.hex.lab](#apidoc.module.color-convert.hex.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>lab (args)](#apidoc.element.color-convert.hex.lab.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.lab.</span>raw (args)](#apidoc.element.color-convert.hex.lab.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hex.lab.</span>conversion

#### [module color-convert.hex.lch](#apidoc.module.color-convert.hex.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>lch (args)](#apidoc.element.color-convert.hex.lch.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.lch.</span>raw (args)](#apidoc.element.color-convert.hex.lch.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hex.lch.</span>conversion

#### [module color-convert.hex.rgb](#apidoc.module.color-convert.hex.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>rgb (args)](#apidoc.element.color-convert.hex.rgb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.rgb.</span>raw (args)](#apidoc.element.color-convert.hex.rgb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hex.rgb.</span>conversion

#### [module color-convert.hex.xyz](#apidoc.module.color-convert.hex.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.</span>xyz (args)](#apidoc.element.color-convert.hex.xyz.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.hex.xyz.</span>raw (args)](#apidoc.element.color-convert.hex.xyz.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hex.xyz.</span>conversion

#### [module color-convert.hsl](#apidoc.module.color-convert.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>ansi16 (args)](#apidoc.element.color-convert.hsl.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>ansi256 (args)](#apidoc.element.color-convert.hsl.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>apple (args)](#apidoc.element.color-convert.hsl.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>cmyk (args)](#apidoc.element.color-convert.hsl.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>gray (args)](#apidoc.element.color-convert.hsl.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>hcg (args)](#apidoc.element.color-convert.hsl.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>hex (args)](#apidoc.element.color-convert.hsl.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>hsv (args)](#apidoc.element.color-convert.hsl.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>hwb (args)](#apidoc.element.color-convert.hsl.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>keyword (args)](#apidoc.element.color-convert.hsl.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>lab (args)](#apidoc.element.color-convert.hsl.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>lch (args)](#apidoc.element.color-convert.hsl.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>rgb (args)](#apidoc.element.color-convert.hsl.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>xyz (args)](#apidoc.element.color-convert.hsl.xyz)

#### [module color-convert.hsl.ansi16](#apidoc.module.color-convert.hsl.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>ansi16 (args)](#apidoc.element.color-convert.hsl.ansi16.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.ansi16.</span>raw (args)](#apidoc.element.color-convert.hsl.ansi16.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsl.ansi16.</span>conversion

#### [module color-convert.hsl.ansi256](#apidoc.module.color-convert.hsl.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>ansi256 (args)](#apidoc.element.color-convert.hsl.ansi256.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.ansi256.</span>raw (args)](#apidoc.element.color-convert.hsl.ansi256.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsl.ansi256.</span>conversion

#### [module color-convert.hsl.apple](#apidoc.module.color-convert.hsl.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>apple (args)](#apidoc.element.color-convert.hsl.apple.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.apple.</span>raw (args)](#apidoc.element.color-convert.hsl.apple.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsl.apple.</span>conversion

#### [module color-convert.hsl.cmyk](#apidoc.module.color-convert.hsl.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>cmyk (args)](#apidoc.element.color-convert.hsl.cmyk.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.cmyk.</span>raw (args)](#apidoc.element.color-convert.hsl.cmyk.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsl.cmyk.</span>conversion

#### [module color-convert.hsl.gray](#apidoc.module.color-convert.hsl.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>gray (args)](#apidoc.element.color-convert.hsl.gray.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.gray.</span>raw (args)](#apidoc.element.color-convert.hsl.gray.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsl.gray.</span>conversion

#### [module color-convert.hsl.hcg](#apidoc.module.color-convert.hsl.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>hcg (args)](#apidoc.element.color-convert.hsl.hcg.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.hcg.</span>raw (args)](#apidoc.element.color-convert.hsl.hcg.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsl.hcg.</span>conversion

#### [module color-convert.hsl.hex](#apidoc.module.color-convert.hsl.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>hex (args)](#apidoc.element.color-convert.hsl.hex.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.hex.</span>raw (args)](#apidoc.element.color-convert.hsl.hex.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsl.hex.</span>conversion

#### [module color-convert.hsl.hsv](#apidoc.module.color-convert.hsl.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>hsv (args)](#apidoc.element.color-convert.hsl.hsv.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.hsv.</span>raw (args)](#apidoc.element.color-convert.hsl.hsv.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsl.hsv.</span>conversion

#### [module color-convert.hsl.hwb](#apidoc.module.color-convert.hsl.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>hwb (args)](#apidoc.element.color-convert.hsl.hwb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.hwb.</span>raw (args)](#apidoc.element.color-convert.hsl.hwb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsl.hwb.</span>conversion

#### [module color-convert.hsl.keyword](#apidoc.module.color-convert.hsl.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>keyword (args)](#apidoc.element.color-convert.hsl.keyword.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.keyword.</span>raw (args)](#apidoc.element.color-convert.hsl.keyword.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsl.keyword.</span>conversion

#### [module color-convert.hsl.lab](#apidoc.module.color-convert.hsl.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>lab (args)](#apidoc.element.color-convert.hsl.lab.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.lab.</span>raw (args)](#apidoc.element.color-convert.hsl.lab.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsl.lab.</span>conversion

#### [module color-convert.hsl.lch](#apidoc.module.color-convert.hsl.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>lch (args)](#apidoc.element.color-convert.hsl.lch.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.lch.</span>raw (args)](#apidoc.element.color-convert.hsl.lch.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsl.lch.</span>conversion

#### [module color-convert.hsl.rgb](#apidoc.module.color-convert.hsl.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>rgb (args)](#apidoc.element.color-convert.hsl.rgb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.rgb.</span>raw (args)](#apidoc.element.color-convert.hsl.rgb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsl.rgb.</span>conversion

#### [module color-convert.hsl.xyz](#apidoc.module.color-convert.hsl.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.</span>xyz (args)](#apidoc.element.color-convert.hsl.xyz.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.hsl.xyz.</span>raw (args)](#apidoc.element.color-convert.hsl.xyz.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsl.xyz.</span>conversion

#### [module color-convert.hsv](#apidoc.module.color-convert.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>ansi16 (args)](#apidoc.element.color-convert.hsv.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>ansi256 (args)](#apidoc.element.color-convert.hsv.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>apple (args)](#apidoc.element.color-convert.hsv.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>cmyk (args)](#apidoc.element.color-convert.hsv.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>gray (args)](#apidoc.element.color-convert.hsv.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>hcg (args)](#apidoc.element.color-convert.hsv.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>hex (args)](#apidoc.element.color-convert.hsv.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>hsl (args)](#apidoc.element.color-convert.hsv.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>hwb (args)](#apidoc.element.color-convert.hsv.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>keyword (args)](#apidoc.element.color-convert.hsv.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>lab (args)](#apidoc.element.color-convert.hsv.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>lch (args)](#apidoc.element.color-convert.hsv.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>rgb (args)](#apidoc.element.color-convert.hsv.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>xyz (args)](#apidoc.element.color-convert.hsv.xyz)

#### [module color-convert.hsv.ansi16](#apidoc.module.color-convert.hsv.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>ansi16 (args)](#apidoc.element.color-convert.hsv.ansi16.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.ansi16.</span>raw (args)](#apidoc.element.color-convert.hsv.ansi16.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsv.ansi16.</span>conversion

#### [module color-convert.hsv.ansi256](#apidoc.module.color-convert.hsv.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>ansi256 (args)](#apidoc.element.color-convert.hsv.ansi256.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.ansi256.</span>raw (args)](#apidoc.element.color-convert.hsv.ansi256.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsv.ansi256.</span>conversion

#### [module color-convert.hsv.apple](#apidoc.module.color-convert.hsv.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>apple (args)](#apidoc.element.color-convert.hsv.apple.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.apple.</span>raw (args)](#apidoc.element.color-convert.hsv.apple.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsv.apple.</span>conversion

#### [module color-convert.hsv.cmyk](#apidoc.module.color-convert.hsv.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>cmyk (args)](#apidoc.element.color-convert.hsv.cmyk.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.cmyk.</span>raw (args)](#apidoc.element.color-convert.hsv.cmyk.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsv.cmyk.</span>conversion

#### [module color-convert.hsv.gray](#apidoc.module.color-convert.hsv.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>gray (args)](#apidoc.element.color-convert.hsv.gray.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.gray.</span>raw (args)](#apidoc.element.color-convert.hsv.gray.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsv.gray.</span>conversion

#### [module color-convert.hsv.hcg](#apidoc.module.color-convert.hsv.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>hcg (args)](#apidoc.element.color-convert.hsv.hcg.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.hcg.</span>raw (args)](#apidoc.element.color-convert.hsv.hcg.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsv.hcg.</span>conversion

#### [module color-convert.hsv.hex](#apidoc.module.color-convert.hsv.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>hex (args)](#apidoc.element.color-convert.hsv.hex.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.hex.</span>raw (args)](#apidoc.element.color-convert.hsv.hex.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsv.hex.</span>conversion

#### [module color-convert.hsv.hsl](#apidoc.module.color-convert.hsv.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>hsl (args)](#apidoc.element.color-convert.hsv.hsl.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.hsl.</span>raw (args)](#apidoc.element.color-convert.hsv.hsl.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsv.hsl.</span>conversion

#### [module color-convert.hsv.hwb](#apidoc.module.color-convert.hsv.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>hwb (args)](#apidoc.element.color-convert.hsv.hwb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.hwb.</span>raw (args)](#apidoc.element.color-convert.hsv.hwb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsv.hwb.</span>conversion

#### [module color-convert.hsv.keyword](#apidoc.module.color-convert.hsv.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>keyword (args)](#apidoc.element.color-convert.hsv.keyword.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.keyword.</span>raw (args)](#apidoc.element.color-convert.hsv.keyword.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsv.keyword.</span>conversion

#### [module color-convert.hsv.lab](#apidoc.module.color-convert.hsv.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>lab (args)](#apidoc.element.color-convert.hsv.lab.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.lab.</span>raw (args)](#apidoc.element.color-convert.hsv.lab.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsv.lab.</span>conversion

#### [module color-convert.hsv.lch](#apidoc.module.color-convert.hsv.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>lch (args)](#apidoc.element.color-convert.hsv.lch.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.lch.</span>raw (args)](#apidoc.element.color-convert.hsv.lch.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsv.lch.</span>conversion

#### [module color-convert.hsv.rgb](#apidoc.module.color-convert.hsv.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>rgb (args)](#apidoc.element.color-convert.hsv.rgb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.rgb.</span>raw (args)](#apidoc.element.color-convert.hsv.rgb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsv.rgb.</span>conversion

#### [module color-convert.hsv.xyz](#apidoc.module.color-convert.hsv.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.</span>xyz (args)](#apidoc.element.color-convert.hsv.xyz.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.hsv.xyz.</span>raw (args)](#apidoc.element.color-convert.hsv.xyz.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hsv.xyz.</span>conversion

#### [module color-convert.hwb](#apidoc.module.color-convert.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>ansi16 (args)](#apidoc.element.color-convert.hwb.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>ansi256 (args)](#apidoc.element.color-convert.hwb.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>apple (args)](#apidoc.element.color-convert.hwb.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>cmyk (args)](#apidoc.element.color-convert.hwb.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>gray (args)](#apidoc.element.color-convert.hwb.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>hcg (args)](#apidoc.element.color-convert.hwb.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>hex (args)](#apidoc.element.color-convert.hwb.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>hsl (args)](#apidoc.element.color-convert.hwb.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>hsv (args)](#apidoc.element.color-convert.hwb.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>keyword (args)](#apidoc.element.color-convert.hwb.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>lab (args)](#apidoc.element.color-convert.hwb.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>lch (args)](#apidoc.element.color-convert.hwb.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>rgb (args)](#apidoc.element.color-convert.hwb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>xyz (args)](#apidoc.element.color-convert.hwb.xyz)

#### [module color-convert.hwb.ansi16](#apidoc.module.color-convert.hwb.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>ansi16 (args)](#apidoc.element.color-convert.hwb.ansi16.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.ansi16.</span>raw (args)](#apidoc.element.color-convert.hwb.ansi16.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hwb.ansi16.</span>conversion

#### [module color-convert.hwb.ansi256](#apidoc.module.color-convert.hwb.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>ansi256 (args)](#apidoc.element.color-convert.hwb.ansi256.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.ansi256.</span>raw (args)](#apidoc.element.color-convert.hwb.ansi256.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hwb.ansi256.</span>conversion

#### [module color-convert.hwb.apple](#apidoc.module.color-convert.hwb.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>apple (args)](#apidoc.element.color-convert.hwb.apple.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.apple.</span>raw (args)](#apidoc.element.color-convert.hwb.apple.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hwb.apple.</span>conversion

#### [module color-convert.hwb.cmyk](#apidoc.module.color-convert.hwb.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>cmyk (args)](#apidoc.element.color-convert.hwb.cmyk.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.cmyk.</span>raw (args)](#apidoc.element.color-convert.hwb.cmyk.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hwb.cmyk.</span>conversion

#### [module color-convert.hwb.gray](#apidoc.module.color-convert.hwb.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>gray (args)](#apidoc.element.color-convert.hwb.gray.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.gray.</span>raw (args)](#apidoc.element.color-convert.hwb.gray.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hwb.gray.</span>conversion

#### [module color-convert.hwb.hcg](#apidoc.module.color-convert.hwb.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>hcg (args)](#apidoc.element.color-convert.hwb.hcg.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.hcg.</span>raw (args)](#apidoc.element.color-convert.hwb.hcg.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hwb.hcg.</span>conversion

#### [module color-convert.hwb.hex](#apidoc.module.color-convert.hwb.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>hex (args)](#apidoc.element.color-convert.hwb.hex.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.hex.</span>raw (args)](#apidoc.element.color-convert.hwb.hex.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hwb.hex.</span>conversion

#### [module color-convert.hwb.hsl](#apidoc.module.color-convert.hwb.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>hsl (args)](#apidoc.element.color-convert.hwb.hsl.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.hsl.</span>raw (args)](#apidoc.element.color-convert.hwb.hsl.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hwb.hsl.</span>conversion

#### [module color-convert.hwb.hsv](#apidoc.module.color-convert.hwb.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>hsv (args)](#apidoc.element.color-convert.hwb.hsv.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.hsv.</span>raw (args)](#apidoc.element.color-convert.hwb.hsv.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hwb.hsv.</span>conversion

#### [module color-convert.hwb.keyword](#apidoc.module.color-convert.hwb.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>keyword (args)](#apidoc.element.color-convert.hwb.keyword.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.keyword.</span>raw (args)](#apidoc.element.color-convert.hwb.keyword.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hwb.keyword.</span>conversion

#### [module color-convert.hwb.lab](#apidoc.module.color-convert.hwb.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>lab (args)](#apidoc.element.color-convert.hwb.lab.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.lab.</span>raw (args)](#apidoc.element.color-convert.hwb.lab.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hwb.lab.</span>conversion

#### [module color-convert.hwb.lch](#apidoc.module.color-convert.hwb.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>lch (args)](#apidoc.element.color-convert.hwb.lch.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.lch.</span>raw (args)](#apidoc.element.color-convert.hwb.lch.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hwb.lch.</span>conversion

#### [module color-convert.hwb.rgb](#apidoc.module.color-convert.hwb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>rgb (args)](#apidoc.element.color-convert.hwb.rgb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.rgb.</span>raw (args)](#apidoc.element.color-convert.hwb.rgb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hwb.rgb.</span>conversion

#### [module color-convert.hwb.xyz](#apidoc.module.color-convert.hwb.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.</span>xyz (args)](#apidoc.element.color-convert.hwb.xyz.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.hwb.xyz.</span>raw (args)](#apidoc.element.color-convert.hwb.xyz.raw)
1.  object <span class="apidocSignatureSpan">color-convert.hwb.xyz.</span>conversion

#### [module color-convert.keyword](#apidoc.module.color-convert.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>ansi16 (args)](#apidoc.element.color-convert.keyword.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>ansi256 (args)](#apidoc.element.color-convert.keyword.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>apple (args)](#apidoc.element.color-convert.keyword.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>cmyk (args)](#apidoc.element.color-convert.keyword.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>gray (args)](#apidoc.element.color-convert.keyword.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>hcg (args)](#apidoc.element.color-convert.keyword.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>hex (args)](#apidoc.element.color-convert.keyword.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>hsl (args)](#apidoc.element.color-convert.keyword.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>hsv (args)](#apidoc.element.color-convert.keyword.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>hwb (args)](#apidoc.element.color-convert.keyword.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>lab (args)](#apidoc.element.color-convert.keyword.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>lch (args)](#apidoc.element.color-convert.keyword.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>rgb (args)](#apidoc.element.color-convert.keyword.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>xyz (args)](#apidoc.element.color-convert.keyword.xyz)

#### [module color-convert.keyword.ansi16](#apidoc.module.color-convert.keyword.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>ansi16 (args)](#apidoc.element.color-convert.keyword.ansi16.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.ansi16.</span>raw (args)](#apidoc.element.color-convert.keyword.ansi16.raw)
1.  object <span class="apidocSignatureSpan">color-convert.keyword.ansi16.</span>conversion

#### [module color-convert.keyword.ansi256](#apidoc.module.color-convert.keyword.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>ansi256 (args)](#apidoc.element.color-convert.keyword.ansi256.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.ansi256.</span>raw (args)](#apidoc.element.color-convert.keyword.ansi256.raw)
1.  object <span class="apidocSignatureSpan">color-convert.keyword.ansi256.</span>conversion

#### [module color-convert.keyword.apple](#apidoc.module.color-convert.keyword.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>apple (args)](#apidoc.element.color-convert.keyword.apple.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.apple.</span>raw (args)](#apidoc.element.color-convert.keyword.apple.raw)
1.  object <span class="apidocSignatureSpan">color-convert.keyword.apple.</span>conversion

#### [module color-convert.keyword.cmyk](#apidoc.module.color-convert.keyword.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>cmyk (args)](#apidoc.element.color-convert.keyword.cmyk.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.cmyk.</span>raw (args)](#apidoc.element.color-convert.keyword.cmyk.raw)
1.  object <span class="apidocSignatureSpan">color-convert.keyword.cmyk.</span>conversion

#### [module color-convert.keyword.gray](#apidoc.module.color-convert.keyword.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>gray (args)](#apidoc.element.color-convert.keyword.gray.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.gray.</span>raw (args)](#apidoc.element.color-convert.keyword.gray.raw)
1.  object <span class="apidocSignatureSpan">color-convert.keyword.gray.</span>conversion

#### [module color-convert.keyword.hcg](#apidoc.module.color-convert.keyword.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>hcg (args)](#apidoc.element.color-convert.keyword.hcg.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.hcg.</span>raw (args)](#apidoc.element.color-convert.keyword.hcg.raw)
1.  object <span class="apidocSignatureSpan">color-convert.keyword.hcg.</span>conversion

#### [module color-convert.keyword.hex](#apidoc.module.color-convert.keyword.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>hex (args)](#apidoc.element.color-convert.keyword.hex.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.hex.</span>raw (args)](#apidoc.element.color-convert.keyword.hex.raw)
1.  object <span class="apidocSignatureSpan">color-convert.keyword.hex.</span>conversion

#### [module color-convert.keyword.hsl](#apidoc.module.color-convert.keyword.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>hsl (args)](#apidoc.element.color-convert.keyword.hsl.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.hsl.</span>raw (args)](#apidoc.element.color-convert.keyword.hsl.raw)
1.  object <span class="apidocSignatureSpan">color-convert.keyword.hsl.</span>conversion

#### [module color-convert.keyword.hsv](#apidoc.module.color-convert.keyword.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>hsv (args)](#apidoc.element.color-convert.keyword.hsv.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.hsv.</span>raw (args)](#apidoc.element.color-convert.keyword.hsv.raw)
1.  object <span class="apidocSignatureSpan">color-convert.keyword.hsv.</span>conversion

#### [module color-convert.keyword.hwb](#apidoc.module.color-convert.keyword.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>hwb (args)](#apidoc.element.color-convert.keyword.hwb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.hwb.</span>raw (args)](#apidoc.element.color-convert.keyword.hwb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.keyword.hwb.</span>conversion

#### [module color-convert.keyword.lab](#apidoc.module.color-convert.keyword.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>lab (args)](#apidoc.element.color-convert.keyword.lab.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.lab.</span>raw (args)](#apidoc.element.color-convert.keyword.lab.raw)
1.  object <span class="apidocSignatureSpan">color-convert.keyword.lab.</span>conversion

#### [module color-convert.keyword.lch](#apidoc.module.color-convert.keyword.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>lch (args)](#apidoc.element.color-convert.keyword.lch.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.lch.</span>raw (args)](#apidoc.element.color-convert.keyword.lch.raw)
1.  object <span class="apidocSignatureSpan">color-convert.keyword.lch.</span>conversion

#### [module color-convert.keyword.rgb](#apidoc.module.color-convert.keyword.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>rgb (args)](#apidoc.element.color-convert.keyword.rgb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.rgb.</span>raw (args)](#apidoc.element.color-convert.keyword.rgb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.keyword.rgb.</span>conversion

#### [module color-convert.keyword.xyz](#apidoc.module.color-convert.keyword.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.</span>xyz (args)](#apidoc.element.color-convert.keyword.xyz.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.keyword.xyz.</span>raw (args)](#apidoc.element.color-convert.keyword.xyz.raw)
1.  object <span class="apidocSignatureSpan">color-convert.keyword.xyz.</span>conversion

#### [module color-convert.lab](#apidoc.module.color-convert.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>ansi16 (args)](#apidoc.element.color-convert.lab.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>ansi256 (args)](#apidoc.element.color-convert.lab.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>apple (args)](#apidoc.element.color-convert.lab.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>cmyk (args)](#apidoc.element.color-convert.lab.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>gray (args)](#apidoc.element.color-convert.lab.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>hcg (args)](#apidoc.element.color-convert.lab.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>hex (args)](#apidoc.element.color-convert.lab.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>hsl (args)](#apidoc.element.color-convert.lab.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>hsv (args)](#apidoc.element.color-convert.lab.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>hwb (args)](#apidoc.element.color-convert.lab.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>keyword (args)](#apidoc.element.color-convert.lab.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>lch (args)](#apidoc.element.color-convert.lab.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>rgb (args)](#apidoc.element.color-convert.lab.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>xyz (args)](#apidoc.element.color-convert.lab.xyz)

#### [module color-convert.lab.ansi16](#apidoc.module.color-convert.lab.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>ansi16 (args)](#apidoc.element.color-convert.lab.ansi16.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.ansi16.</span>raw (args)](#apidoc.element.color-convert.lab.ansi16.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lab.ansi16.</span>conversion

#### [module color-convert.lab.ansi256](#apidoc.module.color-convert.lab.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>ansi256 (args)](#apidoc.element.color-convert.lab.ansi256.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.ansi256.</span>raw (args)](#apidoc.element.color-convert.lab.ansi256.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lab.ansi256.</span>conversion

#### [module color-convert.lab.apple](#apidoc.module.color-convert.lab.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>apple (args)](#apidoc.element.color-convert.lab.apple.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.apple.</span>raw (args)](#apidoc.element.color-convert.lab.apple.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lab.apple.</span>conversion

#### [module color-convert.lab.cmyk](#apidoc.module.color-convert.lab.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>cmyk (args)](#apidoc.element.color-convert.lab.cmyk.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.cmyk.</span>raw (args)](#apidoc.element.color-convert.lab.cmyk.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lab.cmyk.</span>conversion

#### [module color-convert.lab.gray](#apidoc.module.color-convert.lab.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>gray (args)](#apidoc.element.color-convert.lab.gray.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.gray.</span>raw (args)](#apidoc.element.color-convert.lab.gray.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lab.gray.</span>conversion

#### [module color-convert.lab.hcg](#apidoc.module.color-convert.lab.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>hcg (args)](#apidoc.element.color-convert.lab.hcg.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.hcg.</span>raw (args)](#apidoc.element.color-convert.lab.hcg.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lab.hcg.</span>conversion

#### [module color-convert.lab.hex](#apidoc.module.color-convert.lab.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>hex (args)](#apidoc.element.color-convert.lab.hex.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.hex.</span>raw (args)](#apidoc.element.color-convert.lab.hex.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lab.hex.</span>conversion

#### [module color-convert.lab.hsl](#apidoc.module.color-convert.lab.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>hsl (args)](#apidoc.element.color-convert.lab.hsl.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.hsl.</span>raw (args)](#apidoc.element.color-convert.lab.hsl.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lab.hsl.</span>conversion

#### [module color-convert.lab.hsv](#apidoc.module.color-convert.lab.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>hsv (args)](#apidoc.element.color-convert.lab.hsv.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.hsv.</span>raw (args)](#apidoc.element.color-convert.lab.hsv.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lab.hsv.</span>conversion

#### [module color-convert.lab.hwb](#apidoc.module.color-convert.lab.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>hwb (args)](#apidoc.element.color-convert.lab.hwb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.hwb.</span>raw (args)](#apidoc.element.color-convert.lab.hwb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lab.hwb.</span>conversion

#### [module color-convert.lab.keyword](#apidoc.module.color-convert.lab.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>keyword (args)](#apidoc.element.color-convert.lab.keyword.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.keyword.</span>raw (args)](#apidoc.element.color-convert.lab.keyword.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lab.keyword.</span>conversion

#### [module color-convert.lab.lch](#apidoc.module.color-convert.lab.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>lch (args)](#apidoc.element.color-convert.lab.lch.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.lch.</span>raw (args)](#apidoc.element.color-convert.lab.lch.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lab.lch.</span>conversion

#### [module color-convert.lab.rgb](#apidoc.module.color-convert.lab.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>rgb (args)](#apidoc.element.color-convert.lab.rgb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.rgb.</span>raw (args)](#apidoc.element.color-convert.lab.rgb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lab.rgb.</span>conversion

#### [module color-convert.lab.xyz](#apidoc.module.color-convert.lab.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.</span>xyz (args)](#apidoc.element.color-convert.lab.xyz.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.lab.xyz.</span>raw (args)](#apidoc.element.color-convert.lab.xyz.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lab.xyz.</span>conversion

#### [module color-convert.lch](#apidoc.module.color-convert.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>ansi16 (args)](#apidoc.element.color-convert.lch.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>ansi256 (args)](#apidoc.element.color-convert.lch.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>apple (args)](#apidoc.element.color-convert.lch.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>cmyk (args)](#apidoc.element.color-convert.lch.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>gray (args)](#apidoc.element.color-convert.lch.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>hcg (args)](#apidoc.element.color-convert.lch.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>hex (args)](#apidoc.element.color-convert.lch.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>hsl (args)](#apidoc.element.color-convert.lch.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>hsv (args)](#apidoc.element.color-convert.lch.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>hwb (args)](#apidoc.element.color-convert.lch.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>keyword (args)](#apidoc.element.color-convert.lch.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>lab (args)](#apidoc.element.color-convert.lch.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>rgb (args)](#apidoc.element.color-convert.lch.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>xyz (args)](#apidoc.element.color-convert.lch.xyz)

#### [module color-convert.lch.ansi16](#apidoc.module.color-convert.lch.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>ansi16 (args)](#apidoc.element.color-convert.lch.ansi16.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.ansi16.</span>raw (args)](#apidoc.element.color-convert.lch.ansi16.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lch.ansi16.</span>conversion

#### [module color-convert.lch.ansi256](#apidoc.module.color-convert.lch.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>ansi256 (args)](#apidoc.element.color-convert.lch.ansi256.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.ansi256.</span>raw (args)](#apidoc.element.color-convert.lch.ansi256.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lch.ansi256.</span>conversion

#### [module color-convert.lch.apple](#apidoc.module.color-convert.lch.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>apple (args)](#apidoc.element.color-convert.lch.apple.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.apple.</span>raw (args)](#apidoc.element.color-convert.lch.apple.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lch.apple.</span>conversion

#### [module color-convert.lch.cmyk](#apidoc.module.color-convert.lch.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>cmyk (args)](#apidoc.element.color-convert.lch.cmyk.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.cmyk.</span>raw (args)](#apidoc.element.color-convert.lch.cmyk.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lch.cmyk.</span>conversion

#### [module color-convert.lch.gray](#apidoc.module.color-convert.lch.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>gray (args)](#apidoc.element.color-convert.lch.gray.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.gray.</span>raw (args)](#apidoc.element.color-convert.lch.gray.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lch.gray.</span>conversion

#### [module color-convert.lch.hcg](#apidoc.module.color-convert.lch.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>hcg (args)](#apidoc.element.color-convert.lch.hcg.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.hcg.</span>raw (args)](#apidoc.element.color-convert.lch.hcg.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lch.hcg.</span>conversion

#### [module color-convert.lch.hex](#apidoc.module.color-convert.lch.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>hex (args)](#apidoc.element.color-convert.lch.hex.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.hex.</span>raw (args)](#apidoc.element.color-convert.lch.hex.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lch.hex.</span>conversion

#### [module color-convert.lch.hsl](#apidoc.module.color-convert.lch.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>hsl (args)](#apidoc.element.color-convert.lch.hsl.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.hsl.</span>raw (args)](#apidoc.element.color-convert.lch.hsl.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lch.hsl.</span>conversion

#### [module color-convert.lch.hsv](#apidoc.module.color-convert.lch.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>hsv (args)](#apidoc.element.color-convert.lch.hsv.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.hsv.</span>raw (args)](#apidoc.element.color-convert.lch.hsv.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lch.hsv.</span>conversion

#### [module color-convert.lch.hwb](#apidoc.module.color-convert.lch.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>hwb (args)](#apidoc.element.color-convert.lch.hwb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.hwb.</span>raw (args)](#apidoc.element.color-convert.lch.hwb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lch.hwb.</span>conversion

#### [module color-convert.lch.keyword](#apidoc.module.color-convert.lch.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>keyword (args)](#apidoc.element.color-convert.lch.keyword.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.keyword.</span>raw (args)](#apidoc.element.color-convert.lch.keyword.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lch.keyword.</span>conversion

#### [module color-convert.lch.lab](#apidoc.module.color-convert.lch.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>lab (args)](#apidoc.element.color-convert.lch.lab.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.lab.</span>raw (args)](#apidoc.element.color-convert.lch.lab.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lch.lab.</span>conversion

#### [module color-convert.lch.rgb](#apidoc.module.color-convert.lch.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>rgb (args)](#apidoc.element.color-convert.lch.rgb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.rgb.</span>raw (args)](#apidoc.element.color-convert.lch.rgb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lch.rgb.</span>conversion

#### [module color-convert.lch.xyz](#apidoc.module.color-convert.lch.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.</span>xyz (args)](#apidoc.element.color-convert.lch.xyz.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.lch.xyz.</span>raw (args)](#apidoc.element.color-convert.lch.xyz.raw)
1.  object <span class="apidocSignatureSpan">color-convert.lch.xyz.</span>conversion

#### [module color-convert.rgb](#apidoc.module.color-convert.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>ansi16 (args)](#apidoc.element.color-convert.rgb.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>ansi256 (args)](#apidoc.element.color-convert.rgb.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>apple (args)](#apidoc.element.color-convert.rgb.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>cmyk (args)](#apidoc.element.color-convert.rgb.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>gray (args)](#apidoc.element.color-convert.rgb.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>hcg (args)](#apidoc.element.color-convert.rgb.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>hex (args)](#apidoc.element.color-convert.rgb.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>hsl (args)](#apidoc.element.color-convert.rgb.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>hsv (args)](#apidoc.element.color-convert.rgb.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>hwb (args)](#apidoc.element.color-convert.rgb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>keyword (args)](#apidoc.element.color-convert.rgb.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>lab (args)](#apidoc.element.color-convert.rgb.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>lch (args)](#apidoc.element.color-convert.rgb.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>xyz (args)](#apidoc.element.color-convert.rgb.xyz)

#### [module color-convert.rgb.ansi16](#apidoc.module.color-convert.rgb.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>ansi16 (args)](#apidoc.element.color-convert.rgb.ansi16.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.ansi16.</span>raw (args)](#apidoc.element.color-convert.rgb.ansi16.raw)
1.  object <span class="apidocSignatureSpan">color-convert.rgb.ansi16.</span>conversion

#### [module color-convert.rgb.ansi256](#apidoc.module.color-convert.rgb.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>ansi256 (args)](#apidoc.element.color-convert.rgb.ansi256.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.ansi256.</span>raw (args)](#apidoc.element.color-convert.rgb.ansi256.raw)
1.  object <span class="apidocSignatureSpan">color-convert.rgb.ansi256.</span>conversion

#### [module color-convert.rgb.apple](#apidoc.module.color-convert.rgb.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>apple (args)](#apidoc.element.color-convert.rgb.apple.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.apple.</span>raw (args)](#apidoc.element.color-convert.rgb.apple.raw)
1.  object <span class="apidocSignatureSpan">color-convert.rgb.apple.</span>conversion

#### [module color-convert.rgb.cmyk](#apidoc.module.color-convert.rgb.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>cmyk (args)](#apidoc.element.color-convert.rgb.cmyk.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.cmyk.</span>raw (args)](#apidoc.element.color-convert.rgb.cmyk.raw)
1.  object <span class="apidocSignatureSpan">color-convert.rgb.cmyk.</span>conversion

#### [module color-convert.rgb.gray](#apidoc.module.color-convert.rgb.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>gray (args)](#apidoc.element.color-convert.rgb.gray.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.gray.</span>raw (args)](#apidoc.element.color-convert.rgb.gray.raw)
1.  object <span class="apidocSignatureSpan">color-convert.rgb.gray.</span>conversion

#### [module color-convert.rgb.hcg](#apidoc.module.color-convert.rgb.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>hcg (args)](#apidoc.element.color-convert.rgb.hcg.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.hcg.</span>raw (args)](#apidoc.element.color-convert.rgb.hcg.raw)
1.  object <span class="apidocSignatureSpan">color-convert.rgb.hcg.</span>conversion

#### [module color-convert.rgb.hex](#apidoc.module.color-convert.rgb.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>hex (args)](#apidoc.element.color-convert.rgb.hex.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.hex.</span>raw (args)](#apidoc.element.color-convert.rgb.hex.raw)
1.  object <span class="apidocSignatureSpan">color-convert.rgb.hex.</span>conversion

#### [module color-convert.rgb.hsl](#apidoc.module.color-convert.rgb.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>hsl (args)](#apidoc.element.color-convert.rgb.hsl.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.hsl.</span>raw (args)](#apidoc.element.color-convert.rgb.hsl.raw)
1.  object <span class="apidocSignatureSpan">color-convert.rgb.hsl.</span>conversion

#### [module color-convert.rgb.hsv](#apidoc.module.color-convert.rgb.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>hsv (args)](#apidoc.element.color-convert.rgb.hsv.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.hsv.</span>raw (args)](#apidoc.element.color-convert.rgb.hsv.raw)
1.  object <span class="apidocSignatureSpan">color-convert.rgb.hsv.</span>conversion

#### [module color-convert.rgb.hwb](#apidoc.module.color-convert.rgb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>hwb (args)](#apidoc.element.color-convert.rgb.hwb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.hwb.</span>raw (args)](#apidoc.element.color-convert.rgb.hwb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.rgb.hwb.</span>conversion

#### [module color-convert.rgb.keyword](#apidoc.module.color-convert.rgb.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>keyword (args)](#apidoc.element.color-convert.rgb.keyword.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.keyword.</span>raw (args)](#apidoc.element.color-convert.rgb.keyword.raw)
1.  object <span class="apidocSignatureSpan">color-convert.rgb.keyword.</span>conversion

#### [module color-convert.rgb.lab](#apidoc.module.color-convert.rgb.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>lab (args)](#apidoc.element.color-convert.rgb.lab.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.lab.</span>raw (args)](#apidoc.element.color-convert.rgb.lab.raw)
1.  object <span class="apidocSignatureSpan">color-convert.rgb.lab.</span>conversion

#### [module color-convert.rgb.lch](#apidoc.module.color-convert.rgb.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>lch (args)](#apidoc.element.color-convert.rgb.lch.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.lch.</span>raw (args)](#apidoc.element.color-convert.rgb.lch.raw)
1.  object <span class="apidocSignatureSpan">color-convert.rgb.lch.</span>conversion

#### [module color-convert.rgb.xyz](#apidoc.module.color-convert.rgb.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.</span>xyz (args)](#apidoc.element.color-convert.rgb.xyz.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.rgb.xyz.</span>raw (args)](#apidoc.element.color-convert.rgb.xyz.raw)
1.  object <span class="apidocSignatureSpan">color-convert.rgb.xyz.</span>conversion

#### [module color-convert.xyz](#apidoc.module.color-convert.xyz)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>ansi16 (args)](#apidoc.element.color-convert.xyz.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>ansi256 (args)](#apidoc.element.color-convert.xyz.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>apple (args)](#apidoc.element.color-convert.xyz.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>cmyk (args)](#apidoc.element.color-convert.xyz.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>gray (args)](#apidoc.element.color-convert.xyz.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>hcg (args)](#apidoc.element.color-convert.xyz.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>hex (args)](#apidoc.element.color-convert.xyz.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>hsl (args)](#apidoc.element.color-convert.xyz.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>hsv (args)](#apidoc.element.color-convert.xyz.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>hwb (args)](#apidoc.element.color-convert.xyz.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>keyword (args)](#apidoc.element.color-convert.xyz.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>lab (args)](#apidoc.element.color-convert.xyz.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>lch (args)](#apidoc.element.color-convert.xyz.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>rgb (args)](#apidoc.element.color-convert.xyz.rgb)

#### [module color-convert.xyz.ansi16](#apidoc.module.color-convert.xyz.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>ansi16 (args)](#apidoc.element.color-convert.xyz.ansi16.ansi16)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.ansi16.</span>raw (args)](#apidoc.element.color-convert.xyz.ansi16.raw)
1.  object <span class="apidocSignatureSpan">color-convert.xyz.ansi16.</span>conversion

#### [module color-convert.xyz.ansi256](#apidoc.module.color-convert.xyz.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>ansi256 (args)](#apidoc.element.color-convert.xyz.ansi256.ansi256)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.ansi256.</span>raw (args)](#apidoc.element.color-convert.xyz.ansi256.raw)
1.  object <span class="apidocSignatureSpan">color-convert.xyz.ansi256.</span>conversion

#### [module color-convert.xyz.apple](#apidoc.module.color-convert.xyz.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>apple (args)](#apidoc.element.color-convert.xyz.apple.apple)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.apple.</span>raw (args)](#apidoc.element.color-convert.xyz.apple.raw)
1.  object <span class="apidocSignatureSpan">color-convert.xyz.apple.</span>conversion

#### [module color-convert.xyz.cmyk](#apidoc.module.color-convert.xyz.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>cmyk (args)](#apidoc.element.color-convert.xyz.cmyk.cmyk)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.cmyk.</span>raw (args)](#apidoc.element.color-convert.xyz.cmyk.raw)
1.  object <span class="apidocSignatureSpan">color-convert.xyz.cmyk.</span>conversion

#### [module color-convert.xyz.gray](#apidoc.module.color-convert.xyz.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>gray (args)](#apidoc.element.color-convert.xyz.gray.gray)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.gray.</span>raw (args)](#apidoc.element.color-convert.xyz.gray.raw)
1.  object <span class="apidocSignatureSpan">color-convert.xyz.gray.</span>conversion

#### [module color-convert.xyz.hcg](#apidoc.module.color-convert.xyz.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>hcg (args)](#apidoc.element.color-convert.xyz.hcg.hcg)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.hcg.</span>raw (args)](#apidoc.element.color-convert.xyz.hcg.raw)
1.  object <span class="apidocSignatureSpan">color-convert.xyz.hcg.</span>conversion

#### [module color-convert.xyz.hex](#apidoc.module.color-convert.xyz.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>hex (args)](#apidoc.element.color-convert.xyz.hex.hex)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.hex.</span>raw (args)](#apidoc.element.color-convert.xyz.hex.raw)
1.  object <span class="apidocSignatureSpan">color-convert.xyz.hex.</span>conversion

#### [module color-convert.xyz.hsl](#apidoc.module.color-convert.xyz.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>hsl (args)](#apidoc.element.color-convert.xyz.hsl.hsl)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.hsl.</span>raw (args)](#apidoc.element.color-convert.xyz.hsl.raw)
1.  object <span class="apidocSignatureSpan">color-convert.xyz.hsl.</span>conversion

#### [module color-convert.xyz.hsv](#apidoc.module.color-convert.xyz.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>hsv (args)](#apidoc.element.color-convert.xyz.hsv.hsv)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.hsv.</span>raw (args)](#apidoc.element.color-convert.xyz.hsv.raw)
1.  object <span class="apidocSignatureSpan">color-convert.xyz.hsv.</span>conversion

#### [module color-convert.xyz.hwb](#apidoc.module.color-convert.xyz.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>hwb (args)](#apidoc.element.color-convert.xyz.hwb.hwb)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.hwb.</span>raw (args)](#apidoc.element.color-convert.xyz.hwb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.xyz.hwb.</span>conversion

#### [module color-convert.xyz.keyword](#apidoc.module.color-convert.xyz.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>keyword (args)](#apidoc.element.color-convert.xyz.keyword.keyword)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.keyword.</span>raw (args)](#apidoc.element.color-convert.xyz.keyword.raw)
1.  object <span class="apidocSignatureSpan">color-convert.xyz.keyword.</span>conversion

#### [module color-convert.xyz.lab](#apidoc.module.color-convert.xyz.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>lab (args)](#apidoc.element.color-convert.xyz.lab.lab)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.lab.</span>raw (args)](#apidoc.element.color-convert.xyz.lab.raw)
1.  object <span class="apidocSignatureSpan">color-convert.xyz.lab.</span>conversion

#### [module color-convert.xyz.lch](#apidoc.module.color-convert.xyz.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>lch (args)](#apidoc.element.color-convert.xyz.lch.lch)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.lch.</span>raw (args)](#apidoc.element.color-convert.xyz.lch.raw)
1.  object <span class="apidocSignatureSpan">color-convert.xyz.lch.</span>conversion

#### [module color-convert.xyz.rgb](#apidoc.module.color-convert.xyz.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.</span>rgb (args)](#apidoc.element.color-convert.xyz.rgb.rgb)
1.  [function <span class="apidocSignatureSpan">color-convert.xyz.rgb.</span>raw (args)](#apidoc.element.color-convert.xyz.rgb.raw)
1.  object <span class="apidocSignatureSpan">color-convert.xyz.rgb.</span>conversion



# <a name="apidoc.module.color-convert"></a>[module color-convert](#apidoc.module.color-convert)

#### <a name="apidoc.element.color-convert.ansi16.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi16.ansi256 (args)](#apidoc.element.color-convert.ansi16.ansi256)
- description and source-code
```javascript
ansi16.ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.apple"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi16.apple (args)](#apidoc.element.color-convert.ansi16.apple)
- description and source-code
```javascript
ansi16.apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi16.cmyk (args)](#apidoc.element.color-convert.ansi16.cmyk)
- description and source-code
```javascript
ansi16.cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.gray"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi16.gray (args)](#apidoc.element.color-convert.ansi16.gray)
- description and source-code
```javascript
ansi16.gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi16.hcg (args)](#apidoc.element.color-convert.ansi16.hcg)
- description and source-code
```javascript
ansi16.hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.hex"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi16.hex (args)](#apidoc.element.color-convert.ansi16.hex)
- description and source-code
```javascript
ansi16.hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi16.hsl (args)](#apidoc.element.color-convert.ansi16.hsl)
- description and source-code
```javascript
ansi16.hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi16.hsv (args)](#apidoc.element.color-convert.ansi16.hsv)
- description and source-code
```javascript
ansi16.hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi16.hwb (args)](#apidoc.element.color-convert.ansi16.hwb)
- description and source-code
```javascript
ansi16.hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi16.keyword (args)](#apidoc.element.color-convert.ansi16.keyword)
- description and source-code
```javascript
ansi16.keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.lab"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi16.lab (args)](#apidoc.element.color-convert.ansi16.lab)
- description and source-code
```javascript
ansi16.lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.lch"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi16.lch (args)](#apidoc.element.color-convert.ansi16.lch)
- description and source-code
```javascript
ansi16.lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi16.rgb (args)](#apidoc.element.color-convert.ansi16.rgb)
- description and source-code
```javascript
ansi16.rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi16.xyz (args)](#apidoc.element.color-convert.ansi16.xyz)
- description and source-code
```javascript
ansi16.xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi256.ansi16 (args)](#apidoc.element.color-convert.ansi256.ansi16)
- description and source-code
```javascript
ansi256.ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.apple"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi256.apple (args)](#apidoc.element.color-convert.ansi256.apple)
- description and source-code
```javascript
ansi256.apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi256.cmyk (args)](#apidoc.element.color-convert.ansi256.cmyk)
- description and source-code
```javascript
ansi256.cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.gray"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi256.gray (args)](#apidoc.element.color-convert.ansi256.gray)
- description and source-code
```javascript
ansi256.gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi256.hcg (args)](#apidoc.element.color-convert.ansi256.hcg)
- description and source-code
```javascript
ansi256.hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.hex"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi256.hex (args)](#apidoc.element.color-convert.ansi256.hex)
- description and source-code
```javascript
ansi256.hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi256.hsl (args)](#apidoc.element.color-convert.ansi256.hsl)
- description and source-code
```javascript
ansi256.hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi256.hsv (args)](#apidoc.element.color-convert.ansi256.hsv)
- description and source-code
```javascript
ansi256.hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi256.hwb (args)](#apidoc.element.color-convert.ansi256.hwb)
- description and source-code
```javascript
ansi256.hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi256.keyword (args)](#apidoc.element.color-convert.ansi256.keyword)
- description and source-code
```javascript
ansi256.keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.lab"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi256.lab (args)](#apidoc.element.color-convert.ansi256.lab)
- description and source-code
```javascript
ansi256.lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.lch"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi256.lch (args)](#apidoc.element.color-convert.ansi256.lch)
- description and source-code
```javascript
ansi256.lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi256.rgb (args)](#apidoc.element.color-convert.ansi256.rgb)
- description and source-code
```javascript
ansi256.rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.</span>ansi256.xyz (args)](#apidoc.element.color-convert.ansi256.xyz)
- description and source-code
```javascript
ansi256.xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.</span>apple.ansi16 (args)](#apidoc.element.color-convert.apple.ansi16)
- description and source-code
```javascript
apple.ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.</span>apple.ansi256 (args)](#apidoc.element.color-convert.apple.ansi256)
- description and source-code
```javascript
apple.ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.</span>apple.cmyk (args)](#apidoc.element.color-convert.apple.cmyk)
- description and source-code
```javascript
apple.cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.gray"></a>[function <span class="apidocSignatureSpan">color-convert.</span>apple.gray (args)](#apidoc.element.color-convert.apple.gray)
- description and source-code
```javascript
apple.gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.</span>apple.hcg (args)](#apidoc.element.color-convert.apple.hcg)
- description and source-code
```javascript
apple.hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.hex"></a>[function <span class="apidocSignatureSpan">color-convert.</span>apple.hex (args)](#apidoc.element.color-convert.apple.hex)
- description and source-code
```javascript
apple.hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.</span>apple.hsl (args)](#apidoc.element.color-convert.apple.hsl)
- description and source-code
```javascript
apple.hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.</span>apple.hsv (args)](#apidoc.element.color-convert.apple.hsv)
- description and source-code
```javascript
apple.hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>apple.hwb (args)](#apidoc.element.color-convert.apple.hwb)
- description and source-code
```javascript
apple.hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.</span>apple.keyword (args)](#apidoc.element.color-convert.apple.keyword)
- description and source-code
```javascript
apple.keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.lab"></a>[function <span class="apidocSignatureSpan">color-convert.</span>apple.lab (args)](#apidoc.element.color-convert.apple.lab)
- description and source-code
```javascript
apple.lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.lch"></a>[function <span class="apidocSignatureSpan">color-convert.</span>apple.lch (args)](#apidoc.element.color-convert.apple.lch)
- description and source-code
```javascript
apple.lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>apple.rgb (args)](#apidoc.element.color-convert.apple.rgb)
- description and source-code
```javascript
apple.rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.</span>apple.xyz (args)](#apidoc.element.color-convert.apple.xyz)
- description and source-code
```javascript
apple.xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.</span>cmyk.ansi16 (args)](#apidoc.element.color-convert.cmyk.ansi16)
- description and source-code
```javascript
cmyk.ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.</span>cmyk.ansi256 (args)](#apidoc.element.color-convert.cmyk.ansi256)
- description and source-code
```javascript
cmyk.ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.apple"></a>[function <span class="apidocSignatureSpan">color-convert.</span>cmyk.apple (args)](#apidoc.element.color-convert.cmyk.apple)
- description and source-code
```javascript
cmyk.apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.gray"></a>[function <span class="apidocSignatureSpan">color-convert.</span>cmyk.gray (args)](#apidoc.element.color-convert.cmyk.gray)
- description and source-code
```javascript
cmyk.gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.</span>cmyk.hcg (args)](#apidoc.element.color-convert.cmyk.hcg)
- description and source-code
```javascript
cmyk.hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.hex"></a>[function <span class="apidocSignatureSpan">color-convert.</span>cmyk.hex (args)](#apidoc.element.color-convert.cmyk.hex)
- description and source-code
```javascript
cmyk.hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.</span>cmyk.hsl (args)](#apidoc.element.color-convert.cmyk.hsl)
- description and source-code
```javascript
cmyk.hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.</span>cmyk.hsv (args)](#apidoc.element.color-convert.cmyk.hsv)
- description and source-code
```javascript
cmyk.hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>cmyk.hwb (args)](#apidoc.element.color-convert.cmyk.hwb)
- description and source-code
```javascript
cmyk.hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.</span>cmyk.keyword (args)](#apidoc.element.color-convert.cmyk.keyword)
- description and source-code
```javascript
cmyk.keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.lab"></a>[function <span class="apidocSignatureSpan">color-convert.</span>cmyk.lab (args)](#apidoc.element.color-convert.cmyk.lab)
- description and source-code
```javascript
cmyk.lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.lch"></a>[function <span class="apidocSignatureSpan">color-convert.</span>cmyk.lch (args)](#apidoc.element.color-convert.cmyk.lch)
- description and source-code
```javascript
cmyk.lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>cmyk.rgb (args)](#apidoc.element.color-convert.cmyk.rgb)
- description and source-code
```javascript
cmyk.rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.</span>cmyk.xyz (args)](#apidoc.element.color-convert.cmyk.xyz)
- description and source-code
```javascript
cmyk.xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.</span>gray.ansi16 (args)](#apidoc.element.color-convert.gray.ansi16)
- description and source-code
```javascript
gray.ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.</span>gray.ansi256 (args)](#apidoc.element.color-convert.gray.ansi256)
- description and source-code
```javascript
gray.ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.apple"></a>[function <span class="apidocSignatureSpan">color-convert.</span>gray.apple (args)](#apidoc.element.color-convert.gray.apple)
- description and source-code
```javascript
gray.apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.</span>gray.cmyk (args)](#apidoc.element.color-convert.gray.cmyk)
- description and source-code
```javascript
gray.cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.</span>gray.hcg (args)](#apidoc.element.color-convert.gray.hcg)
- description and source-code
```javascript
gray.hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.hex"></a>[function <span class="apidocSignatureSpan">color-convert.</span>gray.hex (args)](#apidoc.element.color-convert.gray.hex)
- description and source-code
```javascript
gray.hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.</span>gray.hsl (args)](#apidoc.element.color-convert.gray.hsl)
- description and source-code
```javascript
gray.hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.</span>gray.hsv (args)](#apidoc.element.color-convert.gray.hsv)
- description and source-code
```javascript
gray.hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>gray.hwb (args)](#apidoc.element.color-convert.gray.hwb)
- description and source-code
```javascript
gray.hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.</span>gray.keyword (args)](#apidoc.element.color-convert.gray.keyword)
- description and source-code
```javascript
gray.keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.lab"></a>[function <span class="apidocSignatureSpan">color-convert.</span>gray.lab (args)](#apidoc.element.color-convert.gray.lab)
- description and source-code
```javascript
gray.lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.lch"></a>[function <span class="apidocSignatureSpan">color-convert.</span>gray.lch (args)](#apidoc.element.color-convert.gray.lch)
- description and source-code
```javascript
gray.lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>gray.rgb (args)](#apidoc.element.color-convert.gray.rgb)
- description and source-code
```javascript
gray.rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.</span>gray.xyz (args)](#apidoc.element.color-convert.gray.xyz)
- description and source-code
```javascript
gray.xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hcg.ansi16 (args)](#apidoc.element.color-convert.hcg.ansi16)
- description and source-code
```javascript
hcg.ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hcg.ansi256 (args)](#apidoc.element.color-convert.hcg.ansi256)
- description and source-code
```javascript
hcg.ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.apple"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hcg.apple (args)](#apidoc.element.color-convert.hcg.apple)
- description and source-code
```javascript
hcg.apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hcg.cmyk (args)](#apidoc.element.color-convert.hcg.cmyk)
- description and source-code
```javascript
hcg.cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.gray"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hcg.gray (args)](#apidoc.element.color-convert.hcg.gray)
- description and source-code
```javascript
hcg.gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.hex"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hcg.hex (args)](#apidoc.element.color-convert.hcg.hex)
- description and source-code
```javascript
hcg.hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hcg.hsl (args)](#apidoc.element.color-convert.hcg.hsl)
- description and source-code
```javascript
hcg.hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hcg.hsv (args)](#apidoc.element.color-convert.hcg.hsv)
- description and source-code
```javascript
hcg.hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hcg.hwb (args)](#apidoc.element.color-convert.hcg.hwb)
- description and source-code
```javascript
hcg.hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hcg.keyword (args)](#apidoc.element.color-convert.hcg.keyword)
- description and source-code
```javascript
hcg.keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.lab"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hcg.lab (args)](#apidoc.element.color-convert.hcg.lab)
- description and source-code
```javascript
hcg.lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.lch"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hcg.lch (args)](#apidoc.element.color-convert.hcg.lch)
- description and source-code
```javascript
hcg.lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hcg.rgb (args)](#apidoc.element.color-convert.hcg.rgb)
- description and source-code
```javascript
hcg.rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hcg.xyz (args)](#apidoc.element.color-convert.hcg.xyz)
- description and source-code
```javascript
hcg.xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hex.ansi16 (args)](#apidoc.element.color-convert.hex.ansi16)
- description and source-code
```javascript
hex.ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hex.ansi256 (args)](#apidoc.element.color-convert.hex.ansi256)
- description and source-code
```javascript
hex.ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.apple"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hex.apple (args)](#apidoc.element.color-convert.hex.apple)
- description and source-code
```javascript
hex.apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hex.cmyk (args)](#apidoc.element.color-convert.hex.cmyk)
- description and source-code
```javascript
hex.cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.gray"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hex.gray (args)](#apidoc.element.color-convert.hex.gray)
- description and source-code
```javascript
hex.gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hex.hcg (args)](#apidoc.element.color-convert.hex.hcg)
- description and source-code
```javascript
hex.hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hex.hsl (args)](#apidoc.element.color-convert.hex.hsl)
- description and source-code
```javascript
hex.hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hex.hsv (args)](#apidoc.element.color-convert.hex.hsv)
- description and source-code
```javascript
hex.hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hex.hwb (args)](#apidoc.element.color-convert.hex.hwb)
- description and source-code
```javascript
hex.hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hex.keyword (args)](#apidoc.element.color-convert.hex.keyword)
- description and source-code
```javascript
hex.keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.lab"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hex.lab (args)](#apidoc.element.color-convert.hex.lab)
- description and source-code
```javascript
hex.lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.hex.lch"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hex.lch (args)](#apidoc.element.color-convert.hex.lch)
- description and source-code
```javascript
hex.lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hex.rgb (args)](#apidoc.element.color-convert.hex.rgb)
- description and source-code
```javascript
hex.rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hex.xyz (args)](#apidoc.element.color-convert.hex.xyz)
- description and source-code
```javascript
hex.xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsl.ansi16 (args)](#apidoc.element.color-convert.hsl.ansi16)
- description and source-code
```javascript
hsl.ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsl.ansi256 (args)](#apidoc.element.color-convert.hsl.ansi256)
- description and source-code
```javascript
hsl.ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.apple"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsl.apple (args)](#apidoc.element.color-convert.hsl.apple)
- description and source-code
```javascript
hsl.apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsl.cmyk (args)](#apidoc.element.color-convert.hsl.cmyk)
- description and source-code
```javascript
hsl.cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.gray"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsl.gray (args)](#apidoc.element.color-convert.hsl.gray)
- description and source-code
```javascript
hsl.gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsl.hcg (args)](#apidoc.element.color-convert.hsl.hcg)
- description and source-code
```javascript
hsl.hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.hex"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsl.hex (args)](#apidoc.element.color-convert.hsl.hex)
- description and source-code
```javascript
hsl.hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsl.hsv (args)](#apidoc.element.color-convert.hsl.hsv)
- description and source-code
```javascript
hsl.hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsl.hwb (args)](#apidoc.element.color-convert.hsl.hwb)
- description and source-code
```javascript
hsl.hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsl.keyword (args)](#apidoc.element.color-convert.hsl.keyword)
- description and source-code
```javascript
hsl.keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.lab"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsl.lab (args)](#apidoc.element.color-convert.hsl.lab)
- description and source-code
```javascript
hsl.lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.lch"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsl.lch (args)](#apidoc.element.color-convert.hsl.lch)
- description and source-code
```javascript
hsl.lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsl.rgb (args)](#apidoc.element.color-convert.hsl.rgb)
- description and source-code
```javascript
hsl.rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsl.xyz (args)](#apidoc.element.color-convert.hsl.xyz)
- description and source-code
```javascript
hsl.xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsv.ansi16 (args)](#apidoc.element.color-convert.hsv.ansi16)
- description and source-code
```javascript
hsv.ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsv.ansi256 (args)](#apidoc.element.color-convert.hsv.ansi256)
- description and source-code
```javascript
hsv.ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.apple"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsv.apple (args)](#apidoc.element.color-convert.hsv.apple)
- description and source-code
```javascript
hsv.apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsv.cmyk (args)](#apidoc.element.color-convert.hsv.cmyk)
- description and source-code
```javascript
hsv.cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.gray"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsv.gray (args)](#apidoc.element.color-convert.hsv.gray)
- description and source-code
```javascript
hsv.gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsv.hcg (args)](#apidoc.element.color-convert.hsv.hcg)
- description and source-code
```javascript
hsv.hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.hex"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsv.hex (args)](#apidoc.element.color-convert.hsv.hex)
- description and source-code
```javascript
hsv.hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsv.hsl (args)](#apidoc.element.color-convert.hsv.hsl)
- description and source-code
```javascript
hsv.hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsv.hwb (args)](#apidoc.element.color-convert.hsv.hwb)
- description and source-code
```javascript
hsv.hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsv.keyword (args)](#apidoc.element.color-convert.hsv.keyword)
- description and source-code
```javascript
hsv.keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.lab"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsv.lab (args)](#apidoc.element.color-convert.hsv.lab)
- description and source-code
```javascript
hsv.lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.lch"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsv.lch (args)](#apidoc.element.color-convert.hsv.lch)
- description and source-code
```javascript
hsv.lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsv.rgb (args)](#apidoc.element.color-convert.hsv.rgb)
- description and source-code
```javascript
hsv.rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.hsv.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hsv.xyz (args)](#apidoc.element.color-convert.hsv.xyz)
- description and source-code
```javascript
hsv.xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hwb.ansi16 (args)](#apidoc.element.color-convert.hwb.ansi16)
- description and source-code
```javascript
hwb.ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hwb.ansi256 (args)](#apidoc.element.color-convert.hwb.ansi256)
- description and source-code
```javascript
hwb.ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.apple"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hwb.apple (args)](#apidoc.element.color-convert.hwb.apple)
- description and source-code
```javascript
hwb.apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hwb.cmyk (args)](#apidoc.element.color-convert.hwb.cmyk)
- description and source-code
```javascript
hwb.cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.gray"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hwb.gray (args)](#apidoc.element.color-convert.hwb.gray)
- description and source-code
```javascript
hwb.gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hwb.hcg (args)](#apidoc.element.color-convert.hwb.hcg)
- description and source-code
```javascript
hwb.hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.hex"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hwb.hex (args)](#apidoc.element.color-convert.hwb.hex)
- description and source-code
```javascript
hwb.hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hwb.hsl (args)](#apidoc.element.color-convert.hwb.hsl)
- description and source-code
```javascript
hwb.hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hwb.hsv (args)](#apidoc.element.color-convert.hwb.hsv)
- description and source-code
```javascript
hwb.hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hwb.keyword (args)](#apidoc.element.color-convert.hwb.keyword)
- description and source-code
```javascript
hwb.keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.lab"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hwb.lab (args)](#apidoc.element.color-convert.hwb.lab)
- description and source-code
```javascript
hwb.lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.lch"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hwb.lch (args)](#apidoc.element.color-convert.hwb.lch)
- description and source-code
```javascript
hwb.lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hwb.rgb (args)](#apidoc.element.color-convert.hwb.rgb)
- description and source-code
```javascript
hwb.rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.</span>hwb.xyz (args)](#apidoc.element.color-convert.hwb.xyz)
- description and source-code
```javascript
hwb.xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.</span>keyword.ansi16 (args)](#apidoc.element.color-convert.keyword.ansi16)
- description and source-code
```javascript
keyword.ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.</span>keyword.ansi256 (args)](#apidoc.element.color-convert.keyword.ansi256)
- description and source-code
```javascript
keyword.ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.apple"></a>[function <span class="apidocSignatureSpan">color-convert.</span>keyword.apple (args)](#apidoc.element.color-convert.keyword.apple)
- description and source-code
```javascript
keyword.apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.</span>keyword.cmyk (args)](#apidoc.element.color-convert.keyword.cmyk)
- description and source-code
```javascript
keyword.cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.gray"></a>[function <span class="apidocSignatureSpan">color-convert.</span>keyword.gray (args)](#apidoc.element.color-convert.keyword.gray)
- description and source-code
```javascript
keyword.gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.</span>keyword.hcg (args)](#apidoc.element.color-convert.keyword.hcg)
- description and source-code
```javascript
keyword.hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.hex"></a>[function <span class="apidocSignatureSpan">color-convert.</span>keyword.hex (args)](#apidoc.element.color-convert.keyword.hex)
- description and source-code
```javascript
keyword.hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.</span>keyword.hsl (args)](#apidoc.element.color-convert.keyword.hsl)
- description and source-code
```javascript
keyword.hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.</span>keyword.hsv (args)](#apidoc.element.color-convert.keyword.hsv)
- description and source-code
```javascript
keyword.hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>keyword.hwb (args)](#apidoc.element.color-convert.keyword.hwb)
- description and source-code
```javascript
keyword.hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.lab"></a>[function <span class="apidocSignatureSpan">color-convert.</span>keyword.lab (args)](#apidoc.element.color-convert.keyword.lab)
- description and source-code
```javascript
keyword.lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.lch"></a>[function <span class="apidocSignatureSpan">color-convert.</span>keyword.lch (args)](#apidoc.element.color-convert.keyword.lch)
- description and source-code
```javascript
keyword.lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>keyword.rgb (args)](#apidoc.element.color-convert.keyword.rgb)
- description and source-code
```javascript
keyword.rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.keyword.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.</span>keyword.xyz (args)](#apidoc.element.color-convert.keyword.xyz)
- description and source-code
```javascript
keyword.xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lab.ansi16 (args)](#apidoc.element.color-convert.lab.ansi16)
- description and source-code
```javascript
lab.ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lab.ansi256 (args)](#apidoc.element.color-convert.lab.ansi256)
- description and source-code
```javascript
lab.ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.apple"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lab.apple (args)](#apidoc.element.color-convert.lab.apple)
- description and source-code
```javascript
lab.apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lab.cmyk (args)](#apidoc.element.color-convert.lab.cmyk)
- description and source-code
```javascript
lab.cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.gray"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lab.gray (args)](#apidoc.element.color-convert.lab.gray)
- description and source-code
```javascript
lab.gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lab.hcg (args)](#apidoc.element.color-convert.lab.hcg)
- description and source-code
```javascript
lab.hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.hex"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lab.hex (args)](#apidoc.element.color-convert.lab.hex)
- description and source-code
```javascript
lab.hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lab.hsl (args)](#apidoc.element.color-convert.lab.hsl)
- description and source-code
```javascript
lab.hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lab.hsv (args)](#apidoc.element.color-convert.lab.hsv)
- description and source-code
```javascript
lab.hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lab.hwb (args)](#apidoc.element.color-convert.lab.hwb)
- description and source-code
```javascript
lab.hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lab.keyword (args)](#apidoc.element.color-convert.lab.keyword)
- description and source-code
```javascript
lab.keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.lch"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lab.lch (args)](#apidoc.element.color-convert.lab.lch)
- description and source-code
```javascript
lab.lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lab.rgb (args)](#apidoc.element.color-convert.lab.rgb)
- description and source-code
```javascript
lab.rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lab.xyz (args)](#apidoc.element.color-convert.lab.xyz)
- description and source-code
```javascript
lab.xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lch.ansi16 (args)](#apidoc.element.color-convert.lch.ansi16)
- description and source-code
```javascript
lch.ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lch.ansi256 (args)](#apidoc.element.color-convert.lch.ansi256)
- description and source-code
```javascript
lch.ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.apple"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lch.apple (args)](#apidoc.element.color-convert.lch.apple)
- description and source-code
```javascript
lch.apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lch.cmyk (args)](#apidoc.element.color-convert.lch.cmyk)
- description and source-code
```javascript
lch.cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.gray"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lch.gray (args)](#apidoc.element.color-convert.lch.gray)
- description and source-code
```javascript
lch.gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lch.hcg (args)](#apidoc.element.color-convert.lch.hcg)
- description and source-code
```javascript
lch.hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.hex"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lch.hex (args)](#apidoc.element.color-convert.lch.hex)
- description and source-code
```javascript
lch.hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lch.hsl (args)](#apidoc.element.color-convert.lch.hsl)
- description and source-code
```javascript
lch.hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lch.hsv (args)](#apidoc.element.color-convert.lch.hsv)
- description and source-code
```javascript
lch.hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lch.hwb (args)](#apidoc.element.color-convert.lch.hwb)
- description and source-code
```javascript
lch.hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lch.keyword (args)](#apidoc.element.color-convert.lch.keyword)
- description and source-code
```javascript
lch.keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.lab"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lch.lab (args)](#apidoc.element.color-convert.lch.lab)
- description and source-code
```javascript
lch.lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lch.rgb (args)](#apidoc.element.color-convert.lch.rgb)
- description and source-code
```javascript
lch.rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.</span>lch.xyz (args)](#apidoc.element.color-convert.lch.xyz)
- description and source-code
```javascript
lch.xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.</span>rgb.ansi16 (args)](#apidoc.element.color-convert.rgb.ansi16)
- description and source-code
```javascript
rgb.ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.rgb.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.</span>rgb.ansi256 (args)](#apidoc.element.color-convert.rgb.ansi256)
- description and source-code
```javascript
rgb.ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.apple"></a>[function <span class="apidocSignatureSpan">color-convert.</span>rgb.apple (args)](#apidoc.element.color-convert.rgb.apple)
- description and source-code
```javascript
rgb.apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.</span>rgb.cmyk (args)](#apidoc.element.color-convert.rgb.cmyk)
- description and source-code
```javascript
rgb.cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.rgb.gray"></a>[function <span class="apidocSignatureSpan">color-convert.</span>rgb.gray (args)](#apidoc.element.color-convert.rgb.gray)
- description and source-code
```javascript
rgb.gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.</span>rgb.hcg (args)](#apidoc.element.color-convert.rgb.hcg)
- description and source-code
```javascript
rgb.hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.hex"></a>[function <span class="apidocSignatureSpan">color-convert.</span>rgb.hex (args)](#apidoc.element.color-convert.rgb.hex)
- description and source-code
```javascript
rgb.hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.rgb.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.</span>rgb.hsl (args)](#apidoc.element.color-convert.rgb.hsl)
- description and source-code
```javascript
rgb.hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.rgb.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.</span>rgb.hsv (args)](#apidoc.element.color-convert.rgb.hsv)
- description and source-code
```javascript
rgb.hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.rgb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>rgb.hwb (args)](#apidoc.element.color-convert.rgb.hwb)
- description and source-code
```javascript
rgb.hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.</span>rgb.keyword (args)](#apidoc.element.color-convert.rgb.keyword)
- description and source-code
```javascript
rgb.keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.lab"></a>[function <span class="apidocSignatureSpan">color-convert.</span>rgb.lab (args)](#apidoc.element.color-convert.rgb.lab)
- description and source-code
```javascript
rgb.lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.lch"></a>[function <span class="apidocSignatureSpan">color-convert.</span>rgb.lch (args)](#apidoc.element.color-convert.rgb.lch)
- description and source-code
```javascript
rgb.lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.</span>rgb.xyz (args)](#apidoc.element.color-convert.rgb.xyz)
- description and source-code
```javascript
rgb.xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```

#### <a name="apidoc.element.color-convert.xyz.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.</span>xyz.ansi16 (args)](#apidoc.element.color-convert.xyz.ansi16)
- description and source-code
```javascript
xyz.ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.</span>xyz.ansi256 (args)](#apidoc.element.color-convert.xyz.ansi256)
- description and source-code
```javascript
xyz.ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.apple"></a>[function <span class="apidocSignatureSpan">color-convert.</span>xyz.apple (args)](#apidoc.element.color-convert.xyz.apple)
- description and source-code
```javascript
xyz.apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.</span>xyz.cmyk (args)](#apidoc.element.color-convert.xyz.cmyk)
- description and source-code
```javascript
xyz.cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.gray"></a>[function <span class="apidocSignatureSpan">color-convert.</span>xyz.gray (args)](#apidoc.element.color-convert.xyz.gray)
- description and source-code
```javascript
xyz.gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.</span>xyz.hcg (args)](#apidoc.element.color-convert.xyz.hcg)
- description and source-code
```javascript
xyz.hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.hex"></a>[function <span class="apidocSignatureSpan">color-convert.</span>xyz.hex (args)](#apidoc.element.color-convert.xyz.hex)
- description and source-code
```javascript
xyz.hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.</span>xyz.hsl (args)](#apidoc.element.color-convert.xyz.hsl)
- description and source-code
```javascript
xyz.hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.</span>xyz.hsv (args)](#apidoc.element.color-convert.xyz.hsv)
- description and source-code
```javascript
xyz.hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>xyz.hwb (args)](#apidoc.element.color-convert.xyz.hwb)
- description and source-code
```javascript
xyz.hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.</span>xyz.keyword (args)](#apidoc.element.color-convert.xyz.keyword)
- description and source-code
```javascript
xyz.keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.lab"></a>[function <span class="apidocSignatureSpan">color-convert.</span>xyz.lab (args)](#apidoc.element.color-convert.xyz.lab)
- description and source-code
```javascript
xyz.lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.lch"></a>[function <span class="apidocSignatureSpan">color-convert.</span>xyz.lch (args)](#apidoc.element.color-convert.xyz.lch)
- description and source-code
```javascript
xyz.lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.</span>xyz.rgb (args)](#apidoc.element.color-convert.xyz.rgb)
- description and source-code
```javascript
xyz.rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.color-convert.ansi16"></a>[module color-convert.ansi16](#apidoc.module.color-convert.ansi16)

#### <a name="apidoc.element.color-convert.ansi16.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>ansi256 (args)](#apidoc.element.color-convert.ansi16.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.apple"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>apple (args)](#apidoc.element.color-convert.ansi16.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>cmyk (args)](#apidoc.element.color-convert.ansi16.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.ansi16.gray"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>gray (args)](#apidoc.element.color-convert.ansi16.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hcg (args)](#apidoc.element.color-convert.ansi16.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.hex"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hex (args)](#apidoc.element.color-convert.ansi16.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.ansi16.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hsl (args)](#apidoc.element.color-convert.ansi16.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.ansi16.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hsv (args)](#apidoc.element.color-convert.ansi16.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.ansi16.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hwb (args)](#apidoc.element.color-convert.ansi16.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>keyword (args)](#apidoc.element.color-convert.ansi16.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.lab"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>lab (args)](#apidoc.element.color-convert.ansi16.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.ansi16.lch"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>lch (args)](#apidoc.element.color-convert.ansi16.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>rgb (args)](#apidoc.element.color-convert.ansi16.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.ansi16.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>xyz (args)](#apidoc.element.color-convert.ansi16.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```



# <a name="apidoc.module.color-convert.ansi16.ansi256"></a>[module color-convert.ansi16.ansi256](#apidoc.module.color-convert.ansi16.ansi256)

#### <a name="apidoc.element.color-convert.ansi16.ansi256.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>ansi256 (args)](#apidoc.element.color-convert.ansi16.ansi256.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.ansi256.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.ansi256.</span>raw (args)](#apidoc.element.color-convert.ansi16.ansi256.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi16.apple"></a>[module color-convert.ansi16.apple](#apidoc.module.color-convert.ansi16.apple)

#### <a name="apidoc.element.color-convert.ansi16.apple.apple"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>apple (args)](#apidoc.element.color-convert.ansi16.apple.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.apple.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.apple.</span>raw (args)](#apidoc.element.color-convert.ansi16.apple.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi16.cmyk"></a>[module color-convert.ansi16.cmyk](#apidoc.module.color-convert.ansi16.cmyk)

#### <a name="apidoc.element.color-convert.ansi16.cmyk.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>cmyk (args)](#apidoc.element.color-convert.ansi16.cmyk.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.ansi16.cmyk.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.cmyk.</span>raw (args)](#apidoc.element.color-convert.ansi16.cmyk.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi16.gray"></a>[module color-convert.ansi16.gray](#apidoc.module.color-convert.ansi16.gray)

#### <a name="apidoc.element.color-convert.ansi16.gray.gray"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>gray (args)](#apidoc.element.color-convert.ansi16.gray.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.gray.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.gray.</span>raw (args)](#apidoc.element.color-convert.ansi16.gray.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi16.hcg"></a>[module color-convert.ansi16.hcg](#apidoc.module.color-convert.ansi16.hcg)

#### <a name="apidoc.element.color-convert.ansi16.hcg.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hcg (args)](#apidoc.element.color-convert.ansi16.hcg.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.hcg.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.hcg.</span>raw (args)](#apidoc.element.color-convert.ansi16.hcg.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi16.hex"></a>[module color-convert.ansi16.hex](#apidoc.module.color-convert.ansi16.hex)

#### <a name="apidoc.element.color-convert.ansi16.hex.hex"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hex (args)](#apidoc.element.color-convert.ansi16.hex.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.ansi16.hex.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.hex.</span>raw (args)](#apidoc.element.color-convert.ansi16.hex.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi16.hsl"></a>[module color-convert.ansi16.hsl](#apidoc.module.color-convert.ansi16.hsl)

#### <a name="apidoc.element.color-convert.ansi16.hsl.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hsl (args)](#apidoc.element.color-convert.ansi16.hsl.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.ansi16.hsl.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.hsl.</span>raw (args)](#apidoc.element.color-convert.ansi16.hsl.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi16.hsv"></a>[module color-convert.ansi16.hsv](#apidoc.module.color-convert.ansi16.hsv)

#### <a name="apidoc.element.color-convert.ansi16.hsv.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hsv (args)](#apidoc.element.color-convert.ansi16.hsv.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.ansi16.hsv.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.hsv.</span>raw (args)](#apidoc.element.color-convert.ansi16.hsv.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi16.hwb"></a>[module color-convert.ansi16.hwb](#apidoc.module.color-convert.ansi16.hwb)

#### <a name="apidoc.element.color-convert.ansi16.hwb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>hwb (args)](#apidoc.element.color-convert.ansi16.hwb.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.hwb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.hwb.</span>raw (args)](#apidoc.element.color-convert.ansi16.hwb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi16.keyword"></a>[module color-convert.ansi16.keyword](#apidoc.module.color-convert.ansi16.keyword)

#### <a name="apidoc.element.color-convert.ansi16.keyword.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>keyword (args)](#apidoc.element.color-convert.ansi16.keyword.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.keyword.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.keyword.</span>raw (args)](#apidoc.element.color-convert.ansi16.keyword.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi16.lab"></a>[module color-convert.ansi16.lab](#apidoc.module.color-convert.ansi16.lab)

#### <a name="apidoc.element.color-convert.ansi16.lab.lab"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>lab (args)](#apidoc.element.color-convert.ansi16.lab.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.ansi16.lab.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.lab.</span>raw (args)](#apidoc.element.color-convert.ansi16.lab.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi16.lch"></a>[module color-convert.ansi16.lch](#apidoc.module.color-convert.ansi16.lch)

#### <a name="apidoc.element.color-convert.ansi16.lch.lch"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>lch (args)](#apidoc.element.color-convert.ansi16.lch.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi16.lch.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.lch.</span>raw (args)](#apidoc.element.color-convert.ansi16.lch.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi16.rgb"></a>[module color-convert.ansi16.rgb](#apidoc.module.color-convert.ansi16.rgb)

#### <a name="apidoc.element.color-convert.ansi16.rgb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>rgb (args)](#apidoc.element.color-convert.ansi16.rgb.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.ansi16.rgb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.rgb.</span>raw (args)](#apidoc.element.color-convert.ansi16.rgb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi16.xyz"></a>[module color-convert.ansi16.xyz](#apidoc.module.color-convert.ansi16.xyz)

#### <a name="apidoc.element.color-convert.ansi16.xyz.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.</span>xyz (args)](#apidoc.element.color-convert.ansi16.xyz.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```

#### <a name="apidoc.element.color-convert.ansi16.xyz.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi16.xyz.</span>raw (args)](#apidoc.element.color-convert.ansi16.xyz.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi256"></a>[module color-convert.ansi256](#apidoc.module.color-convert.ansi256)

#### <a name="apidoc.element.color-convert.ansi256.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>ansi16 (args)](#apidoc.element.color-convert.ansi256.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.ansi256.apple"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>apple (args)](#apidoc.element.color-convert.ansi256.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>cmyk (args)](#apidoc.element.color-convert.ansi256.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.ansi256.gray"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>gray (args)](#apidoc.element.color-convert.ansi256.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hcg (args)](#apidoc.element.color-convert.ansi256.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.hex"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hex (args)](#apidoc.element.color-convert.ansi256.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.ansi256.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hsl (args)](#apidoc.element.color-convert.ansi256.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.ansi256.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hsv (args)](#apidoc.element.color-convert.ansi256.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.ansi256.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hwb (args)](#apidoc.element.color-convert.ansi256.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>keyword (args)](#apidoc.element.color-convert.ansi256.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.lab"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>lab (args)](#apidoc.element.color-convert.ansi256.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.ansi256.lch"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>lch (args)](#apidoc.element.color-convert.ansi256.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>rgb (args)](#apidoc.element.color-convert.ansi256.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.ansi256.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>xyz (args)](#apidoc.element.color-convert.ansi256.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```



# <a name="apidoc.module.color-convert.ansi256.ansi16"></a>[module color-convert.ansi256.ansi16](#apidoc.module.color-convert.ansi256.ansi16)

#### <a name="apidoc.element.color-convert.ansi256.ansi16.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>ansi16 (args)](#apidoc.element.color-convert.ansi256.ansi16.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.ansi256.ansi16.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.ansi16.</span>raw (args)](#apidoc.element.color-convert.ansi256.ansi16.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi256.apple"></a>[module color-convert.ansi256.apple](#apidoc.module.color-convert.ansi256.apple)

#### <a name="apidoc.element.color-convert.ansi256.apple.apple"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>apple (args)](#apidoc.element.color-convert.ansi256.apple.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.apple.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.apple.</span>raw (args)](#apidoc.element.color-convert.ansi256.apple.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi256.cmyk"></a>[module color-convert.ansi256.cmyk](#apidoc.module.color-convert.ansi256.cmyk)

#### <a name="apidoc.element.color-convert.ansi256.cmyk.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>cmyk (args)](#apidoc.element.color-convert.ansi256.cmyk.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.ansi256.cmyk.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.cmyk.</span>raw (args)](#apidoc.element.color-convert.ansi256.cmyk.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi256.gray"></a>[module color-convert.ansi256.gray](#apidoc.module.color-convert.ansi256.gray)

#### <a name="apidoc.element.color-convert.ansi256.gray.gray"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>gray (args)](#apidoc.element.color-convert.ansi256.gray.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.gray.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.gray.</span>raw (args)](#apidoc.element.color-convert.ansi256.gray.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi256.hcg"></a>[module color-convert.ansi256.hcg](#apidoc.module.color-convert.ansi256.hcg)

#### <a name="apidoc.element.color-convert.ansi256.hcg.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hcg (args)](#apidoc.element.color-convert.ansi256.hcg.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.hcg.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.hcg.</span>raw (args)](#apidoc.element.color-convert.ansi256.hcg.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi256.hex"></a>[module color-convert.ansi256.hex](#apidoc.module.color-convert.ansi256.hex)

#### <a name="apidoc.element.color-convert.ansi256.hex.hex"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hex (args)](#apidoc.element.color-convert.ansi256.hex.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.ansi256.hex.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.hex.</span>raw (args)](#apidoc.element.color-convert.ansi256.hex.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi256.hsl"></a>[module color-convert.ansi256.hsl](#apidoc.module.color-convert.ansi256.hsl)

#### <a name="apidoc.element.color-convert.ansi256.hsl.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hsl (args)](#apidoc.element.color-convert.ansi256.hsl.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.ansi256.hsl.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.hsl.</span>raw (args)](#apidoc.element.color-convert.ansi256.hsl.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi256.hsv"></a>[module color-convert.ansi256.hsv](#apidoc.module.color-convert.ansi256.hsv)

#### <a name="apidoc.element.color-convert.ansi256.hsv.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hsv (args)](#apidoc.element.color-convert.ansi256.hsv.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.ansi256.hsv.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.hsv.</span>raw (args)](#apidoc.element.color-convert.ansi256.hsv.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi256.hwb"></a>[module color-convert.ansi256.hwb](#apidoc.module.color-convert.ansi256.hwb)

#### <a name="apidoc.element.color-convert.ansi256.hwb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>hwb (args)](#apidoc.element.color-convert.ansi256.hwb.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.hwb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.hwb.</span>raw (args)](#apidoc.element.color-convert.ansi256.hwb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi256.keyword"></a>[module color-convert.ansi256.keyword](#apidoc.module.color-convert.ansi256.keyword)

#### <a name="apidoc.element.color-convert.ansi256.keyword.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>keyword (args)](#apidoc.element.color-convert.ansi256.keyword.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.keyword.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.keyword.</span>raw (args)](#apidoc.element.color-convert.ansi256.keyword.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi256.lab"></a>[module color-convert.ansi256.lab](#apidoc.module.color-convert.ansi256.lab)

#### <a name="apidoc.element.color-convert.ansi256.lab.lab"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>lab (args)](#apidoc.element.color-convert.ansi256.lab.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.ansi256.lab.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.lab.</span>raw (args)](#apidoc.element.color-convert.ansi256.lab.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi256.lch"></a>[module color-convert.ansi256.lch](#apidoc.module.color-convert.ansi256.lch)

#### <a name="apidoc.element.color-convert.ansi256.lch.lch"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>lch (args)](#apidoc.element.color-convert.ansi256.lch.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.ansi256.lch.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.lch.</span>raw (args)](#apidoc.element.color-convert.ansi256.lch.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi256.rgb"></a>[module color-convert.ansi256.rgb](#apidoc.module.color-convert.ansi256.rgb)

#### <a name="apidoc.element.color-convert.ansi256.rgb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>rgb (args)](#apidoc.element.color-convert.ansi256.rgb.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.ansi256.rgb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.rgb.</span>raw (args)](#apidoc.element.color-convert.ansi256.rgb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.ansi256.xyz"></a>[module color-convert.ansi256.xyz](#apidoc.module.color-convert.ansi256.xyz)

#### <a name="apidoc.element.color-convert.ansi256.xyz.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.</span>xyz (args)](#apidoc.element.color-convert.ansi256.xyz.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```

#### <a name="apidoc.element.color-convert.ansi256.xyz.raw"></a>[function <span class="apidocSignatureSpan">color-convert.ansi256.xyz.</span>raw (args)](#apidoc.element.color-convert.ansi256.xyz.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.apple"></a>[module color-convert.apple](#apidoc.module.color-convert.apple)

#### <a name="apidoc.element.color-convert.apple.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>ansi16 (args)](#apidoc.element.color-convert.apple.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.apple.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>ansi256 (args)](#apidoc.element.color-convert.apple.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>cmyk (args)](#apidoc.element.color-convert.apple.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.apple.gray"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>gray (args)](#apidoc.element.color-convert.apple.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>hcg (args)](#apidoc.element.color-convert.apple.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.hex"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>hex (args)](#apidoc.element.color-convert.apple.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.apple.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>hsl (args)](#apidoc.element.color-convert.apple.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.apple.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>hsv (args)](#apidoc.element.color-convert.apple.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.apple.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>hwb (args)](#apidoc.element.color-convert.apple.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>keyword (args)](#apidoc.element.color-convert.apple.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.lab"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>lab (args)](#apidoc.element.color-convert.apple.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.apple.lch"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>lch (args)](#apidoc.element.color-convert.apple.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>rgb (args)](#apidoc.element.color-convert.apple.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.apple.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>xyz (args)](#apidoc.element.color-convert.apple.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```



# <a name="apidoc.module.color-convert.apple.ansi16"></a>[module color-convert.apple.ansi16](#apidoc.module.color-convert.apple.ansi16)

#### <a name="apidoc.element.color-convert.apple.ansi16.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>ansi16 (args)](#apidoc.element.color-convert.apple.ansi16.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.apple.ansi16.raw"></a>[function <span class="apidocSignatureSpan">color-convert.apple.ansi16.</span>raw (args)](#apidoc.element.color-convert.apple.ansi16.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.apple.ansi256"></a>[module color-convert.apple.ansi256](#apidoc.module.color-convert.apple.ansi256)

#### <a name="apidoc.element.color-convert.apple.ansi256.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>ansi256 (args)](#apidoc.element.color-convert.apple.ansi256.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.ansi256.raw"></a>[function <span class="apidocSignatureSpan">color-convert.apple.ansi256.</span>raw (args)](#apidoc.element.color-convert.apple.ansi256.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.apple.cmyk"></a>[module color-convert.apple.cmyk](#apidoc.module.color-convert.apple.cmyk)

#### <a name="apidoc.element.color-convert.apple.cmyk.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>cmyk (args)](#apidoc.element.color-convert.apple.cmyk.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.apple.cmyk.raw"></a>[function <span class="apidocSignatureSpan">color-convert.apple.cmyk.</span>raw (args)](#apidoc.element.color-convert.apple.cmyk.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.apple.gray"></a>[module color-convert.apple.gray](#apidoc.module.color-convert.apple.gray)

#### <a name="apidoc.element.color-convert.apple.gray.gray"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>gray (args)](#apidoc.element.color-convert.apple.gray.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.gray.raw"></a>[function <span class="apidocSignatureSpan">color-convert.apple.gray.</span>raw (args)](#apidoc.element.color-convert.apple.gray.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.apple.hcg"></a>[module color-convert.apple.hcg](#apidoc.module.color-convert.apple.hcg)

#### <a name="apidoc.element.color-convert.apple.hcg.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>hcg (args)](#apidoc.element.color-convert.apple.hcg.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.hcg.raw"></a>[function <span class="apidocSignatureSpan">color-convert.apple.hcg.</span>raw (args)](#apidoc.element.color-convert.apple.hcg.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.apple.hex"></a>[module color-convert.apple.hex](#apidoc.module.color-convert.apple.hex)

#### <a name="apidoc.element.color-convert.apple.hex.hex"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>hex (args)](#apidoc.element.color-convert.apple.hex.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.apple.hex.raw"></a>[function <span class="apidocSignatureSpan">color-convert.apple.hex.</span>raw (args)](#apidoc.element.color-convert.apple.hex.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.apple.hsl"></a>[module color-convert.apple.hsl](#apidoc.module.color-convert.apple.hsl)

#### <a name="apidoc.element.color-convert.apple.hsl.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>hsl (args)](#apidoc.element.color-convert.apple.hsl.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.apple.hsl.raw"></a>[function <span class="apidocSignatureSpan">color-convert.apple.hsl.</span>raw (args)](#apidoc.element.color-convert.apple.hsl.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.apple.hsv"></a>[module color-convert.apple.hsv](#apidoc.module.color-convert.apple.hsv)

#### <a name="apidoc.element.color-convert.apple.hsv.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>hsv (args)](#apidoc.element.color-convert.apple.hsv.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.apple.hsv.raw"></a>[function <span class="apidocSignatureSpan">color-convert.apple.hsv.</span>raw (args)](#apidoc.element.color-convert.apple.hsv.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.apple.hwb"></a>[module color-convert.apple.hwb](#apidoc.module.color-convert.apple.hwb)

#### <a name="apidoc.element.color-convert.apple.hwb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>hwb (args)](#apidoc.element.color-convert.apple.hwb.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.hwb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.apple.hwb.</span>raw (args)](#apidoc.element.color-convert.apple.hwb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.apple.keyword"></a>[module color-convert.apple.keyword](#apidoc.module.color-convert.apple.keyword)

#### <a name="apidoc.element.color-convert.apple.keyword.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>keyword (args)](#apidoc.element.color-convert.apple.keyword.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.keyword.raw"></a>[function <span class="apidocSignatureSpan">color-convert.apple.keyword.</span>raw (args)](#apidoc.element.color-convert.apple.keyword.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.apple.lab"></a>[module color-convert.apple.lab](#apidoc.module.color-convert.apple.lab)

#### <a name="apidoc.element.color-convert.apple.lab.lab"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>lab (args)](#apidoc.element.color-convert.apple.lab.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.apple.lab.raw"></a>[function <span class="apidocSignatureSpan">color-convert.apple.lab.</span>raw (args)](#apidoc.element.color-convert.apple.lab.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.apple.lch"></a>[module color-convert.apple.lch](#apidoc.module.color-convert.apple.lch)

#### <a name="apidoc.element.color-convert.apple.lch.lch"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>lch (args)](#apidoc.element.color-convert.apple.lch.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.apple.lch.raw"></a>[function <span class="apidocSignatureSpan">color-convert.apple.lch.</span>raw (args)](#apidoc.element.color-convert.apple.lch.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.apple.rgb"></a>[module color-convert.apple.rgb](#apidoc.module.color-convert.apple.rgb)

#### <a name="apidoc.element.color-convert.apple.rgb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>rgb (args)](#apidoc.element.color-convert.apple.rgb.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.apple.rgb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.apple.rgb.</span>raw (args)](#apidoc.element.color-convert.apple.rgb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.apple.xyz"></a>[module color-convert.apple.xyz](#apidoc.module.color-convert.apple.xyz)

#### <a name="apidoc.element.color-convert.apple.xyz.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.apple.</span>xyz (args)](#apidoc.element.color-convert.apple.xyz.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```

#### <a name="apidoc.element.color-convert.apple.xyz.raw"></a>[function <span class="apidocSignatureSpan">color-convert.apple.xyz.</span>raw (args)](#apidoc.element.color-convert.apple.xyz.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.cmyk"></a>[module color-convert.cmyk](#apidoc.module.color-convert.cmyk)

#### <a name="apidoc.element.color-convert.cmyk.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>ansi16 (args)](#apidoc.element.color-convert.cmyk.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.cmyk.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>ansi256 (args)](#apidoc.element.color-convert.cmyk.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.apple"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>apple (args)](#apidoc.element.color-convert.cmyk.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.gray"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>gray (args)](#apidoc.element.color-convert.cmyk.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hcg (args)](#apidoc.element.color-convert.cmyk.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.hex"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hex (args)](#apidoc.element.color-convert.cmyk.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.cmyk.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hsl (args)](#apidoc.element.color-convert.cmyk.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.cmyk.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hsv (args)](#apidoc.element.color-convert.cmyk.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.cmyk.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hwb (args)](#apidoc.element.color-convert.cmyk.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>keyword (args)](#apidoc.element.color-convert.cmyk.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.lab"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>lab (args)](#apidoc.element.color-convert.cmyk.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.cmyk.lch"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>lch (args)](#apidoc.element.color-convert.cmyk.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>rgb (args)](#apidoc.element.color-convert.cmyk.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.cmyk.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>xyz (args)](#apidoc.element.color-convert.cmyk.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```



# <a name="apidoc.module.color-convert.cmyk.ansi16"></a>[module color-convert.cmyk.ansi16](#apidoc.module.color-convert.cmyk.ansi16)

#### <a name="apidoc.element.color-convert.cmyk.ansi16.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>ansi16 (args)](#apidoc.element.color-convert.cmyk.ansi16.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.cmyk.ansi16.raw"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.ansi16.</span>raw (args)](#apidoc.element.color-convert.cmyk.ansi16.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.cmyk.ansi256"></a>[module color-convert.cmyk.ansi256](#apidoc.module.color-convert.cmyk.ansi256)

#### <a name="apidoc.element.color-convert.cmyk.ansi256.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>ansi256 (args)](#apidoc.element.color-convert.cmyk.ansi256.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.ansi256.raw"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.ansi256.</span>raw (args)](#apidoc.element.color-convert.cmyk.ansi256.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.cmyk.apple"></a>[module color-convert.cmyk.apple](#apidoc.module.color-convert.cmyk.apple)

#### <a name="apidoc.element.color-convert.cmyk.apple.apple"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>apple (args)](#apidoc.element.color-convert.cmyk.apple.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.apple.raw"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.apple.</span>raw (args)](#apidoc.element.color-convert.cmyk.apple.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.cmyk.gray"></a>[module color-convert.cmyk.gray](#apidoc.module.color-convert.cmyk.gray)

#### <a name="apidoc.element.color-convert.cmyk.gray.gray"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>gray (args)](#apidoc.element.color-convert.cmyk.gray.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.gray.raw"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.gray.</span>raw (args)](#apidoc.element.color-convert.cmyk.gray.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.cmyk.hcg"></a>[module color-convert.cmyk.hcg](#apidoc.module.color-convert.cmyk.hcg)

#### <a name="apidoc.element.color-convert.cmyk.hcg.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hcg (args)](#apidoc.element.color-convert.cmyk.hcg.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.hcg.raw"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.hcg.</span>raw (args)](#apidoc.element.color-convert.cmyk.hcg.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.cmyk.hex"></a>[module color-convert.cmyk.hex](#apidoc.module.color-convert.cmyk.hex)

#### <a name="apidoc.element.color-convert.cmyk.hex.hex"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hex (args)](#apidoc.element.color-convert.cmyk.hex.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.cmyk.hex.raw"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.hex.</span>raw (args)](#apidoc.element.color-convert.cmyk.hex.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.cmyk.hsl"></a>[module color-convert.cmyk.hsl](#apidoc.module.color-convert.cmyk.hsl)

#### <a name="apidoc.element.color-convert.cmyk.hsl.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hsl (args)](#apidoc.element.color-convert.cmyk.hsl.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.cmyk.hsl.raw"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.hsl.</span>raw (args)](#apidoc.element.color-convert.cmyk.hsl.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.cmyk.hsv"></a>[module color-convert.cmyk.hsv](#apidoc.module.color-convert.cmyk.hsv)

#### <a name="apidoc.element.color-convert.cmyk.hsv.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hsv (args)](#apidoc.element.color-convert.cmyk.hsv.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.cmyk.hsv.raw"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.hsv.</span>raw (args)](#apidoc.element.color-convert.cmyk.hsv.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.cmyk.hwb"></a>[module color-convert.cmyk.hwb](#apidoc.module.color-convert.cmyk.hwb)

#### <a name="apidoc.element.color-convert.cmyk.hwb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>hwb (args)](#apidoc.element.color-convert.cmyk.hwb.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.hwb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.hwb.</span>raw (args)](#apidoc.element.color-convert.cmyk.hwb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.cmyk.keyword"></a>[module color-convert.cmyk.keyword](#apidoc.module.color-convert.cmyk.keyword)

#### <a name="apidoc.element.color-convert.cmyk.keyword.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>keyword (args)](#apidoc.element.color-convert.cmyk.keyword.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.keyword.raw"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.keyword.</span>raw (args)](#apidoc.element.color-convert.cmyk.keyword.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.cmyk.lab"></a>[module color-convert.cmyk.lab](#apidoc.module.color-convert.cmyk.lab)

#### <a name="apidoc.element.color-convert.cmyk.lab.lab"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>lab (args)](#apidoc.element.color-convert.cmyk.lab.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.cmyk.lab.raw"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.lab.</span>raw (args)](#apidoc.element.color-convert.cmyk.lab.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.cmyk.lch"></a>[module color-convert.cmyk.lch](#apidoc.module.color-convert.cmyk.lch)

#### <a name="apidoc.element.color-convert.cmyk.lch.lch"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>lch (args)](#apidoc.element.color-convert.cmyk.lch.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.cmyk.lch.raw"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.lch.</span>raw (args)](#apidoc.element.color-convert.cmyk.lch.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.cmyk.rgb"></a>[module color-convert.cmyk.rgb](#apidoc.module.color-convert.cmyk.rgb)

#### <a name="apidoc.element.color-convert.cmyk.rgb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>rgb (args)](#apidoc.element.color-convert.cmyk.rgb.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.cmyk.rgb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.rgb.</span>raw (args)](#apidoc.element.color-convert.cmyk.rgb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.cmyk.xyz"></a>[module color-convert.cmyk.xyz](#apidoc.module.color-convert.cmyk.xyz)

#### <a name="apidoc.element.color-convert.cmyk.xyz.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.</span>xyz (args)](#apidoc.element.color-convert.cmyk.xyz.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```

#### <a name="apidoc.element.color-convert.cmyk.xyz.raw"></a>[function <span class="apidocSignatureSpan">color-convert.cmyk.xyz.</span>raw (args)](#apidoc.element.color-convert.cmyk.xyz.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.gray"></a>[module color-convert.gray](#apidoc.module.color-convert.gray)

#### <a name="apidoc.element.color-convert.gray.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>ansi16 (args)](#apidoc.element.color-convert.gray.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.gray.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>ansi256 (args)](#apidoc.element.color-convert.gray.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.apple"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>apple (args)](#apidoc.element.color-convert.gray.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>cmyk (args)](#apidoc.element.color-convert.gray.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.gray.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>hcg (args)](#apidoc.element.color-convert.gray.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.hex"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>hex (args)](#apidoc.element.color-convert.gray.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.gray.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>hsl (args)](#apidoc.element.color-convert.gray.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.gray.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>hsv (args)](#apidoc.element.color-convert.gray.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.gray.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>hwb (args)](#apidoc.element.color-convert.gray.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>keyword (args)](#apidoc.element.color-convert.gray.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.lab"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>lab (args)](#apidoc.element.color-convert.gray.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.gray.lch"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>lch (args)](#apidoc.element.color-convert.gray.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>rgb (args)](#apidoc.element.color-convert.gray.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.gray.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>xyz (args)](#apidoc.element.color-convert.gray.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```



# <a name="apidoc.module.color-convert.gray.ansi16"></a>[module color-convert.gray.ansi16](#apidoc.module.color-convert.gray.ansi16)

#### <a name="apidoc.element.color-convert.gray.ansi16.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>ansi16 (args)](#apidoc.element.color-convert.gray.ansi16.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.gray.ansi16.raw"></a>[function <span class="apidocSignatureSpan">color-convert.gray.ansi16.</span>raw (args)](#apidoc.element.color-convert.gray.ansi16.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.gray.ansi256"></a>[module color-convert.gray.ansi256](#apidoc.module.color-convert.gray.ansi256)

#### <a name="apidoc.element.color-convert.gray.ansi256.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>ansi256 (args)](#apidoc.element.color-convert.gray.ansi256.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.ansi256.raw"></a>[function <span class="apidocSignatureSpan">color-convert.gray.ansi256.</span>raw (args)](#apidoc.element.color-convert.gray.ansi256.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.gray.apple"></a>[module color-convert.gray.apple](#apidoc.module.color-convert.gray.apple)

#### <a name="apidoc.element.color-convert.gray.apple.apple"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>apple (args)](#apidoc.element.color-convert.gray.apple.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.apple.raw"></a>[function <span class="apidocSignatureSpan">color-convert.gray.apple.</span>raw (args)](#apidoc.element.color-convert.gray.apple.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.gray.cmyk"></a>[module color-convert.gray.cmyk](#apidoc.module.color-convert.gray.cmyk)

#### <a name="apidoc.element.color-convert.gray.cmyk.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>cmyk (args)](#apidoc.element.color-convert.gray.cmyk.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.gray.cmyk.raw"></a>[function <span class="apidocSignatureSpan">color-convert.gray.cmyk.</span>raw (args)](#apidoc.element.color-convert.gray.cmyk.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.gray.hcg"></a>[module color-convert.gray.hcg](#apidoc.module.color-convert.gray.hcg)

#### <a name="apidoc.element.color-convert.gray.hcg.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>hcg (args)](#apidoc.element.color-convert.gray.hcg.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.hcg.raw"></a>[function <span class="apidocSignatureSpan">color-convert.gray.hcg.</span>raw (args)](#apidoc.element.color-convert.gray.hcg.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.gray.hex"></a>[module color-convert.gray.hex](#apidoc.module.color-convert.gray.hex)

#### <a name="apidoc.element.color-convert.gray.hex.hex"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>hex (args)](#apidoc.element.color-convert.gray.hex.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.gray.hex.raw"></a>[function <span class="apidocSignatureSpan">color-convert.gray.hex.</span>raw (args)](#apidoc.element.color-convert.gray.hex.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.gray.hsl"></a>[module color-convert.gray.hsl](#apidoc.module.color-convert.gray.hsl)

#### <a name="apidoc.element.color-convert.gray.hsl.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>hsl (args)](#apidoc.element.color-convert.gray.hsl.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.gray.hsl.raw"></a>[function <span class="apidocSignatureSpan">color-convert.gray.hsl.</span>raw (args)](#apidoc.element.color-convert.gray.hsl.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.gray.hsv"></a>[module color-convert.gray.hsv](#apidoc.module.color-convert.gray.hsv)

#### <a name="apidoc.element.color-convert.gray.hsv.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>hsv (args)](#apidoc.element.color-convert.gray.hsv.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.gray.hsv.raw"></a>[function <span class="apidocSignatureSpan">color-convert.gray.hsv.</span>raw (args)](#apidoc.element.color-convert.gray.hsv.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.gray.hwb"></a>[module color-convert.gray.hwb](#apidoc.module.color-convert.gray.hwb)

#### <a name="apidoc.element.color-convert.gray.hwb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>hwb (args)](#apidoc.element.color-convert.gray.hwb.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.hwb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.gray.hwb.</span>raw (args)](#apidoc.element.color-convert.gray.hwb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.gray.keyword"></a>[module color-convert.gray.keyword](#apidoc.module.color-convert.gray.keyword)

#### <a name="apidoc.element.color-convert.gray.keyword.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>keyword (args)](#apidoc.element.color-convert.gray.keyword.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.keyword.raw"></a>[function <span class="apidocSignatureSpan">color-convert.gray.keyword.</span>raw (args)](#apidoc.element.color-convert.gray.keyword.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.gray.lab"></a>[module color-convert.gray.lab](#apidoc.module.color-convert.gray.lab)

#### <a name="apidoc.element.color-convert.gray.lab.lab"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>lab (args)](#apidoc.element.color-convert.gray.lab.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.gray.lab.raw"></a>[function <span class="apidocSignatureSpan">color-convert.gray.lab.</span>raw (args)](#apidoc.element.color-convert.gray.lab.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.gray.lch"></a>[module color-convert.gray.lch](#apidoc.module.color-convert.gray.lch)

#### <a name="apidoc.element.color-convert.gray.lch.lch"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>lch (args)](#apidoc.element.color-convert.gray.lch.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.gray.lch.raw"></a>[function <span class="apidocSignatureSpan">color-convert.gray.lch.</span>raw (args)](#apidoc.element.color-convert.gray.lch.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.gray.rgb"></a>[module color-convert.gray.rgb](#apidoc.module.color-convert.gray.rgb)

#### <a name="apidoc.element.color-convert.gray.rgb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>rgb (args)](#apidoc.element.color-convert.gray.rgb.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.gray.rgb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.gray.rgb.</span>raw (args)](#apidoc.element.color-convert.gray.rgb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.gray.xyz"></a>[module color-convert.gray.xyz](#apidoc.module.color-convert.gray.xyz)

#### <a name="apidoc.element.color-convert.gray.xyz.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.gray.</span>xyz (args)](#apidoc.element.color-convert.gray.xyz.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```

#### <a name="apidoc.element.color-convert.gray.xyz.raw"></a>[function <span class="apidocSignatureSpan">color-convert.gray.xyz.</span>raw (args)](#apidoc.element.color-convert.gray.xyz.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hcg"></a>[module color-convert.hcg](#apidoc.module.color-convert.hcg)

#### <a name="apidoc.element.color-convert.hcg.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>ansi16 (args)](#apidoc.element.color-convert.hcg.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.hcg.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>ansi256 (args)](#apidoc.element.color-convert.hcg.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.apple"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>apple (args)](#apidoc.element.color-convert.hcg.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>cmyk (args)](#apidoc.element.color-convert.hcg.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.hcg.gray"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>gray (args)](#apidoc.element.color-convert.hcg.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.hex"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>hex (args)](#apidoc.element.color-convert.hcg.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.hcg.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>hsl (args)](#apidoc.element.color-convert.hcg.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.hcg.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>hsv (args)](#apidoc.element.color-convert.hcg.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.hcg.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>hwb (args)](#apidoc.element.color-convert.hcg.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>keyword (args)](#apidoc.element.color-convert.hcg.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.lab"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>lab (args)](#apidoc.element.color-convert.hcg.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.hcg.lch"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>lch (args)](#apidoc.element.color-convert.hcg.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>rgb (args)](#apidoc.element.color-convert.hcg.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.hcg.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>xyz (args)](#apidoc.element.color-convert.hcg.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```



# <a name="apidoc.module.color-convert.hcg.ansi16"></a>[module color-convert.hcg.ansi16](#apidoc.module.color-convert.hcg.ansi16)

#### <a name="apidoc.element.color-convert.hcg.ansi16.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>ansi16 (args)](#apidoc.element.color-convert.hcg.ansi16.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.hcg.ansi16.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.ansi16.</span>raw (args)](#apidoc.element.color-convert.hcg.ansi16.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hcg.ansi256"></a>[module color-convert.hcg.ansi256](#apidoc.module.color-convert.hcg.ansi256)

#### <a name="apidoc.element.color-convert.hcg.ansi256.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>ansi256 (args)](#apidoc.element.color-convert.hcg.ansi256.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.ansi256.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.ansi256.</span>raw (args)](#apidoc.element.color-convert.hcg.ansi256.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hcg.apple"></a>[module color-convert.hcg.apple](#apidoc.module.color-convert.hcg.apple)

#### <a name="apidoc.element.color-convert.hcg.apple.apple"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>apple (args)](#apidoc.element.color-convert.hcg.apple.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.apple.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.apple.</span>raw (args)](#apidoc.element.color-convert.hcg.apple.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hcg.cmyk"></a>[module color-convert.hcg.cmyk](#apidoc.module.color-convert.hcg.cmyk)

#### <a name="apidoc.element.color-convert.hcg.cmyk.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>cmyk (args)](#apidoc.element.color-convert.hcg.cmyk.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.hcg.cmyk.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.cmyk.</span>raw (args)](#apidoc.element.color-convert.hcg.cmyk.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hcg.gray"></a>[module color-convert.hcg.gray](#apidoc.module.color-convert.hcg.gray)

#### <a name="apidoc.element.color-convert.hcg.gray.gray"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>gray (args)](#apidoc.element.color-convert.hcg.gray.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.gray.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.gray.</span>raw (args)](#apidoc.element.color-convert.hcg.gray.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hcg.hex"></a>[module color-convert.hcg.hex](#apidoc.module.color-convert.hcg.hex)

#### <a name="apidoc.element.color-convert.hcg.hex.hex"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>hex (args)](#apidoc.element.color-convert.hcg.hex.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.hcg.hex.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.hex.</span>raw (args)](#apidoc.element.color-convert.hcg.hex.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hcg.hsl"></a>[module color-convert.hcg.hsl](#apidoc.module.color-convert.hcg.hsl)

#### <a name="apidoc.element.color-convert.hcg.hsl.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>hsl (args)](#apidoc.element.color-convert.hcg.hsl.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.hcg.hsl.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.hsl.</span>raw (args)](#apidoc.element.color-convert.hcg.hsl.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hcg.hsv"></a>[module color-convert.hcg.hsv](#apidoc.module.color-convert.hcg.hsv)

#### <a name="apidoc.element.color-convert.hcg.hsv.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>hsv (args)](#apidoc.element.color-convert.hcg.hsv.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.hcg.hsv.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.hsv.</span>raw (args)](#apidoc.element.color-convert.hcg.hsv.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hcg.hwb"></a>[module color-convert.hcg.hwb](#apidoc.module.color-convert.hcg.hwb)

#### <a name="apidoc.element.color-convert.hcg.hwb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>hwb (args)](#apidoc.element.color-convert.hcg.hwb.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.hwb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.hwb.</span>raw (args)](#apidoc.element.color-convert.hcg.hwb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hcg.keyword"></a>[module color-convert.hcg.keyword](#apidoc.module.color-convert.hcg.keyword)

#### <a name="apidoc.element.color-convert.hcg.keyword.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>keyword (args)](#apidoc.element.color-convert.hcg.keyword.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.keyword.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.keyword.</span>raw (args)](#apidoc.element.color-convert.hcg.keyword.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hcg.lab"></a>[module color-convert.hcg.lab](#apidoc.module.color-convert.hcg.lab)

#### <a name="apidoc.element.color-convert.hcg.lab.lab"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>lab (args)](#apidoc.element.color-convert.hcg.lab.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.hcg.lab.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.lab.</span>raw (args)](#apidoc.element.color-convert.hcg.lab.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hcg.lch"></a>[module color-convert.hcg.lch](#apidoc.module.color-convert.hcg.lch)

#### <a name="apidoc.element.color-convert.hcg.lch.lch"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>lch (args)](#apidoc.element.color-convert.hcg.lch.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hcg.lch.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.lch.</span>raw (args)](#apidoc.element.color-convert.hcg.lch.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hcg.rgb"></a>[module color-convert.hcg.rgb](#apidoc.module.color-convert.hcg.rgb)

#### <a name="apidoc.element.color-convert.hcg.rgb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>rgb (args)](#apidoc.element.color-convert.hcg.rgb.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.hcg.rgb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.rgb.</span>raw (args)](#apidoc.element.color-convert.hcg.rgb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hcg.xyz"></a>[module color-convert.hcg.xyz](#apidoc.module.color-convert.hcg.xyz)

#### <a name="apidoc.element.color-convert.hcg.xyz.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.</span>xyz (args)](#apidoc.element.color-convert.hcg.xyz.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```

#### <a name="apidoc.element.color-convert.hcg.xyz.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hcg.xyz.</span>raw (args)](#apidoc.element.color-convert.hcg.xyz.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hex"></a>[module color-convert.hex](#apidoc.module.color-convert.hex)

#### <a name="apidoc.element.color-convert.hex.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>ansi16 (args)](#apidoc.element.color-convert.hex.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.hex.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>ansi256 (args)](#apidoc.element.color-convert.hex.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.apple"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>apple (args)](#apidoc.element.color-convert.hex.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>cmyk (args)](#apidoc.element.color-convert.hex.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.hex.gray"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>gray (args)](#apidoc.element.color-convert.hex.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>hcg (args)](#apidoc.element.color-convert.hex.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>hsl (args)](#apidoc.element.color-convert.hex.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.hex.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>hsv (args)](#apidoc.element.color-convert.hex.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.hex.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>hwb (args)](#apidoc.element.color-convert.hex.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>keyword (args)](#apidoc.element.color-convert.hex.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.lab"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>lab (args)](#apidoc.element.color-convert.hex.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.hex.lch"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>lch (args)](#apidoc.element.color-convert.hex.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>rgb (args)](#apidoc.element.color-convert.hex.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.hex.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>xyz (args)](#apidoc.element.color-convert.hex.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```



# <a name="apidoc.module.color-convert.hex.ansi16"></a>[module color-convert.hex.ansi16](#apidoc.module.color-convert.hex.ansi16)

#### <a name="apidoc.element.color-convert.hex.ansi16.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>ansi16 (args)](#apidoc.element.color-convert.hex.ansi16.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.hex.ansi16.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hex.ansi16.</span>raw (args)](#apidoc.element.color-convert.hex.ansi16.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hex.ansi256"></a>[module color-convert.hex.ansi256](#apidoc.module.color-convert.hex.ansi256)

#### <a name="apidoc.element.color-convert.hex.ansi256.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>ansi256 (args)](#apidoc.element.color-convert.hex.ansi256.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.ansi256.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hex.ansi256.</span>raw (args)](#apidoc.element.color-convert.hex.ansi256.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hex.apple"></a>[module color-convert.hex.apple](#apidoc.module.color-convert.hex.apple)

#### <a name="apidoc.element.color-convert.hex.apple.apple"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>apple (args)](#apidoc.element.color-convert.hex.apple.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.apple.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hex.apple.</span>raw (args)](#apidoc.element.color-convert.hex.apple.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hex.cmyk"></a>[module color-convert.hex.cmyk](#apidoc.module.color-convert.hex.cmyk)

#### <a name="apidoc.element.color-convert.hex.cmyk.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>cmyk (args)](#apidoc.element.color-convert.hex.cmyk.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.hex.cmyk.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hex.cmyk.</span>raw (args)](#apidoc.element.color-convert.hex.cmyk.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hex.gray"></a>[module color-convert.hex.gray](#apidoc.module.color-convert.hex.gray)

#### <a name="apidoc.element.color-convert.hex.gray.gray"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>gray (args)](#apidoc.element.color-convert.hex.gray.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.gray.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hex.gray.</span>raw (args)](#apidoc.element.color-convert.hex.gray.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hex.hcg"></a>[module color-convert.hex.hcg](#apidoc.module.color-convert.hex.hcg)

#### <a name="apidoc.element.color-convert.hex.hcg.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>hcg (args)](#apidoc.element.color-convert.hex.hcg.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.hcg.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hex.hcg.</span>raw (args)](#apidoc.element.color-convert.hex.hcg.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hex.hsl"></a>[module color-convert.hex.hsl](#apidoc.module.color-convert.hex.hsl)

#### <a name="apidoc.element.color-convert.hex.hsl.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>hsl (args)](#apidoc.element.color-convert.hex.hsl.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.hex.hsl.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hex.hsl.</span>raw (args)](#apidoc.element.color-convert.hex.hsl.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hex.hsv"></a>[module color-convert.hex.hsv](#apidoc.module.color-convert.hex.hsv)

#### <a name="apidoc.element.color-convert.hex.hsv.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>hsv (args)](#apidoc.element.color-convert.hex.hsv.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.hex.hsv.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hex.hsv.</span>raw (args)](#apidoc.element.color-convert.hex.hsv.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hex.hwb"></a>[module color-convert.hex.hwb](#apidoc.module.color-convert.hex.hwb)

#### <a name="apidoc.element.color-convert.hex.hwb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>hwb (args)](#apidoc.element.color-convert.hex.hwb.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.hwb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hex.hwb.</span>raw (args)](#apidoc.element.color-convert.hex.hwb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hex.keyword"></a>[module color-convert.hex.keyword](#apidoc.module.color-convert.hex.keyword)

#### <a name="apidoc.element.color-convert.hex.keyword.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>keyword (args)](#apidoc.element.color-convert.hex.keyword.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.keyword.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hex.keyword.</span>raw (args)](#apidoc.element.color-convert.hex.keyword.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hex.lab"></a>[module color-convert.hex.lab](#apidoc.module.color-convert.hex.lab)

#### <a name="apidoc.element.color-convert.hex.lab.lab"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>lab (args)](#apidoc.element.color-convert.hex.lab.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.hex.lab.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hex.lab.</span>raw (args)](#apidoc.element.color-convert.hex.lab.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hex.lch"></a>[module color-convert.hex.lch](#apidoc.module.color-convert.hex.lch)

#### <a name="apidoc.element.color-convert.hex.lch.lch"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>lch (args)](#apidoc.element.color-convert.hex.lch.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hex.lch.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hex.lch.</span>raw (args)](#apidoc.element.color-convert.hex.lch.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hex.rgb"></a>[module color-convert.hex.rgb](#apidoc.module.color-convert.hex.rgb)

#### <a name="apidoc.element.color-convert.hex.rgb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>rgb (args)](#apidoc.element.color-convert.hex.rgb.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.hex.rgb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hex.rgb.</span>raw (args)](#apidoc.element.color-convert.hex.rgb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hex.xyz"></a>[module color-convert.hex.xyz](#apidoc.module.color-convert.hex.xyz)

#### <a name="apidoc.element.color-convert.hex.xyz.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.hex.</span>xyz (args)](#apidoc.element.color-convert.hex.xyz.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```

#### <a name="apidoc.element.color-convert.hex.xyz.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hex.xyz.</span>raw (args)](#apidoc.element.color-convert.hex.xyz.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsl"></a>[module color-convert.hsl](#apidoc.module.color-convert.hsl)

#### <a name="apidoc.element.color-convert.hsl.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>ansi16 (args)](#apidoc.element.color-convert.hsl.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.hsl.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>ansi256 (args)](#apidoc.element.color-convert.hsl.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.apple"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>apple (args)](#apidoc.element.color-convert.hsl.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>cmyk (args)](#apidoc.element.color-convert.hsl.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.hsl.gray"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>gray (args)](#apidoc.element.color-convert.hsl.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>hcg (args)](#apidoc.element.color-convert.hsl.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.hex"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>hex (args)](#apidoc.element.color-convert.hsl.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.hsl.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>hsv (args)](#apidoc.element.color-convert.hsl.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.hsl.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>hwb (args)](#apidoc.element.color-convert.hsl.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>keyword (args)](#apidoc.element.color-convert.hsl.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.lab"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>lab (args)](#apidoc.element.color-convert.hsl.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.hsl.lch"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>lch (args)](#apidoc.element.color-convert.hsl.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>rgb (args)](#apidoc.element.color-convert.hsl.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.hsl.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>xyz (args)](#apidoc.element.color-convert.hsl.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```



# <a name="apidoc.module.color-convert.hsl.ansi16"></a>[module color-convert.hsl.ansi16](#apidoc.module.color-convert.hsl.ansi16)

#### <a name="apidoc.element.color-convert.hsl.ansi16.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>ansi16 (args)](#apidoc.element.color-convert.hsl.ansi16.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.hsl.ansi16.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.ansi16.</span>raw (args)](#apidoc.element.color-convert.hsl.ansi16.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsl.ansi256"></a>[module color-convert.hsl.ansi256](#apidoc.module.color-convert.hsl.ansi256)

#### <a name="apidoc.element.color-convert.hsl.ansi256.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>ansi256 (args)](#apidoc.element.color-convert.hsl.ansi256.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.ansi256.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.ansi256.</span>raw (args)](#apidoc.element.color-convert.hsl.ansi256.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsl.apple"></a>[module color-convert.hsl.apple](#apidoc.module.color-convert.hsl.apple)

#### <a name="apidoc.element.color-convert.hsl.apple.apple"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>apple (args)](#apidoc.element.color-convert.hsl.apple.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.apple.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.apple.</span>raw (args)](#apidoc.element.color-convert.hsl.apple.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsl.cmyk"></a>[module color-convert.hsl.cmyk](#apidoc.module.color-convert.hsl.cmyk)

#### <a name="apidoc.element.color-convert.hsl.cmyk.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>cmyk (args)](#apidoc.element.color-convert.hsl.cmyk.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.hsl.cmyk.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.cmyk.</span>raw (args)](#apidoc.element.color-convert.hsl.cmyk.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsl.gray"></a>[module color-convert.hsl.gray](#apidoc.module.color-convert.hsl.gray)

#### <a name="apidoc.element.color-convert.hsl.gray.gray"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>gray (args)](#apidoc.element.color-convert.hsl.gray.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.gray.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.gray.</span>raw (args)](#apidoc.element.color-convert.hsl.gray.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsl.hcg"></a>[module color-convert.hsl.hcg](#apidoc.module.color-convert.hsl.hcg)

#### <a name="apidoc.element.color-convert.hsl.hcg.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>hcg (args)](#apidoc.element.color-convert.hsl.hcg.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.hcg.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.hcg.</span>raw (args)](#apidoc.element.color-convert.hsl.hcg.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsl.hex"></a>[module color-convert.hsl.hex](#apidoc.module.color-convert.hsl.hex)

#### <a name="apidoc.element.color-convert.hsl.hex.hex"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>hex (args)](#apidoc.element.color-convert.hsl.hex.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.hsl.hex.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.hex.</span>raw (args)](#apidoc.element.color-convert.hsl.hex.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsl.hsv"></a>[module color-convert.hsl.hsv](#apidoc.module.color-convert.hsl.hsv)

#### <a name="apidoc.element.color-convert.hsl.hsv.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>hsv (args)](#apidoc.element.color-convert.hsl.hsv.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.hsl.hsv.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.hsv.</span>raw (args)](#apidoc.element.color-convert.hsl.hsv.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsl.hwb"></a>[module color-convert.hsl.hwb](#apidoc.module.color-convert.hsl.hwb)

#### <a name="apidoc.element.color-convert.hsl.hwb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>hwb (args)](#apidoc.element.color-convert.hsl.hwb.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.hwb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.hwb.</span>raw (args)](#apidoc.element.color-convert.hsl.hwb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsl.keyword"></a>[module color-convert.hsl.keyword](#apidoc.module.color-convert.hsl.keyword)

#### <a name="apidoc.element.color-convert.hsl.keyword.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>keyword (args)](#apidoc.element.color-convert.hsl.keyword.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.keyword.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.keyword.</span>raw (args)](#apidoc.element.color-convert.hsl.keyword.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsl.lab"></a>[module color-convert.hsl.lab](#apidoc.module.color-convert.hsl.lab)

#### <a name="apidoc.element.color-convert.hsl.lab.lab"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>lab (args)](#apidoc.element.color-convert.hsl.lab.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.hsl.lab.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.lab.</span>raw (args)](#apidoc.element.color-convert.hsl.lab.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsl.lch"></a>[module color-convert.hsl.lch](#apidoc.module.color-convert.hsl.lch)

#### <a name="apidoc.element.color-convert.hsl.lch.lch"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>lch (args)](#apidoc.element.color-convert.hsl.lch.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsl.lch.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.lch.</span>raw (args)](#apidoc.element.color-convert.hsl.lch.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsl.rgb"></a>[module color-convert.hsl.rgb](#apidoc.module.color-convert.hsl.rgb)

#### <a name="apidoc.element.color-convert.hsl.rgb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>rgb (args)](#apidoc.element.color-convert.hsl.rgb.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.hsl.rgb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.rgb.</span>raw (args)](#apidoc.element.color-convert.hsl.rgb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsl.xyz"></a>[module color-convert.hsl.xyz](#apidoc.module.color-convert.hsl.xyz)

#### <a name="apidoc.element.color-convert.hsl.xyz.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.</span>xyz (args)](#apidoc.element.color-convert.hsl.xyz.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```

#### <a name="apidoc.element.color-convert.hsl.xyz.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsl.xyz.</span>raw (args)](#apidoc.element.color-convert.hsl.xyz.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsv"></a>[module color-convert.hsv](#apidoc.module.color-convert.hsv)

#### <a name="apidoc.element.color-convert.hsv.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>ansi16 (args)](#apidoc.element.color-convert.hsv.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.hsv.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>ansi256 (args)](#apidoc.element.color-convert.hsv.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.apple"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>apple (args)](#apidoc.element.color-convert.hsv.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>cmyk (args)](#apidoc.element.color-convert.hsv.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.hsv.gray"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>gray (args)](#apidoc.element.color-convert.hsv.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>hcg (args)](#apidoc.element.color-convert.hsv.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.hex"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>hex (args)](#apidoc.element.color-convert.hsv.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.hsv.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>hsl (args)](#apidoc.element.color-convert.hsv.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.hsv.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>hwb (args)](#apidoc.element.color-convert.hsv.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>keyword (args)](#apidoc.element.color-convert.hsv.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.lab"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>lab (args)](#apidoc.element.color-convert.hsv.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.hsv.lch"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>lch (args)](#apidoc.element.color-convert.hsv.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>rgb (args)](#apidoc.element.color-convert.hsv.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.hsv.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>xyz (args)](#apidoc.element.color-convert.hsv.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```



# <a name="apidoc.module.color-convert.hsv.ansi16"></a>[module color-convert.hsv.ansi16](#apidoc.module.color-convert.hsv.ansi16)

#### <a name="apidoc.element.color-convert.hsv.ansi16.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>ansi16 (args)](#apidoc.element.color-convert.hsv.ansi16.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.hsv.ansi16.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.ansi16.</span>raw (args)](#apidoc.element.color-convert.hsv.ansi16.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsv.ansi256"></a>[module color-convert.hsv.ansi256](#apidoc.module.color-convert.hsv.ansi256)

#### <a name="apidoc.element.color-convert.hsv.ansi256.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>ansi256 (args)](#apidoc.element.color-convert.hsv.ansi256.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.ansi256.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.ansi256.</span>raw (args)](#apidoc.element.color-convert.hsv.ansi256.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsv.apple"></a>[module color-convert.hsv.apple](#apidoc.module.color-convert.hsv.apple)

#### <a name="apidoc.element.color-convert.hsv.apple.apple"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>apple (args)](#apidoc.element.color-convert.hsv.apple.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.apple.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.apple.</span>raw (args)](#apidoc.element.color-convert.hsv.apple.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsv.cmyk"></a>[module color-convert.hsv.cmyk](#apidoc.module.color-convert.hsv.cmyk)

#### <a name="apidoc.element.color-convert.hsv.cmyk.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>cmyk (args)](#apidoc.element.color-convert.hsv.cmyk.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.hsv.cmyk.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.cmyk.</span>raw (args)](#apidoc.element.color-convert.hsv.cmyk.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsv.gray"></a>[module color-convert.hsv.gray](#apidoc.module.color-convert.hsv.gray)

#### <a name="apidoc.element.color-convert.hsv.gray.gray"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>gray (args)](#apidoc.element.color-convert.hsv.gray.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.gray.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.gray.</span>raw (args)](#apidoc.element.color-convert.hsv.gray.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsv.hcg"></a>[module color-convert.hsv.hcg](#apidoc.module.color-convert.hsv.hcg)

#### <a name="apidoc.element.color-convert.hsv.hcg.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>hcg (args)](#apidoc.element.color-convert.hsv.hcg.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.hcg.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.hcg.</span>raw (args)](#apidoc.element.color-convert.hsv.hcg.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsv.hex"></a>[module color-convert.hsv.hex](#apidoc.module.color-convert.hsv.hex)

#### <a name="apidoc.element.color-convert.hsv.hex.hex"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>hex (args)](#apidoc.element.color-convert.hsv.hex.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.hsv.hex.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.hex.</span>raw (args)](#apidoc.element.color-convert.hsv.hex.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsv.hsl"></a>[module color-convert.hsv.hsl](#apidoc.module.color-convert.hsv.hsl)

#### <a name="apidoc.element.color-convert.hsv.hsl.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>hsl (args)](#apidoc.element.color-convert.hsv.hsl.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.hsv.hsl.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.hsl.</span>raw (args)](#apidoc.element.color-convert.hsv.hsl.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsv.hwb"></a>[module color-convert.hsv.hwb](#apidoc.module.color-convert.hsv.hwb)

#### <a name="apidoc.element.color-convert.hsv.hwb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>hwb (args)](#apidoc.element.color-convert.hsv.hwb.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.hwb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.hwb.</span>raw (args)](#apidoc.element.color-convert.hsv.hwb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsv.keyword"></a>[module color-convert.hsv.keyword](#apidoc.module.color-convert.hsv.keyword)

#### <a name="apidoc.element.color-convert.hsv.keyword.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>keyword (args)](#apidoc.element.color-convert.hsv.keyword.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.keyword.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.keyword.</span>raw (args)](#apidoc.element.color-convert.hsv.keyword.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsv.lab"></a>[module color-convert.hsv.lab](#apidoc.module.color-convert.hsv.lab)

#### <a name="apidoc.element.color-convert.hsv.lab.lab"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>lab (args)](#apidoc.element.color-convert.hsv.lab.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.hsv.lab.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.lab.</span>raw (args)](#apidoc.element.color-convert.hsv.lab.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsv.lch"></a>[module color-convert.hsv.lch](#apidoc.module.color-convert.hsv.lch)

#### <a name="apidoc.element.color-convert.hsv.lch.lch"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>lch (args)](#apidoc.element.color-convert.hsv.lch.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hsv.lch.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.lch.</span>raw (args)](#apidoc.element.color-convert.hsv.lch.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsv.rgb"></a>[module color-convert.hsv.rgb](#apidoc.module.color-convert.hsv.rgb)

#### <a name="apidoc.element.color-convert.hsv.rgb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>rgb (args)](#apidoc.element.color-convert.hsv.rgb.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.hsv.rgb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.rgb.</span>raw (args)](#apidoc.element.color-convert.hsv.rgb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hsv.xyz"></a>[module color-convert.hsv.xyz](#apidoc.module.color-convert.hsv.xyz)

#### <a name="apidoc.element.color-convert.hsv.xyz.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.</span>xyz (args)](#apidoc.element.color-convert.hsv.xyz.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```

#### <a name="apidoc.element.color-convert.hsv.xyz.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hsv.xyz.</span>raw (args)](#apidoc.element.color-convert.hsv.xyz.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hwb"></a>[module color-convert.hwb](#apidoc.module.color-convert.hwb)

#### <a name="apidoc.element.color-convert.hwb.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>ansi16 (args)](#apidoc.element.color-convert.hwb.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.hwb.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>ansi256 (args)](#apidoc.element.color-convert.hwb.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.apple"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>apple (args)](#apidoc.element.color-convert.hwb.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>cmyk (args)](#apidoc.element.color-convert.hwb.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.hwb.gray"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>gray (args)](#apidoc.element.color-convert.hwb.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>hcg (args)](#apidoc.element.color-convert.hwb.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.hex"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>hex (args)](#apidoc.element.color-convert.hwb.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.hwb.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>hsl (args)](#apidoc.element.color-convert.hwb.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.hwb.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>hsv (args)](#apidoc.element.color-convert.hwb.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.hwb.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>keyword (args)](#apidoc.element.color-convert.hwb.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.lab"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>lab (args)](#apidoc.element.color-convert.hwb.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.hwb.lch"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>lch (args)](#apidoc.element.color-convert.hwb.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>rgb (args)](#apidoc.element.color-convert.hwb.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.hwb.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>xyz (args)](#apidoc.element.color-convert.hwb.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```



# <a name="apidoc.module.color-convert.hwb.ansi16"></a>[module color-convert.hwb.ansi16](#apidoc.module.color-convert.hwb.ansi16)

#### <a name="apidoc.element.color-convert.hwb.ansi16.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>ansi16 (args)](#apidoc.element.color-convert.hwb.ansi16.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.hwb.ansi16.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.ansi16.</span>raw (args)](#apidoc.element.color-convert.hwb.ansi16.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hwb.ansi256"></a>[module color-convert.hwb.ansi256](#apidoc.module.color-convert.hwb.ansi256)

#### <a name="apidoc.element.color-convert.hwb.ansi256.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>ansi256 (args)](#apidoc.element.color-convert.hwb.ansi256.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.ansi256.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.ansi256.</span>raw (args)](#apidoc.element.color-convert.hwb.ansi256.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hwb.apple"></a>[module color-convert.hwb.apple](#apidoc.module.color-convert.hwb.apple)

#### <a name="apidoc.element.color-convert.hwb.apple.apple"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>apple (args)](#apidoc.element.color-convert.hwb.apple.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.apple.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.apple.</span>raw (args)](#apidoc.element.color-convert.hwb.apple.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hwb.cmyk"></a>[module color-convert.hwb.cmyk](#apidoc.module.color-convert.hwb.cmyk)

#### <a name="apidoc.element.color-convert.hwb.cmyk.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>cmyk (args)](#apidoc.element.color-convert.hwb.cmyk.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.hwb.cmyk.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.cmyk.</span>raw (args)](#apidoc.element.color-convert.hwb.cmyk.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hwb.gray"></a>[module color-convert.hwb.gray](#apidoc.module.color-convert.hwb.gray)

#### <a name="apidoc.element.color-convert.hwb.gray.gray"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>gray (args)](#apidoc.element.color-convert.hwb.gray.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.gray.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.gray.</span>raw (args)](#apidoc.element.color-convert.hwb.gray.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hwb.hcg"></a>[module color-convert.hwb.hcg](#apidoc.module.color-convert.hwb.hcg)

#### <a name="apidoc.element.color-convert.hwb.hcg.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>hcg (args)](#apidoc.element.color-convert.hwb.hcg.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.hcg.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.hcg.</span>raw (args)](#apidoc.element.color-convert.hwb.hcg.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hwb.hex"></a>[module color-convert.hwb.hex](#apidoc.module.color-convert.hwb.hex)

#### <a name="apidoc.element.color-convert.hwb.hex.hex"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>hex (args)](#apidoc.element.color-convert.hwb.hex.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.hwb.hex.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.hex.</span>raw (args)](#apidoc.element.color-convert.hwb.hex.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hwb.hsl"></a>[module color-convert.hwb.hsl](#apidoc.module.color-convert.hwb.hsl)

#### <a name="apidoc.element.color-convert.hwb.hsl.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>hsl (args)](#apidoc.element.color-convert.hwb.hsl.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.hwb.hsl.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.hsl.</span>raw (args)](#apidoc.element.color-convert.hwb.hsl.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hwb.hsv"></a>[module color-convert.hwb.hsv](#apidoc.module.color-convert.hwb.hsv)

#### <a name="apidoc.element.color-convert.hwb.hsv.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>hsv (args)](#apidoc.element.color-convert.hwb.hsv.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.hwb.hsv.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.hsv.</span>raw (args)](#apidoc.element.color-convert.hwb.hsv.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hwb.keyword"></a>[module color-convert.hwb.keyword](#apidoc.module.color-convert.hwb.keyword)

#### <a name="apidoc.element.color-convert.hwb.keyword.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>keyword (args)](#apidoc.element.color-convert.hwb.keyword.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.keyword.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.keyword.</span>raw (args)](#apidoc.element.color-convert.hwb.keyword.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hwb.lab"></a>[module color-convert.hwb.lab](#apidoc.module.color-convert.hwb.lab)

#### <a name="apidoc.element.color-convert.hwb.lab.lab"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>lab (args)](#apidoc.element.color-convert.hwb.lab.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.hwb.lab.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.lab.</span>raw (args)](#apidoc.element.color-convert.hwb.lab.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hwb.lch"></a>[module color-convert.hwb.lch](#apidoc.module.color-convert.hwb.lch)

#### <a name="apidoc.element.color-convert.hwb.lch.lch"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>lch (args)](#apidoc.element.color-convert.hwb.lch.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.hwb.lch.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.lch.</span>raw (args)](#apidoc.element.color-convert.hwb.lch.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hwb.rgb"></a>[module color-convert.hwb.rgb](#apidoc.module.color-convert.hwb.rgb)

#### <a name="apidoc.element.color-convert.hwb.rgb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>rgb (args)](#apidoc.element.color-convert.hwb.rgb.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.hwb.rgb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.rgb.</span>raw (args)](#apidoc.element.color-convert.hwb.rgb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.hwb.xyz"></a>[module color-convert.hwb.xyz](#apidoc.module.color-convert.hwb.xyz)

#### <a name="apidoc.element.color-convert.hwb.xyz.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.</span>xyz (args)](#apidoc.element.color-convert.hwb.xyz.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```

#### <a name="apidoc.element.color-convert.hwb.xyz.raw"></a>[function <span class="apidocSignatureSpan">color-convert.hwb.xyz.</span>raw (args)](#apidoc.element.color-convert.hwb.xyz.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.keyword"></a>[module color-convert.keyword](#apidoc.module.color-convert.keyword)

#### <a name="apidoc.element.color-convert.keyword.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>ansi16 (args)](#apidoc.element.color-convert.keyword.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.keyword.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>ansi256 (args)](#apidoc.element.color-convert.keyword.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.apple"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>apple (args)](#apidoc.element.color-convert.keyword.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>cmyk (args)](#apidoc.element.color-convert.keyword.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.keyword.gray"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>gray (args)](#apidoc.element.color-convert.keyword.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>hcg (args)](#apidoc.element.color-convert.keyword.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.hex"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>hex (args)](#apidoc.element.color-convert.keyword.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.keyword.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>hsl (args)](#apidoc.element.color-convert.keyword.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.keyword.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>hsv (args)](#apidoc.element.color-convert.keyword.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.keyword.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>hwb (args)](#apidoc.element.color-convert.keyword.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.lab"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>lab (args)](#apidoc.element.color-convert.keyword.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.keyword.lch"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>lch (args)](#apidoc.element.color-convert.keyword.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>rgb (args)](#apidoc.element.color-convert.keyword.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.keyword.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>xyz (args)](#apidoc.element.color-convert.keyword.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```



# <a name="apidoc.module.color-convert.keyword.ansi16"></a>[module color-convert.keyword.ansi16](#apidoc.module.color-convert.keyword.ansi16)

#### <a name="apidoc.element.color-convert.keyword.ansi16.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>ansi16 (args)](#apidoc.element.color-convert.keyword.ansi16.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.keyword.ansi16.raw"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.ansi16.</span>raw (args)](#apidoc.element.color-convert.keyword.ansi16.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.keyword.ansi256"></a>[module color-convert.keyword.ansi256](#apidoc.module.color-convert.keyword.ansi256)

#### <a name="apidoc.element.color-convert.keyword.ansi256.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>ansi256 (args)](#apidoc.element.color-convert.keyword.ansi256.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.ansi256.raw"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.ansi256.</span>raw (args)](#apidoc.element.color-convert.keyword.ansi256.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.keyword.apple"></a>[module color-convert.keyword.apple](#apidoc.module.color-convert.keyword.apple)

#### <a name="apidoc.element.color-convert.keyword.apple.apple"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>apple (args)](#apidoc.element.color-convert.keyword.apple.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.apple.raw"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.apple.</span>raw (args)](#apidoc.element.color-convert.keyword.apple.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.keyword.cmyk"></a>[module color-convert.keyword.cmyk](#apidoc.module.color-convert.keyword.cmyk)

#### <a name="apidoc.element.color-convert.keyword.cmyk.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>cmyk (args)](#apidoc.element.color-convert.keyword.cmyk.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.keyword.cmyk.raw"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.cmyk.</span>raw (args)](#apidoc.element.color-convert.keyword.cmyk.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.keyword.gray"></a>[module color-convert.keyword.gray](#apidoc.module.color-convert.keyword.gray)

#### <a name="apidoc.element.color-convert.keyword.gray.gray"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>gray (args)](#apidoc.element.color-convert.keyword.gray.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.gray.raw"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.gray.</span>raw (args)](#apidoc.element.color-convert.keyword.gray.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.keyword.hcg"></a>[module color-convert.keyword.hcg](#apidoc.module.color-convert.keyword.hcg)

#### <a name="apidoc.element.color-convert.keyword.hcg.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>hcg (args)](#apidoc.element.color-convert.keyword.hcg.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.hcg.raw"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.hcg.</span>raw (args)](#apidoc.element.color-convert.keyword.hcg.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.keyword.hex"></a>[module color-convert.keyword.hex](#apidoc.module.color-convert.keyword.hex)

#### <a name="apidoc.element.color-convert.keyword.hex.hex"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>hex (args)](#apidoc.element.color-convert.keyword.hex.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.keyword.hex.raw"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.hex.</span>raw (args)](#apidoc.element.color-convert.keyword.hex.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.keyword.hsl"></a>[module color-convert.keyword.hsl](#apidoc.module.color-convert.keyword.hsl)

#### <a name="apidoc.element.color-convert.keyword.hsl.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>hsl (args)](#apidoc.element.color-convert.keyword.hsl.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.keyword.hsl.raw"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.hsl.</span>raw (args)](#apidoc.element.color-convert.keyword.hsl.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.keyword.hsv"></a>[module color-convert.keyword.hsv](#apidoc.module.color-convert.keyword.hsv)

#### <a name="apidoc.element.color-convert.keyword.hsv.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>hsv (args)](#apidoc.element.color-convert.keyword.hsv.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.keyword.hsv.raw"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.hsv.</span>raw (args)](#apidoc.element.color-convert.keyword.hsv.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.keyword.hwb"></a>[module color-convert.keyword.hwb](#apidoc.module.color-convert.keyword.hwb)

#### <a name="apidoc.element.color-convert.keyword.hwb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>hwb (args)](#apidoc.element.color-convert.keyword.hwb.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.hwb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.hwb.</span>raw (args)](#apidoc.element.color-convert.keyword.hwb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.keyword.lab"></a>[module color-convert.keyword.lab](#apidoc.module.color-convert.keyword.lab)

#### <a name="apidoc.element.color-convert.keyword.lab.lab"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>lab (args)](#apidoc.element.color-convert.keyword.lab.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.keyword.lab.raw"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.lab.</span>raw (args)](#apidoc.element.color-convert.keyword.lab.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.keyword.lch"></a>[module color-convert.keyword.lch](#apidoc.module.color-convert.keyword.lch)

#### <a name="apidoc.element.color-convert.keyword.lch.lch"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>lch (args)](#apidoc.element.color-convert.keyword.lch.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.keyword.lch.raw"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.lch.</span>raw (args)](#apidoc.element.color-convert.keyword.lch.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.keyword.rgb"></a>[module color-convert.keyword.rgb](#apidoc.module.color-convert.keyword.rgb)

#### <a name="apidoc.element.color-convert.keyword.rgb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>rgb (args)](#apidoc.element.color-convert.keyword.rgb.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.keyword.rgb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.rgb.</span>raw (args)](#apidoc.element.color-convert.keyword.rgb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.keyword.xyz"></a>[module color-convert.keyword.xyz](#apidoc.module.color-convert.keyword.xyz)

#### <a name="apidoc.element.color-convert.keyword.xyz.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.</span>xyz (args)](#apidoc.element.color-convert.keyword.xyz.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```

#### <a name="apidoc.element.color-convert.keyword.xyz.raw"></a>[function <span class="apidocSignatureSpan">color-convert.keyword.xyz.</span>raw (args)](#apidoc.element.color-convert.keyword.xyz.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lab"></a>[module color-convert.lab](#apidoc.module.color-convert.lab)

#### <a name="apidoc.element.color-convert.lab.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>ansi16 (args)](#apidoc.element.color-convert.lab.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.lab.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>ansi256 (args)](#apidoc.element.color-convert.lab.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.apple"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>apple (args)](#apidoc.element.color-convert.lab.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>cmyk (args)](#apidoc.element.color-convert.lab.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.lab.gray"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>gray (args)](#apidoc.element.color-convert.lab.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>hcg (args)](#apidoc.element.color-convert.lab.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.hex"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>hex (args)](#apidoc.element.color-convert.lab.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.lab.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>hsl (args)](#apidoc.element.color-convert.lab.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.lab.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>hsv (args)](#apidoc.element.color-convert.lab.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.lab.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>hwb (args)](#apidoc.element.color-convert.lab.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>keyword (args)](#apidoc.element.color-convert.lab.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.lch"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>lch (args)](#apidoc.element.color-convert.lab.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>rgb (args)](#apidoc.element.color-convert.lab.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.lab.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>xyz (args)](#apidoc.element.color-convert.lab.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```



# <a name="apidoc.module.color-convert.lab.ansi16"></a>[module color-convert.lab.ansi16](#apidoc.module.color-convert.lab.ansi16)

#### <a name="apidoc.element.color-convert.lab.ansi16.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>ansi16 (args)](#apidoc.element.color-convert.lab.ansi16.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.lab.ansi16.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lab.ansi16.</span>raw (args)](#apidoc.element.color-convert.lab.ansi16.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lab.ansi256"></a>[module color-convert.lab.ansi256](#apidoc.module.color-convert.lab.ansi256)

#### <a name="apidoc.element.color-convert.lab.ansi256.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>ansi256 (args)](#apidoc.element.color-convert.lab.ansi256.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.ansi256.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lab.ansi256.</span>raw (args)](#apidoc.element.color-convert.lab.ansi256.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lab.apple"></a>[module color-convert.lab.apple](#apidoc.module.color-convert.lab.apple)

#### <a name="apidoc.element.color-convert.lab.apple.apple"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>apple (args)](#apidoc.element.color-convert.lab.apple.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.apple.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lab.apple.</span>raw (args)](#apidoc.element.color-convert.lab.apple.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lab.cmyk"></a>[module color-convert.lab.cmyk](#apidoc.module.color-convert.lab.cmyk)

#### <a name="apidoc.element.color-convert.lab.cmyk.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>cmyk (args)](#apidoc.element.color-convert.lab.cmyk.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.lab.cmyk.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lab.cmyk.</span>raw (args)](#apidoc.element.color-convert.lab.cmyk.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lab.gray"></a>[module color-convert.lab.gray](#apidoc.module.color-convert.lab.gray)

#### <a name="apidoc.element.color-convert.lab.gray.gray"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>gray (args)](#apidoc.element.color-convert.lab.gray.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.gray.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lab.gray.</span>raw (args)](#apidoc.element.color-convert.lab.gray.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lab.hcg"></a>[module color-convert.lab.hcg](#apidoc.module.color-convert.lab.hcg)

#### <a name="apidoc.element.color-convert.lab.hcg.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>hcg (args)](#apidoc.element.color-convert.lab.hcg.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.hcg.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lab.hcg.</span>raw (args)](#apidoc.element.color-convert.lab.hcg.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lab.hex"></a>[module color-convert.lab.hex](#apidoc.module.color-convert.lab.hex)

#### <a name="apidoc.element.color-convert.lab.hex.hex"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>hex (args)](#apidoc.element.color-convert.lab.hex.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.lab.hex.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lab.hex.</span>raw (args)](#apidoc.element.color-convert.lab.hex.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lab.hsl"></a>[module color-convert.lab.hsl](#apidoc.module.color-convert.lab.hsl)

#### <a name="apidoc.element.color-convert.lab.hsl.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>hsl (args)](#apidoc.element.color-convert.lab.hsl.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.lab.hsl.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lab.hsl.</span>raw (args)](#apidoc.element.color-convert.lab.hsl.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lab.hsv"></a>[module color-convert.lab.hsv](#apidoc.module.color-convert.lab.hsv)

#### <a name="apidoc.element.color-convert.lab.hsv.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>hsv (args)](#apidoc.element.color-convert.lab.hsv.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.lab.hsv.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lab.hsv.</span>raw (args)](#apidoc.element.color-convert.lab.hsv.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lab.hwb"></a>[module color-convert.lab.hwb](#apidoc.module.color-convert.lab.hwb)

#### <a name="apidoc.element.color-convert.lab.hwb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>hwb (args)](#apidoc.element.color-convert.lab.hwb.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.hwb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lab.hwb.</span>raw (args)](#apidoc.element.color-convert.lab.hwb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lab.keyword"></a>[module color-convert.lab.keyword](#apidoc.module.color-convert.lab.keyword)

#### <a name="apidoc.element.color-convert.lab.keyword.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>keyword (args)](#apidoc.element.color-convert.lab.keyword.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.keyword.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lab.keyword.</span>raw (args)](#apidoc.element.color-convert.lab.keyword.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lab.lch"></a>[module color-convert.lab.lch](#apidoc.module.color-convert.lab.lch)

#### <a name="apidoc.element.color-convert.lab.lch.lch"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>lch (args)](#apidoc.element.color-convert.lab.lch.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lab.lch.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lab.lch.</span>raw (args)](#apidoc.element.color-convert.lab.lch.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lab.rgb"></a>[module color-convert.lab.rgb](#apidoc.module.color-convert.lab.rgb)

#### <a name="apidoc.element.color-convert.lab.rgb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>rgb (args)](#apidoc.element.color-convert.lab.rgb.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.lab.rgb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lab.rgb.</span>raw (args)](#apidoc.element.color-convert.lab.rgb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lab.xyz"></a>[module color-convert.lab.xyz](#apidoc.module.color-convert.lab.xyz)

#### <a name="apidoc.element.color-convert.lab.xyz.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.lab.</span>xyz (args)](#apidoc.element.color-convert.lab.xyz.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```

#### <a name="apidoc.element.color-convert.lab.xyz.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lab.xyz.</span>raw (args)](#apidoc.element.color-convert.lab.xyz.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lch"></a>[module color-convert.lch](#apidoc.module.color-convert.lch)

#### <a name="apidoc.element.color-convert.lch.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>ansi16 (args)](#apidoc.element.color-convert.lch.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.lch.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>ansi256 (args)](#apidoc.element.color-convert.lch.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.apple"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>apple (args)](#apidoc.element.color-convert.lch.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>cmyk (args)](#apidoc.element.color-convert.lch.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.lch.gray"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>gray (args)](#apidoc.element.color-convert.lch.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>hcg (args)](#apidoc.element.color-convert.lch.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.hex"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>hex (args)](#apidoc.element.color-convert.lch.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.lch.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>hsl (args)](#apidoc.element.color-convert.lch.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.lch.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>hsv (args)](#apidoc.element.color-convert.lch.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.lch.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>hwb (args)](#apidoc.element.color-convert.lch.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>keyword (args)](#apidoc.element.color-convert.lch.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.lab"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>lab (args)](#apidoc.element.color-convert.lch.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.lch.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>rgb (args)](#apidoc.element.color-convert.lch.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.lch.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>xyz (args)](#apidoc.element.color-convert.lch.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```



# <a name="apidoc.module.color-convert.lch.ansi16"></a>[module color-convert.lch.ansi16](#apidoc.module.color-convert.lch.ansi16)

#### <a name="apidoc.element.color-convert.lch.ansi16.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>ansi16 (args)](#apidoc.element.color-convert.lch.ansi16.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.lch.ansi16.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lch.ansi16.</span>raw (args)](#apidoc.element.color-convert.lch.ansi16.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lch.ansi256"></a>[module color-convert.lch.ansi256](#apidoc.module.color-convert.lch.ansi256)

#### <a name="apidoc.element.color-convert.lch.ansi256.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>ansi256 (args)](#apidoc.element.color-convert.lch.ansi256.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.ansi256.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lch.ansi256.</span>raw (args)](#apidoc.element.color-convert.lch.ansi256.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lch.apple"></a>[module color-convert.lch.apple](#apidoc.module.color-convert.lch.apple)

#### <a name="apidoc.element.color-convert.lch.apple.apple"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>apple (args)](#apidoc.element.color-convert.lch.apple.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.apple.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lch.apple.</span>raw (args)](#apidoc.element.color-convert.lch.apple.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lch.cmyk"></a>[module color-convert.lch.cmyk](#apidoc.module.color-convert.lch.cmyk)

#### <a name="apidoc.element.color-convert.lch.cmyk.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>cmyk (args)](#apidoc.element.color-convert.lch.cmyk.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.lch.cmyk.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lch.cmyk.</span>raw (args)](#apidoc.element.color-convert.lch.cmyk.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lch.gray"></a>[module color-convert.lch.gray](#apidoc.module.color-convert.lch.gray)

#### <a name="apidoc.element.color-convert.lch.gray.gray"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>gray (args)](#apidoc.element.color-convert.lch.gray.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.gray.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lch.gray.</span>raw (args)](#apidoc.element.color-convert.lch.gray.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lch.hcg"></a>[module color-convert.lch.hcg](#apidoc.module.color-convert.lch.hcg)

#### <a name="apidoc.element.color-convert.lch.hcg.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>hcg (args)](#apidoc.element.color-convert.lch.hcg.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.hcg.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lch.hcg.</span>raw (args)](#apidoc.element.color-convert.lch.hcg.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lch.hex"></a>[module color-convert.lch.hex](#apidoc.module.color-convert.lch.hex)

#### <a name="apidoc.element.color-convert.lch.hex.hex"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>hex (args)](#apidoc.element.color-convert.lch.hex.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.lch.hex.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lch.hex.</span>raw (args)](#apidoc.element.color-convert.lch.hex.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lch.hsl"></a>[module color-convert.lch.hsl](#apidoc.module.color-convert.lch.hsl)

#### <a name="apidoc.element.color-convert.lch.hsl.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>hsl (args)](#apidoc.element.color-convert.lch.hsl.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.lch.hsl.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lch.hsl.</span>raw (args)](#apidoc.element.color-convert.lch.hsl.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lch.hsv"></a>[module color-convert.lch.hsv](#apidoc.module.color-convert.lch.hsv)

#### <a name="apidoc.element.color-convert.lch.hsv.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>hsv (args)](#apidoc.element.color-convert.lch.hsv.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.lch.hsv.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lch.hsv.</span>raw (args)](#apidoc.element.color-convert.lch.hsv.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lch.hwb"></a>[module color-convert.lch.hwb](#apidoc.module.color-convert.lch.hwb)

#### <a name="apidoc.element.color-convert.lch.hwb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>hwb (args)](#apidoc.element.color-convert.lch.hwb.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.hwb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lch.hwb.</span>raw (args)](#apidoc.element.color-convert.lch.hwb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lch.keyword"></a>[module color-convert.lch.keyword](#apidoc.module.color-convert.lch.keyword)

#### <a name="apidoc.element.color-convert.lch.keyword.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>keyword (args)](#apidoc.element.color-convert.lch.keyword.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.lch.keyword.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lch.keyword.</span>raw (args)](#apidoc.element.color-convert.lch.keyword.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lch.lab"></a>[module color-convert.lch.lab](#apidoc.module.color-convert.lch.lab)

#### <a name="apidoc.element.color-convert.lch.lab.lab"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>lab (args)](#apidoc.element.color-convert.lch.lab.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.lch.lab.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lch.lab.</span>raw (args)](#apidoc.element.color-convert.lch.lab.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lch.rgb"></a>[module color-convert.lch.rgb](#apidoc.module.color-convert.lch.rgb)

#### <a name="apidoc.element.color-convert.lch.rgb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>rgb (args)](#apidoc.element.color-convert.lch.rgb.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.lch.rgb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lch.rgb.</span>raw (args)](#apidoc.element.color-convert.lch.rgb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.lch.xyz"></a>[module color-convert.lch.xyz](#apidoc.module.color-convert.lch.xyz)

#### <a name="apidoc.element.color-convert.lch.xyz.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.lch.</span>xyz (args)](#apidoc.element.color-convert.lch.xyz.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```

#### <a name="apidoc.element.color-convert.lch.xyz.raw"></a>[function <span class="apidocSignatureSpan">color-convert.lch.xyz.</span>raw (args)](#apidoc.element.color-convert.lch.xyz.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.rgb"></a>[module color-convert.rgb](#apidoc.module.color-convert.rgb)

#### <a name="apidoc.element.color-convert.rgb.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>ansi16 (args)](#apidoc.element.color-convert.rgb.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.rgb.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>ansi256 (args)](#apidoc.element.color-convert.rgb.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.apple"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>apple (args)](#apidoc.element.color-convert.rgb.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>cmyk (args)](#apidoc.element.color-convert.rgb.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.rgb.gray"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>gray (args)](#apidoc.element.color-convert.rgb.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>hcg (args)](#apidoc.element.color-convert.rgb.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.hex"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>hex (args)](#apidoc.element.color-convert.rgb.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.rgb.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>hsl (args)](#apidoc.element.color-convert.rgb.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.rgb.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>hsv (args)](#apidoc.element.color-convert.rgb.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.rgb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>hwb (args)](#apidoc.element.color-convert.rgb.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>keyword (args)](#apidoc.element.color-convert.rgb.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.lab"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>lab (args)](#apidoc.element.color-convert.rgb.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.rgb.lch"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>lch (args)](#apidoc.element.color-convert.rgb.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>xyz (args)](#apidoc.element.color-convert.rgb.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```



# <a name="apidoc.module.color-convert.rgb.ansi16"></a>[module color-convert.rgb.ansi16](#apidoc.module.color-convert.rgb.ansi16)

#### <a name="apidoc.element.color-convert.rgb.ansi16.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>ansi16 (args)](#apidoc.element.color-convert.rgb.ansi16.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.rgb.ansi16.raw"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.ansi16.</span>raw (args)](#apidoc.element.color-convert.rgb.ansi16.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.rgb.ansi256"></a>[module color-convert.rgb.ansi256](#apidoc.module.color-convert.rgb.ansi256)

#### <a name="apidoc.element.color-convert.rgb.ansi256.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>ansi256 (args)](#apidoc.element.color-convert.rgb.ansi256.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.ansi256.raw"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.ansi256.</span>raw (args)](#apidoc.element.color-convert.rgb.ansi256.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.rgb.apple"></a>[module color-convert.rgb.apple](#apidoc.module.color-convert.rgb.apple)

#### <a name="apidoc.element.color-convert.rgb.apple.apple"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>apple (args)](#apidoc.element.color-convert.rgb.apple.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.apple.raw"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.apple.</span>raw (args)](#apidoc.element.color-convert.rgb.apple.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.rgb.cmyk"></a>[module color-convert.rgb.cmyk](#apidoc.module.color-convert.rgb.cmyk)

#### <a name="apidoc.element.color-convert.rgb.cmyk.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>cmyk (args)](#apidoc.element.color-convert.rgb.cmyk.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.rgb.cmyk.raw"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.cmyk.</span>raw (args)](#apidoc.element.color-convert.rgb.cmyk.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.rgb.gray"></a>[module color-convert.rgb.gray](#apidoc.module.color-convert.rgb.gray)

#### <a name="apidoc.element.color-convert.rgb.gray.gray"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>gray (args)](#apidoc.element.color-convert.rgb.gray.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.gray.raw"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.gray.</span>raw (args)](#apidoc.element.color-convert.rgb.gray.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.rgb.hcg"></a>[module color-convert.rgb.hcg](#apidoc.module.color-convert.rgb.hcg)

#### <a name="apidoc.element.color-convert.rgb.hcg.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>hcg (args)](#apidoc.element.color-convert.rgb.hcg.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.hcg.raw"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.hcg.</span>raw (args)](#apidoc.element.color-convert.rgb.hcg.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.rgb.hex"></a>[module color-convert.rgb.hex](#apidoc.module.color-convert.rgb.hex)

#### <a name="apidoc.element.color-convert.rgb.hex.hex"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>hex (args)](#apidoc.element.color-convert.rgb.hex.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.rgb.hex.raw"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.hex.</span>raw (args)](#apidoc.element.color-convert.rgb.hex.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.rgb.hsl"></a>[module color-convert.rgb.hsl](#apidoc.module.color-convert.rgb.hsl)

#### <a name="apidoc.element.color-convert.rgb.hsl.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>hsl (args)](#apidoc.element.color-convert.rgb.hsl.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.rgb.hsl.raw"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.hsl.</span>raw (args)](#apidoc.element.color-convert.rgb.hsl.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.rgb.hsv"></a>[module color-convert.rgb.hsv](#apidoc.module.color-convert.rgb.hsv)

#### <a name="apidoc.element.color-convert.rgb.hsv.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>hsv (args)](#apidoc.element.color-convert.rgb.hsv.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.rgb.hsv.raw"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.hsv.</span>raw (args)](#apidoc.element.color-convert.rgb.hsv.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.rgb.hwb"></a>[module color-convert.rgb.hwb](#apidoc.module.color-convert.rgb.hwb)

#### <a name="apidoc.element.color-convert.rgb.hwb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>hwb (args)](#apidoc.element.color-convert.rgb.hwb.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.hwb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.hwb.</span>raw (args)](#apidoc.element.color-convert.rgb.hwb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.rgb.keyword"></a>[module color-convert.rgb.keyword](#apidoc.module.color-convert.rgb.keyword)

#### <a name="apidoc.element.color-convert.rgb.keyword.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>keyword (args)](#apidoc.element.color-convert.rgb.keyword.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.keyword.raw"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.keyword.</span>raw (args)](#apidoc.element.color-convert.rgb.keyword.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.rgb.lab"></a>[module color-convert.rgb.lab](#apidoc.module.color-convert.rgb.lab)

#### <a name="apidoc.element.color-convert.rgb.lab.lab"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>lab (args)](#apidoc.element.color-convert.rgb.lab.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.rgb.lab.raw"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.lab.</span>raw (args)](#apidoc.element.color-convert.rgb.lab.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.rgb.lch"></a>[module color-convert.rgb.lch](#apidoc.module.color-convert.rgb.lch)

#### <a name="apidoc.element.color-convert.rgb.lch.lch"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>lch (args)](#apidoc.element.color-convert.rgb.lch.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.rgb.lch.raw"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.lch.</span>raw (args)](#apidoc.element.color-convert.rgb.lch.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.rgb.xyz"></a>[module color-convert.rgb.xyz](#apidoc.module.color-convert.rgb.xyz)

#### <a name="apidoc.element.color-convert.rgb.xyz.xyz"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.</span>xyz (args)](#apidoc.element.color-convert.rgb.xyz.xyz)
- description and source-code
```javascript
xyz = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	var y = (r * 0.2126) + (g * 0.7152) + (b * 0.0722);
	var z = (r * 0.0193) + (g * 0.1192) + (b * 0.9505);

	return [x * 100, y * 100, z * 100];
};

convert.rgb.lab = function (rgb) {
	var xyz = convert.rgb.xyz(rgb);
	var x = xyz[0];
	var y = xyz[1];
	var z = xyz[2];
	var l;
	var a;
	var b;
...
```

#### <a name="apidoc.element.color-convert.rgb.xyz.raw"></a>[function <span class="apidocSignatureSpan">color-convert.rgb.xyz.</span>raw (args)](#apidoc.element.color-convert.rgb.xyz.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.xyz"></a>[module color-convert.xyz](#apidoc.module.color-convert.xyz)

#### <a name="apidoc.element.color-convert.xyz.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>ansi16 (args)](#apidoc.element.color-convert.xyz.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.xyz.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>ansi256 (args)](#apidoc.element.color-convert.xyz.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.apple"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>apple (args)](#apidoc.element.color-convert.xyz.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>cmyk (args)](#apidoc.element.color-convert.xyz.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.xyz.gray"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>gray (args)](#apidoc.element.color-convert.xyz.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>hcg (args)](#apidoc.element.color-convert.xyz.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.hex"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>hex (args)](#apidoc.element.color-convert.xyz.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.xyz.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>hsl (args)](#apidoc.element.color-convert.xyz.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.xyz.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>hsv (args)](#apidoc.element.color-convert.xyz.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.xyz.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>hwb (args)](#apidoc.element.color-convert.xyz.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>keyword (args)](#apidoc.element.color-convert.xyz.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.lab"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>lab (args)](#apidoc.element.color-convert.xyz.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.xyz.lch"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>lch (args)](#apidoc.element.color-convert.xyz.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>rgb (args)](#apidoc.element.color-convert.xyz.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```



# <a name="apidoc.module.color-convert.xyz.ansi16"></a>[module color-convert.xyz.ansi16](#apidoc.module.color-convert.xyz.ansi16)

#### <a name="apidoc.element.color-convert.xyz.ansi16.ansi16"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>ansi16 (args)](#apidoc.element.color-convert.xyz.ansi16.ansi16)
- description and source-code
```javascript
ansi16 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

	return ansi;
};

convert.hsv.ansi16 = function (args) {
	// optimization here; we already know the value and don't need to get
	// it converted for us.
	return convert.rgb.ansi16(convert.hsv.rgb(args), args[2]);
};

convert.rgb.ansi256 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
...
```

#### <a name="apidoc.element.color-convert.xyz.ansi16.raw"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.ansi16.</span>raw (args)](#apidoc.element.color-convert.xyz.ansi16.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.xyz.ansi256"></a>[module color-convert.xyz.ansi256](#apidoc.module.color-convert.xyz.ansi256)

#### <a name="apidoc.element.color-convert.xyz.ansi256.ansi256"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>ansi256 (args)](#apidoc.element.color-convert.xyz.ansi256.ansi256)
- description and source-code
```javascript
ansi256 = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.ansi256.raw"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.ansi256.</span>raw (args)](#apidoc.element.color-convert.xyz.ansi256.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.xyz.apple"></a>[module color-convert.xyz.apple](#apidoc.module.color-convert.xyz.apple)

#### <a name="apidoc.element.color-convert.xyz.apple.apple"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>apple (args)](#apidoc.element.color-convert.xyz.apple.apple)
- description and source-code
```javascript
apple = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.apple.raw"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.apple.</span>raw (args)](#apidoc.element.color-convert.xyz.apple.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.xyz.cmyk"></a>[module color-convert.xyz.cmyk](#apidoc.module.color-convert.xyz.cmyk)

#### <a name="apidoc.element.color-convert.xyz.cmyk.cmyk"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>cmyk (args)](#apidoc.element.color-convert.xyz.cmyk.cmyk)
- description and source-code
```javascript
cmyk = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)
...
```

#### <a name="apidoc.element.color-convert.xyz.cmyk.raw"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.cmyk.</span>raw (args)](#apidoc.element.color-convert.xyz.cmyk.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.xyz.gray"></a>[module color-convert.xyz.gray](#apidoc.module.color-convert.xyz.gray)

#### <a name="apidoc.element.color-convert.xyz.gray.gray"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>gray (args)](#apidoc.element.color-convert.xyz.gray.gray)
- description and source-code
```javascript
gray = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.gray.raw"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.gray.</span>raw (args)](#apidoc.element.color-convert.xyz.gray.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.xyz.hcg"></a>[module color-convert.xyz.hcg](#apidoc.module.color-convert.xyz.hcg)

#### <a name="apidoc.element.color-convert.xyz.hcg.hcg"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>hcg (args)](#apidoc.element.color-convert.xyz.hcg.hcg)
- description and source-code
```javascript
hcg = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.hcg.raw"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.hcg.</span>raw (args)](#apidoc.element.color-convert.xyz.hcg.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.xyz.hex"></a>[module color-convert.xyz.hex](#apidoc.module.color-convert.xyz.hex)

#### <a name="apidoc.element.color-convert.xyz.hex.hex"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>hex (args)](#apidoc.element.color-convert.xyz.hex.hex)
- description and source-code
```javascript
hex = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
All functions that accept multiple arguments also support passing an array.

Note that this does **not** apply to functions that convert from a color that only requires one value (e.g. 'keyword', 'ansi256', '
hex', etc.)

'''js
var convert = require('color-convert');

convert.rgb.hex(123, 45, 67);      // '7B2D43'
convert.rgb.hex([123, 45, 67]);    // '7B2D43'
'''

## Routing

Conversions that don't have an _explicitly_ defined conversion (in [conversions.js](conversions.js)), but can be converted by means
 of sub-conversions (e.g. XYZ -> **RGB** -> CMYK), are automatically routed together. This allows just about any color model supported
 by 'color-convert' to be converted to any other model, so long as a sub-conversion path exists. This is also true for conversions
 requiring more than one step in between (e.g. LCH -> **LAB** -> **XYZ** -> **RGB** -> Hex).
...
```

#### <a name="apidoc.element.color-convert.xyz.hex.raw"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.hex.</span>raw (args)](#apidoc.element.color-convert.xyz.hex.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.xyz.hsl"></a>[module color-convert.xyz.hsl](#apidoc.module.color-convert.xyz.hsl)

#### <a name="apidoc.element.color-convert.xyz.hsl.hsl"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>hsl (args)](#apidoc.element.color-convert.xyz.hsl.hsl)
- description and source-code
```javascript
hsl = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''
...
```

#### <a name="apidoc.element.color-convert.xyz.hsl.raw"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.hsl.</span>raw (args)](#apidoc.element.color-convert.xyz.hsl.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.xyz.hsv"></a>[module color-convert.xyz.hsv](#apidoc.module.color-convert.xyz.hsv)

#### <a name="apidoc.element.color-convert.xyz.hsv.hsv"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>hsv (args)](#apidoc.element.color-convert.xyz.hsv.hsv)
- description and source-code
```javascript
hsv = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
	return [l, a, b];
};

convert.rgb.ansi16 = function (args) {
	var r = args[0];
	var g = args[1];
	var b = args[2];
	var value = 1 in arguments ? arguments[1] : convert.rgb.hsv(args)[2]; // hsv -> ansi16 optimization

	value = Math.round(value / 50);

	if (value === 0) {
		return 30;
	}
...
```

#### <a name="apidoc.element.color-convert.xyz.hsv.raw"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.hsv.</span>raw (args)](#apidoc.element.color-convert.xyz.hsv.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.xyz.hwb"></a>[module color-convert.xyz.hwb](#apidoc.module.color-convert.xyz.hwb)

#### <a name="apidoc.element.color-convert.xyz.hwb.hwb"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>hwb (args)](#apidoc.element.color-convert.xyz.hwb.hwb)
- description and source-code
```javascript
hwb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.hwb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.hwb.</span>raw (args)](#apidoc.element.color-convert.xyz.hwb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.xyz.keyword"></a>[module color-convert.xyz.keyword](#apidoc.module.color-convert.xyz.keyword)

#### <a name="apidoc.element.color-convert.xyz.keyword.keyword"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>keyword (args)](#apidoc.element.color-convert.xyz.keyword.keyword)
- description and source-code
```javascript
keyword = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.keyword.raw"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.keyword.</span>raw (args)](#apidoc.element.color-convert.xyz.keyword.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.xyz.lab"></a>[module color-convert.xyz.lab](#apidoc.module.color-convert.xyz.lab)

#### <a name="apidoc.element.color-convert.xyz.lab.lab"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>lab (args)](#apidoc.element.color-convert.xyz.lab.lab)
- description and source-code
```javascript
lab = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...

All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''
...
```

#### <a name="apidoc.element.color-convert.xyz.lab.raw"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.lab.</span>raw (args)](#apidoc.element.color-convert.xyz.lab.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.xyz.lch"></a>[module color-convert.xyz.lch](#apidoc.module.color-convert.xyz.lch)

#### <a name="apidoc.element.color-convert.xyz.lch.lch"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>lch (args)](#apidoc.element.color-convert.xyz.lch.lch)
- description and source-code
```javascript
lch = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.color-convert.xyz.lch.raw"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.lch.</span>raw (args)](#apidoc.element.color-convert.xyz.lch.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# <a name="apidoc.module.color-convert.xyz.rgb"></a>[module color-convert.xyz.rgb](#apidoc.module.color-convert.xyz.rgb)

#### <a name="apidoc.element.color-convert.xyz.rgb.rgb"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.</span>rgb (args)](#apidoc.element.color-convert.xyz.rgb.rgb)
- description and source-code
```javascript
rgb = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		var result = fn(args);

		// we're assuming the result is an array here.
		// see notice in conversions.js; don't use box types
		// in conversion functions.
		if (typeof result === 'object') {
			for (var len = result.length, i = 0; i < len; i++) {
				result[i] = Math.round(result[i]);
			}
		}

		return result;
	}
```
- example usage
```shell
...
Color-convert is a color conversion library for JavaScript and node.
It converts all ways between 'rgb', 'hsl', 'hsv', 'hwb', 'cmyk', 'ansi', 'ansi16', 'hex' strings, and CSS 'keyword's (will round
 to closest):

'''js
var convert = require('color-convert');

convert.rgb.hsl(140, 200, 100);             // [96, 48, 59]
convert.keyword.rgb('blue');                // [0, 0, 255]

var rgbChannels = convert.rgb.channels;     // 3
var cmykChannels = convert.cmyk.channels;   // 4
var ansiChannels = convert.ansi16.channels; // 1
'''

# Install
...
```

#### <a name="apidoc.element.color-convert.xyz.rgb.raw"></a>[function <span class="apidocSignatureSpan">color-convert.xyz.rgb.</span>raw (args)](#apidoc.element.color-convert.xyz.rgb.raw)
- description and source-code
```javascript
raw = function (args) {
		if (args === undefined || args === null) {
			return args;
		}

		if (arguments.length > 1) {
			args = Array.prototype.slice.call(arguments);
		}

		return fn(args);
	}
```
- example usage
```shell
...
All 'from' functions have a hidden property called '.channels' that indicates the number of channels the function expects (not including
 alpha).

'''js
var convert = require('color-convert');

// Hex to LAB
convert.hex.lab('DEADBF');         // [ 76, 21, -2 ]
convert.hex.lab.raw('DEADBF');     // [ 75.56213190997677, 20.653827952644754, -2.290532499330533 ]

// RGB to CMYK
convert.rgb.cmyk(167, 255, 4);     // [ 35, 0, 98, 0 ]
convert.rgb.cmyk.raw(167, 255, 4); // [ 34.509803921568626, 0, 98.43137254901961, 0 ]
'''

### Arrays
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
