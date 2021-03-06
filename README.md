# Absolute Positioning Example
(v1.0)

![Screen shot of absolute position example](img/screen-shot.png "Screen shot of absolute position example")

This example shows four nested `div` elements with different colored borders. The position for each `div` is `static`, the default. Every 1.5 seconds, the position property for one of the inner `div` elements is set to `absolute` and offset from the `top` and `left` by 0 pixels.

After 1.5 seconds, that element’s position property is set back to `static` and an outer `div`’s position is set to `absolute`, setting the cycle in motion again. This is repeated for all four elements and shows how any element marked `position: absolute` looks for a non-`static` parent, then binds to the initial containing block if one is not found.

— Roy Vanegas
