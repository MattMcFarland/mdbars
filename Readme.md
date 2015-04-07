# mdbars

[Express.js](http://github.com/visionmedia/express) view engine for Markdown using
[handlebars.js](http://github.com/wycats/handlebars.js)

This is a modification of [hbs](https://github.com/donpark/hbs) version 2.9.0.  so you can do all the cool stuff  [hbs](https://github.com/donpark/hbs) does, but on markdown instead of html.

## Install ##

```
npm install mdbars
```

## Use ##

Using *mdbars* as the default view engine requires just one line of code in your app setup. This will render `.hbs` files when `res.render` is called.

```javascript
app.set('view engine', 'mdbars');
```

To use a different extension (i.e. html) for your template files:

```javascript
app.set('view engine', 'mdbars');
app.engine('mdbars', require('mdbars').__express);
```

## Layout ##

You can subsitute the express generators structure using the same layout system.

    /views
        layout.md
        index.md
        users.md


## More Info ##

mdbars is a sister of [hbs](https://github.com/donpark/hbs), this means you can use a lot of stuff  [hbs](https://github.com/donpark/hbs) uses, same syntax and all.. just replace `hbs` with `mdbars` and you are good to go.