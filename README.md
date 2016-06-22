# GitBook Sidebar Ad plugin

Add a nice sidebar ad to your GitBook. 

## Example:

[Example](http://i.imgur.com/K3HPXzm.png)

## How to use it:

Add this to your "book.json":

```
{
    "plugins": ["sidebar-ad"],
    "pluginsConfig": {
        "sidebar-ad": {
            "imageUrl": "http://i.imgur.com/K3HPXzm.png", // Url to your ad
            "url": "http://google.com/", // Url that image will be linked to, optional
            "description": "text", // Text next to the add, optional
            "btnText": "Buy me!" // Text for the Call to Action button, optional
        }
    }
}
```

## License

BSD
