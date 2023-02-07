# wanna-see-a-whiter-white

> Visit https://fff.kidi.ng for the demo.

<img src="https://github.com/kiding/wanna-see-a-whiter-white/raw/gh-pages/demo.jpg">

## How does this work?

By combining an HDR video with CSS hack, the white color of the text becomes even brighter.

```css
#whiter {
  filter: brightness(10);
  backdrop-filter: brightness(1);
}
```

When a HDR-capable browser encounters one, it switches to HDR mode. The exact reason for this behavior is not yet known.
