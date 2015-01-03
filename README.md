| Device | Points | Pixel Resolution | Identifier(s) | Naming Example
|--------|--------|------------------|---------------|---------------
| iPhone Classic, 3G, 3GS<br>iPod Touch 1<sup>st</sup> - 3<sup>rd</sup> Gen. | 320 x 480 | 320 x 480 | N/A | `example.png`
| iPhone 4, 4S<br>iPod 4<sup>th</sup> Gen. | 320 x 480 | 640px x 960px | @2x | `example@2x.png`
| iPhone 5, 5C, 5S<br>iPod 5<sup>th</sup> Gen. | 320 x 568 | 640px x 1136px | @2x, -568h | `example-568h@2x.png`
| iPhone 6 | 375 x 667 | 750px x 1334px | @2x, -667h | `example-667h@2x.png`
| iPhone 6 Plus | 414 x 736 | 1242px x 2208px | @3x | `example@3x.png`
| iPad 1, 2<br>iPad Mini | 768 x 1024 | 768px x 1024px | ~ipad | `example~ipad.png`
| iPad 3, 4, Air, Air 2<br>iPad Mini 2, 3 | 768 x 1024 | 1536px x 2048px | @2x, ~ipad | `example@2x~ipad.png`

Unless you are specifically wanting to target the iPhone 5 or 6 families, simply use `@2x`. The `-xxxh` suffixes are primarily used for launch images.

Data pulled from the following sources:
- [Designing Content for the Whole iOS Family](https://www.codeandweb.com/blog/2012/12/14/scaling-content-for-retina-display-iphone-and-ipad)
- [Preparing for the new iPhone 6 and iPhone 6 Plus Screen Sizes](http://www.reigndesign.com/blog/preparing-for-the-new-iphone-6-and-iphone-6-plus-screen-sizes/)
