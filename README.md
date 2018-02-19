# #shefcodefirst HTML course resources

## Creating a session's slides

Use [reveal.js](htttps://github.com/hakimel/reveal.js) to create the slideshow. The bare slides themselves should rest in `_includes/sessionX.html`. Then, create two files in the project root with the following content:

```
---
layout: <client/master>
---
include sessionX.html [surrounded by percent signs and curly brackets, but Liquid is overly sensitive so I can't do this. See session4-<client/master>.html for demo.]
```

Name these `sessionX-<client/master>` - one for the client, and one for the master. Pushing to the GitHub origin will make the client version accessible at [https://shefcodefirstgirls.github.io/shefcodefirst-html](https://shefcodefirstgirls.github.io/shefcodefirst-html)/sessionX-client. 

## Presenting

You'll need to run this locally, in which case you should navigate to localhost:4000/sessionX-master after making sure your config has the client ID and secret of the multiplexing server. Then your audience can follow along at the client version link in the previous section.
