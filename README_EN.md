[[Эти же советы на русском]](https://github.com/procedural/magicacsg_tips/blob/main/README.md)

* [[Link]](https://twitter.com/redgpus/status/1399359753487323138) #MagicaCSG v0.0.0 tips: since there is no way to select strokes of multiple layers, prefer to keep strokes of a symmetric object on one layer. This way it'll be easier to delete one half of the object, move or rotate the other half, and recreate the deleted half with a flip trick.

* #MagicaCSG v0.0.0:
```
Size X:   Cube --- 2 -- 2   --- 2     --- 2     --- X1 --- 447.5  --- 447.5
Size Y:   Cube --- 2 -- 2   --- 2     --- 893   --- X1 --- 893    --- 893
Size Z:   Cube --- 2 -- 2   --- 893   --- 893   --- X1 --- 893    --- 893

Center X: Cube --- 1 -- 1   --- 1     --- 1     --- X1 --- 223.75 --- 222.5
Center Y: Cube --- 0 -- 0   --- 0     --- 0     --- X1 --- 0      --- 0
Center Z: Cube --- 2 -- 893 --- 447.5 --- 447.5 --- X1 --- 447.5  --- 447.5
```

* [[Link]](https://twitter.com/redgpus/status/1398992183726837763) #MagicaCSG v0.0.0 tips: the " character in layer names is disallowed.

* [[Link]](https://twitter.com/redgpus/status/1397848141379026944) #MagicaCSG v0.0.0 tips: as of now, you can't export or import current camera position and orientation, so as a workaround you can create a dummy tiny sphere stroke on a new layer and focus camera on it by pressing key 5. Restart the scene and press 5 to get back to that position.

* [[Link]](https://twitter.com/redgpus/status/1397844271072436226) #MagicaCSG v0.0.0 tips: currently, there's no way to export and import all the settings of a scene, so make screenshots of everything (Ctrl + 6) to type everything back in later.
