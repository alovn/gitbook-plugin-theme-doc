# Gitbook theme for Docs

## Usage

Add the theme to your book's configuration `book.json` or `book.js`:

```js
{
    "plugins": [
        "theme-doc@git+ssh://git@github.com:alovn/gitbook-plugin-theme-doc.git"
    ],
    "variables": {
        "themeDoc":{
            "nav":[
                {
                    "url":"http://...",
                    "target":"_blank",
                    "name": "Demo"
                }
            ]
        },
    },
    "pluginsConfig": {
        "theme-doc":{
            "search-placeholder":"输入关键字搜索", //搜索框提示信息
            "logo":"./logo.png", //logo地址
            "favicon": "./favicon.ico" //ico地址
        }
    }
},
```

Install by command:

``` bash
gitbook install
```

Enjoy!
