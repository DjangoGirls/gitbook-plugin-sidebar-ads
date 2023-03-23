# GitBook Sidebar Ad with Carousel plugin

Add a nice sidebar ad to your GitBook with a carousel to cater for sponsored ads. This is based on the [GitBook Sidebar Ad](https://www.npmjs.com/package/gitbook-plugin-sidebar-ad) plugin developed by [Ola Sitarska]() for the Django Girls Tutorial.

## Example:

![Example](http://i.imgur.com/K3HPXzm.png)

[See demo](https://tutorial.djangogirls.org/en/)

## How to use it:

Add this to your "book.json":

```
{
    "plugins": ["sidebar-ads"],
    "pluginsConfig": {
        "sidebar-ads": {
            "ads": [
                {
                    "imageUrl": "https://i.imgur.com/K3HPXzm.png",
                    "url": "http://google.com/",
                    "description": "text",
                    "btnText": "Buy me again!"
                },
                {
                    "imageUrl": "https://i.imgur.com/K3HPXzm.png",
                    "url": "http://google.com/",
                    "description": "text",
                    "btnText": "Buy me again!"
                },
            ]
        },
    }
}
```

## License

BSD
