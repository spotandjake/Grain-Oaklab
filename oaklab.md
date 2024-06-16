---
title: OakLab
---

A library for working with the [OakLab color space](https://bottosson.github.io/posts/oklab/)

## Values

Functions and constants included in the OakLab module.

### OakLab.**linearize**

```grain
linearize : (x: Number) => Number
```

### OakLab.**delinearize**

```grain
delinearize : (x: Number) => Number
```

### OakLab.**oklab2rgb**

```grain
oklab2rgb : (l: Number, a: Number, b: Number) => List<Number>
```

Converts the OakLab color space to RGB

Parameters:

|param|type|description|
|-----|----|-----------|
|`l`|`Number`|The colors perceived lightness|
|`a`|`Number`|The colors position between red and green|
|`b`|`Number`|The colors position between yellow and blue|

Returns:

|type|description|
|----|-----------|
|`List<Number>`|The RGB values|

### OakLab.**rgb2oklab**

```grain
rgb2oklab : (r: Number, g: Number, b: Number) => Array<Number>
```

Converts the RGB color space to OakLab

Parameters:

|param|type|description|
|-----|----|-----------|
|`r`|`Number`|The amount of red|
|`g`|`Number`|The amount of green|
|`b`|`Number`|The amount of blue|

Returns:

|type|description|
|----|-----------|
|`Array<Number>`|The OakLab values|

