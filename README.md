SukerMarioBros — Swift and SpriteKit
==============

This is a hacathon project done in like 12 hours — expect troubles :)

It builds on iOS7&8 in xCode6 beta 2, but sprites doesn't load on iOS7 — http://stackoverflow.com/questions/24069168/swift-and-spritekit-wont-run-on-device-running-ios-7-1

There's a map for the whole first level. You can use Tiled to edit the level map — http://www.mapeditor.org/
You can find other sprites here http://www.spriters-resource.com/nes/supermariobros/ or elsewhere.

Nodes for collisions load (not at all lazily) from "Collisions" objects layer in the .tmx level map. They are stored inside a node, which moves together with the map. Not all collidable objects are added :)

Collectables (mushrooms, coins) are just rendered where they should be, for now (not by objects, simply by static tiles). There're no enemies. 

I didn't have time to process any collisions. Mario can move through obstacles, if pressed by the walls :)

Have fun and contact me if you have issues.

![](https://scontent-b.xx.fbcdn.net/hphotos-xpa1/t1.0-9/10516819_659707870778456_6413796525526250145_n.jpg)
