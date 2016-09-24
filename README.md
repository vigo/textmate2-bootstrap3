# Bootstrap 3 Helpers for TextMate2

## Installation

```bash
cd "~/Library/Application Support/Avian/Bundles/"
# if you don’t have Avian/Bundles folder, you need to create it!

git clone https://github.com/vigo/textmate2-bootstrap3.git textmate2-bootstrap3.tmbundle
# reload your TextMate2
```

## Available Items

`html5`: Creates base template + adds `Merriweather` font from Google.

```html
<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Hello World</title>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" integrity="sha384-1q8mTJOASx8j1Au+a5WDVnPi2lkFfwwEAa8hDDdjZlpLegxhjVME1fgjWPGmkzs7" crossorigin="anonymous">
        <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
        <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
        <!--[if lt IE 9]>
            <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
            <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
        <![endif]-->
        <style type="text/css" media="screen">
            @import url(https://fonts.googleapis.com/css?family=Merriweather:400,300,300italic,400italic,700,700italic,900,900italic&subset=latin,latin-ext);
            body {
                font-family: 'Merriweather', serif;
            }
        </style>
    </head>
    <body>

        <div class="block">
            <div class="container">
                <div class="row">
                    <div class="col-xs-12">
                        <h1>Hello World</h1>
                    </div>
                </div>
            </div>
        </div>

        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js" integrity="sha384-0mSbJDEHialfmuBBQP6A4Qrprq5OVfW37PRR3j5ELqxss1yVqOtnepnHVP9aJ7xS" crossorigin="anonymous"></script>
    </body>
</html>
```

***

### Grid

* `con`: Creates `container` | `container-fluid`
* `blo`: Creates `div` with class `block`
* `con`: Creates `div` with class `container`
* `row`: Creates `div` with class `row`
* `col`: BS’s cols...
* `cell`: Creates additional col information.
* `offset`: Column offsets...
* `order`: Helps for `pull` and `push`

***

### Typography

* `h`: Creates `<h1>` to `<h6>` + `<small>` option.
* `.h`: Creates `class="h1"` to `class="h6"`
* `cmd+shift+i`: Inlines : `<del>`, `<mark>`, `<small>`, `<ins>`, `<u>`
* `lead`: Paragraph with `class="lead"`
* `.lead`: Only `class="lead"`

## Change Log

**2016-09-24**

* `del`, `small`, `kbd` added.

**2016-03-25**

* Alignment and Transformation classes added.
* `h` and `.h` added.
* Inline elements added `cmd+shift+i`
* `html5` added.
* `con` added.

**2016-03-20**

* Initial release.
* Grid helpers added.

***

## Contributers

* [Uğur "vigo" Özyılmazel](https://github.com/vigo) - Creator, maintainer

***

## Contribute

1. `fork` (https://github.com/vigo/textmate2-bootstrap3/fork)
2. Create your `branch` (`git checkout -b my-features`)
3. `commit` yours (`git commit -am 'added killer features'`)
4. `push` your `branch` (`git push origin my-features`)
5. Than create a new **Pull Request**!


***

## License

This project is licensed under MIT.
