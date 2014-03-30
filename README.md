# Middleman for Ghost

I'm not a big fan of the node dev environment, but I love Ghost. So I set up a Middleman template for developing Ghost themes.

You get all of the goodness of gems, sprockets, and whatnot in development from the Middleman server; then a Middleman build gives you everything packaged up all nice for Ghost.

You also get real blog settings and post data from the ghost-dev.db while running the Middleman server.

##Installation
1. Clone/copy/whatever into [Ghost dir]/content/themes
2. ```bundle install```
3. ```middleman server```
4. Develop your theme
5. ```middleman build```
6. Preview on node dev server


---

[Ghost](https://github.com/TryGhost/Ghost) v0.4  
[Middleman](https://github.com/TryGhost/Ghost) v3.0.13