![Version](https://img.shields.io/badge/version-1.1.1-orange.svg)
![Plaftorm](https://img.shields.io/badge/platform-TextMate-blue.svg)


# Bootstrap 3 Helpers for TextMate2

Un-official Bootstrap 3 html helper bundle for you with ❤️


## Installation

```bash
cd ~/Library/Application\ Support/TextMate/Bundles/
git clone https://github.com/vigo/textmate2-bootstrap3.git Bootstrap3.tmbundle

# Restart your TextMate2
```


## Available Items

`html5` + <kbd>⇥</kbd>

Creates base template + adds `Merriweather` font from Google.

```html
<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Hello World</title>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
        <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
        <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
        <!--[if lt IE 9]>
            <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
            <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
        <![endif]-->        
        <style type="text/css" media="screen">
            @import url(https://fonts.googleapis.com/css?family=Merriweather:400,300,300italic,400italic,700,700italic,900,900italic&subset=latin,latin-ext);
            body { font-family: 'Merriweather', serif; }
        </style>
    </head>
    <body>

        <div class="block">
            <div class="container">
                <div class="row">
                    <div class="col-xs-12">
                        <h1>${0:Hello World}</h1>
                    </div>
                </div>
            </div>
        </div>

        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
    </body>
</html>
```

---

### Grid

* `con` + <kbd>⇥</kbd>: Creates `container` | `container-fluid`
* `blo` + <kbd>⇥</kbd>: Creates `div` with class `block`
* `row` + <kbd>⇥</kbd>: Creates `div` with class `row`
* `col` + <kbd>⇥</kbd>: Bootstrap’s columns
* `cell` + <kbd>⇥</kbd>: Creates additional column information.
* `offset` + <kbd>⇥</kbd>: Column offsets...
* `order` + <kbd>⇥</kbd>: Helps for `pull` and `push` columns.

---

### Typography

* `h` + <kbd>⇥</kbd>: Creates `<h1>` to `<h6>` + `<small>` option.
* `.h` + <kbd>⇥</kbd>: Creates `class="h1"` to `class="h6"`
* <kbd>⌘</kbd> + <kbd>⇧</kbd> + <kbd>i</kbd>: Inlines : `<del>`, `<mark>`, `<small>`, `<ins>`, `<u>`
* `lead` + <kbd>⇥</kbd>: Paragraph with `class="lead"`
* `.lead` + <kbd>⇥</kbd>: Only `class="lead"`

---

## Contributers

* [Uğur "vigo" Özyılmazel](https://github.com/vigo) - Creator, maintainer

---

## Contribute

1. `fork` (https://github.com/vigo/textmate2-bootstrap3/fork)
2. Create your `branch` (`git checkout -b my-features`)
3. `commit` yours (`git commit -am 'added killer features'`)
4. `push` your `branch` (`git push origin my-features`)
5. Than create a new **Pull Request**!

---

## License

This project is licensed under MIT.
