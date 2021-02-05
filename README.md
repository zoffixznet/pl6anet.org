# planet.raku.org

This repo provides the links for the Raku news feeds on
[pl6anet.org](https://pl6anet.org).

That collection is the source for the world-famous
[Raku Weekly News](https://rakudoweekly.blog/blog-feed) 
which is curated and edited by Elizabeth Mattijsen.

Persons who wish to add their favorite Raku blog sites
to that collection should use the following instructions. (Please file an
issue if you have any problems, or ask for help
on IRC channel \#raku.  Note you can use either the rss or the atom feed format.)

1. Fork this repo on Github.

2. Add your entry to the **perlanetrc** file.

For example, the following is the entry for the
[Raku Weekly News](https://rakudoweekly.blog/blog-feed):

~~~
 -  url: https://rakudoweekly.blog/feed/
    title: Rakudo Weekly News
    web: https://rakudoweekly.blog/
~~~

The **url** is the path to the file containing the actual atom or rss code. Note the 
example above probably ends at the implied **index.html**.

The **title** is what the author wants the viewer of 
[pl6anet.org](https://pl6anet.org) to see for his or her entry.

The **web** is the link to the home page of the blog being referenced.

3. Submit a PR (pull request).


