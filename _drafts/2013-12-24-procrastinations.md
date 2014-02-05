---
layout: post
title:  "procrastinations"
date:   2013-12-24 00:00:00
categories: blog
---

You'll find this post in your `_posts` directory - edit this post and re-build (or run with the `-w` switch) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention: YYYY-MM-DD-name-of-post.ext.

```javascript
Object.prototype.hej = function(){ return "hej " + this.toString();};
var cody = {};
cody.asdf ="qwer";
cody.date = new Date();
```

Jekyll also offers powerful support for code snippets:

```javascript 
Object.prototype.hej = function(){ return "hej " + this.toString();};
var cody = {};
cody.asdf ="qwer";
cody.date = new Date();
```

and also:

```java 
AisReader reader = AisReaders.createReaderFromInputStream(inputStream);
reader.registerHandler(new Consumer<AisMessage>() {
    @Override
    public void accept(AisMessage aisMessage) {
        GeoEvent event = createGeoEvent(aisMessage);
        if (event != null) {
            geoEventListener.receive(event);
        } 
    }
});
```

and of course:

```brainfuck
+[-<+]-ÿ<<<<<<<[.>]
```
