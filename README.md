MyBootstrap
-----------

When I'm developing a cordova application or a website, I always define some
useful class such that *no-margin* to set to 0 margin properties of an object,
or *text-left* to align text on left.

To avoid to rewrite same classes, I add these useful classes into a less or sass
file name mybootstrap. When I begin a new project, I import the less or sass
file.

I use these small bootstrap file to avoid to have lots of classes I don't need
with popular libraries such as [http://bootstrap.com](Bootstrap Twitter).

Class list
=======

- **no-margin?[-left/right/bottom/top]**: set *margin?[-left/right/bottom/top]*
  to 0.

- **no-padding?[-left/right/bottom/top]**: set *padding?[-left/right/bottom/top]*
  to 0.

- **text-[center/left/right]**: set text-align to [center/left/right]
