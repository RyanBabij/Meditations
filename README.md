# Meditations
 Wiki software

I've been using [TiddlyWiki](https://tiddlywiki.com/) for keeping notes and ideas organised. I've been using it for over 3 years now and overall it's pretty good. I have a total of 3,849 tiddlers with a total wordcount of 1,745,293 and it has been growing fairly steadily. I've had a lot of time to think about parts of the software I would like to improve.

I've identified a few major issues for which unfortunately I could not come up with a satisfactory resolution:

* The search feature does not scale well. You are only given a list of tiddlers where a match has been found. As the wiki gets bigger you can end up with massive lists of matches.
* Backups are awkward to manage.
* There is no wikipedia-style history tracking.
* There are no sortable tables.
* Images can be embedded directly in the wiki folder but this very quickly bloats the file. Or you can link to them using a file path, but this has to be done manually and there's no way to manage all the images you've linked to.
* You can't link between different wikis.
* Tiddlers with more than a few thousand words can start to lag.
* Managing your wiki over multiple devices is difficult and there's no sycnchronisation process.

Most of these issues are easy enough to deal with, but I've finally decided I might as well go ahead and see if I can implement my own wiki system which works a little better for me. I intend it to be barebones and only implement the exact features that I use, so I doubt other people will want to use it. But I figure I might as well put it up here anyway.

I basically want to implement the following features:

* Text support (obviously lol)
* Linking between wikis
* Human-readable portable markdown
* JPEG/PNG support, linking by hash/phash.
* Better search system.
* Change tracking and diffs.
* Tags (Videogame, book, movie)
* key:value pairs (year_published:2011)
* List and sort articles by tag or key:value.
* Sortable tables
* Inter-article linking (table of contents basically)
* Support for reasonably large articles (~20,000 words) without input/viewing lag.

I have no idea how long it'll take to implement each feature but I'd like to have something functional within a few months. I then plan to migrate to that system and slowly implement functionality as I need it. So initially I want to just make a bunch of interlinked text-only articles and kinda go from there.
