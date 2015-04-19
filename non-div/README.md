Non-`<div>`
===========
HTML5 sectioning elements are unsupported in <=IE8.

Fallback
--------
* You need [html5shiv][] for unsupported browsers.

Example
-------

```html
<html>
    <head>
        <!--[if lt IE 9]>
            <script src="/js//html5shiv.min.js"></script>
            <script src="/js/html5shiv-printshiv.min.js"></script>
        <![endif]-->
    </head>
    <body>
        <header></header>
        <main>
            <section>
                <article></article>
            </section>
        </main>
        <footer></footer>
    </body>
</html>
```


[html5shiv]: https://github.com/aFarkas/html5shiv
