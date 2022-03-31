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
            "your-ad'": {
                "imageUrl": "http://i.imgur.com/K3HPXzm.png", // Url to your ad
                "url": "http://google.com/", // Url that image will be linked to, optional
                "description": "text", // Text next to the add, optional
                "btnText": "Buy me!" // Text for the Call to Action button, optional
            },
            "sponsor-ads" : [
                {
                    "imageUrl": "http://i.imgur.com/K3HPXzm.png", // Url to your sponsor ad
                    "url": "http://google.com/", // Url that image will be linked to, optional
                    "description": "text", // Text next to the add, optional
                    "btnText": "Buy me again!" // Text for the Call to Action button, optional
                }
            ]
        }
    }
}
```

## License

BSD
