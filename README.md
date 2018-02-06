# unstash
a quick and dirty tumblr theme bc i was sick of customising someone else's one

this is literally a one-night job, don't @ me

## how to use
if you'd like to try this theme out for a spin, open up tumblr's "customise html" screen for the blog you want to skin and copy and paste the entirety of `index.html` in there. make sure to delete the current one before you do so.

i've provided the following customisation options:

- description toggle
- background color
- text color
- two accent colors, currently just for links
- random link toggle
- archive link toggle
- rss link toggle
- hq images toggle
- four custom sidebar links

i'm planning on making it more flexible but you should feel free to go into custom html and edit things for yourself. the html and css structure is a lot less complex than most tumblr themes. i use css variables, so basic customisations like sidebar widith and how wide the posts are in the grid can be changed there. open up the html and look for this bit of css:

```
:root{
  ...
  --sidebar-width: 12rem;
  --post-width: 25rem;
}
```

### todo
- [ ] allow font family selection
- [ ] custom toggle showing photo captions, titles and tags on index page
- [ ] research how to make css grid rows break naturally whilst keeping columns (might end up needing flexbox, hmm)
- [ ] typography still needs work
- [ ] support other post types

