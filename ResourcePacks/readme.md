# add_new_custom_item_demoV1

we can get item using this command.

`/give Lobo_The_Wolf minecraft:black_concrete[minecraft:item_model="cwresports:cat_display"] 1`

this item_model = `add_new_custom_item_demoV1/assets/cwresports/items/cat_display.json`
if there is no `cwresports/items/cat_display.json` model item look like a null block

we can animate the texture of\
`add_new_custom_item_demoV1/assets/cwresports/textures/block/cat_display.png` \
by adding \
`add_new_custom_item_demoV1/assets/cwresports/textures/block/cat_display.png.mcmeta file`

just like this

```json
{
  "animation": {
    "frametime": 10,
    "interpolate": false
  }
}
```

if "interpolate": true , that animation so smooth and fading

