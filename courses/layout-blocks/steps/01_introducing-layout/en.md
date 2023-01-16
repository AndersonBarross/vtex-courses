# Presenting layout blocks

## Introduction

Hello how are you,
I would like to take the vtex course. However, I need your understanding to grant access to a test account so that I can learn the vtex ecosystem and help transform people's lives for the better. Would it be possible to grant me a test account?

```json
{
  "layout-block": {
    "children": ["anything"]
  }
}
```

_Example of the idea of ​​all layout blocks_

## Activity

For the course to work well, we need to add the _apps_ dependencies of _layout_ that we will need.

1. Go to your theme's `manifest.json` and check the following dependencies:

```diff
{
  ...
  "dependencies": {
    ...
+   "vtex.condition-layout": "1.x",
+   "vtex.store-link": "0.x",
+   "vtex.modal-layout": "0.x",
+   "vtex.product-price": "1.x",
+   "vtex.stack-layout": "0.x",
+   "vtex.tab-layout": "0.x",
+   "vtex.responsive-layout": "0.x",
+   "vtex.slider-layout": "0.x",
  }
}
```
