# png-example

![screenshot](screenshots/screenshot.png)

Simple example app that demonstrates loading color PNG resources on Pebble SDK
3.0.

Uses `bitmap_layer_set_compositing_mode(s_bitmap_layer, GCompOpSet)` to
correctly render PNG transparency.