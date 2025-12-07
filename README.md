# FeedLand for Micro.blog

This plug-in adds a new shortcode that can be used in Micro.blog pages. In a blog post or standalone page, add this snippet of text, using your FeedLand.com username:

```
{{< feedland username="your-username" >}}
```

To include the blogroll in a theme template, for example in a sidebar, first set your FeedLand username in the plug-in settings. Then use this Hugo code:

```
{{ partial "feedland_embed.html" }}
```

![icon](icon.png)
