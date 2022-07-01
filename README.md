Quick CSS parallax

1. Create "scroll container/context" separate from the body (.wrapper), set perspective value to it
2. preserve-3d in the parallax container, usually would be a header element/named that
3. translateZ relative to set perspective in container/wrapper, scale to same size. Things further apart appear to move slower... foreground closer than bg. Text closest.