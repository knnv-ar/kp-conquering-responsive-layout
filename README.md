# Kevin Powell's Conquering responsive layouts

## Day 0 | Introduction

### Intro & Why the course is formatted this way

[VIDEO]

### Asking Questions

[VIDEO]

In the video, I mention the #welcome channel, but I've moved where you can add the correct role to gain access.

Once you join with the link below, go to the #😍-reaction-roles channel and click the CRL icon as I show in the video to add the role and gain access to the channels.

Join my Discord community with this link: https://discord.gg/9Rc6WNhNGJ

### My editor and a usefull extension

[VIDEO]

VS Code - https://code.visualstudio.com/

Live Server - https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer

## Day 1 | Using percentage & avoiding heights

### Percentage vs Fixed widths on the parent

[VIDEO]

### Percentage on the child

[VIDEO]

### Why it's a good idea to avoid heights

[VIDEO]

This is a general rule. There are times when you want to use height, but for the most part, they cause more issues than they solve.

It's very rare that I ever use height, and we'll see why in this lesson.

Em vs rem - https://youtu.be/_-aDOAMmDHI

#### Observaciones

La unidad 'rem' siempre tiene que ver con el tamaño de la tipografía en el elemento html{} o en su equivalente :root{}.

Tanto 'rem' como 'em' suelen ser usados en padding, margin, width, height, 

Si utilizamos la unidad 'em', font-size siempre buscar el tamaño de fuente del parent. Para padding y margin, siempre busca el tamaño de fuente de dicho elemento y no de su parent.

Por lo tanto:
- Se recomienda usar 'rem' para determinar el font-size.
- Se recomienda usar 'rem' para determinar el margin así toma siempre referencia fija a 16px.
- Se recomienda usar 'em' para determinar padding y margin ya que tiene sentido tomar su valor de acuerdo al tamaño de fuente (font-size) local.

Para botones se suele usar: `padding: 1em 3em;`

### Challenge #1

[VIDEO]

Here is a challenge to end today's lessons!

### Challenge #1 - Starting Files

[challenge01.zip]

Here are the files you'll need to complete the challenge to finish off today's lesson. Watch the next lesson to get the details on what you need to do.

### Information about the daily drip

As I said in the introduction to the course, this is intentionally set up as a daily drip. 

I occasionally get people asking me to unlock everything at once. With how the course is set up, I cannot do that without it affecting everyone, and for the most part, people enjoy the pacing.

It might seem a little slow at first, especially if you are familiar with some of the concepts I talk about early on, but the pace picks up a little as the course moves on, and this is 100% done on purpose. 

You may feel like you learn more when you can get through a lot of content at once, but it just feels like you are learning a lot.

Take your time, take what you are learning here and apply it to projects, and do the challenges :).

Also, if you *really* want to do a lot at once, once the content is unlocked you have it forever, so you can wait a few days and come back to go through several lessons at once if you really prefer that style of learning.

Enjoy the course!

## Day 2 | Getting familiar with relative units

### Getting familiar with relative units

#### Welcome to day 2 of the course!

There are no video lessons here today. These days are here to give you a chance to keep up if you fall behind, and also to provide some extra learning and resources for those who want to keep pushing.

#### Relative units
While you won't need to dive into relative units to get through this course, I do strongly suggest you learn how em and rem work, as they are essential in CSS today.

I have a [YT video on em and rem units](https://youtu.be/_-aDOAMmDHI), if you aren't already familiar with them, or if you struggle to know which one to use.

I also want to make sure that you completed the challenge. I'll be looking at the solution tomorrow, but I want to make sure you did it first, and this one shouldn't take you very long, so there are no excuses!

The easiest thing to do for them is to create a [CodePen](https://codepen.io/) or [JSFiddle](https://jsfiddle.net/).

In CodePen, you can super easily get started by dragging the challenge files right into the browser window!

![animation](./day-02/day02-1.gif)

If you see a challenge and say "that's too easy!" make sure you actually do it anyway. It'll reinforce what was covered, and it's all building up skills we'll need to complete later challenges and help you conquer responsive layouts.

### CSS em and rem explained

https://youtu.be/_-aDOAMmDHI

### Why you shouldn't set font-sizes using em

https://youtu.be/pautqDqa54I

---
## Postdata

Video files in m3u8 format

Example: https://fast.wistia.com/embed/medias/3r8rhc2x27.m3u8

```m3u8
#EXTM3U
#EXT-X-VERSION:3
#EXT-X-MEDIA:TYPE=SUBTITLES,GROUP-ID="subtitles",NAME="English",AUTOSELECT=NO,DEFAULT=NO,FORCED=NO,LANGUAGE="eng",CHARACTERISTICS="public.accessibility.transcribes-spoken-dialog,public.accessibility.describes-music-and-sound",URI="https://fast.wistia.net/embed/captions/3r8rhc2x27.m3u8?language=eng"

#EXT-X-STREAM-INF:AVERAGE_BANDWIDTH=405061,BANDWIDTH=487295,RESOLUTION=1920x1080,NAME=1080p,SUBTITLES="subtitles"
https://embed-cloudfront.wistia.com/deliveries/f5a15083195563be45390266c5137048c18b6a70.m3u8
#EXT-X-STREAM-INF:AVERAGE_BANDWIDTH=32672,BANDWIDTH=42091,RESOLUTION=400x224,NAME=224p,SUBTITLES="subtitles"
https://embed-cloudfront.wistia.com/deliveries/294a81fed810a6227a27e459a11a301162baf4a8.m3u8
#EXT-X-STREAM-INF:AVERAGE_BANDWIDTH=56134,BANDWIDTH=75017,RESOLUTION=640x360,NAME=360p,SUBTITLES="subtitles"
https://embed-cloudfront.wistia.com/deliveries/a99160907779288b7761cf36acd256108b0a8c12.m3u8
#EXT-X-STREAM-INF:AVERAGE_BANDWIDTH=96090,BANDWIDTH=132400,RESOLUTION=960x540,NAME=540p,SUBTITLES="subtitles"
https://embed-cloudfront.wistia.com/deliveries/47ccabbc83e2a7308aae9e5aca292a8866fae3d5.m3u8
#EXT-X-STREAM-INF:AVERAGE_BANDWIDTH=150893,BANDWIDTH=204181,RESOLUTION=1280x720,NAME=720p,SUBTITLES="subtitles"
https://embed-cloudfront.wistia.com/deliveries/011f7110b9520aa8310bd2b3e4a6059261f0dbdc.m3u8
```

mpeg ts

video.ts to mp4

---
## The 140 HTML Color Names

Basado en https://htmlcolorcodes.com/color-names/

### Red HTML Color Names

| Color | Name | Hex Code | RGB Code |
|-------|------|----------|----------|
|<div style="width: 32px; height: 10px; background-color: indianred;"></div>| IndianRed | #CD5C5C | rgb(205, 92, 92) |
| <div style="width: 32px; height: 10px; background-color: #F08080;"></div> | LightCoral | #F08080 | rgb(240, 128, 128) |
| <div style="width: 32px; height: 10px; background-color: #FA8072;"></div> | Salmon | #FA8072 | rgb(250, 128, 114) |
| <div style="width: 32px; height: 10px; background-color: #E9967A;"></div> | DarkSalmon | #E9967A | rgb(233, 150, 122) |
| <div style="width: 32px; height: 10px; background-color: #FFA07A;"></div> | LightSalmon | #FFA07A | rgb(255, 160, 122) |
| <div style="width: 32px; height: 10px; background-color: #DC143C;"></div> | Crimson | #DC143C | rgb(220, 20, 60) |
| <div style="width: 32px; height: 10px; background-color: #FF0000;"></div> | Red | #FF0000 | rgb(255, 0, 0) |
| <div style="width: 32px; height: 10px; background-color: #B22222;"></div> | FireBrick | #B22222 | rgb(178, 34, 34) |
| <div style="width: 32px; height: 10px; background-color: #8B0000;"></div> | DarkRed | #8B0000 | rgb(139, 0, 0) |

### Pink HTML Color Names

| Color | Name | Hex Code | RGB Code |
|-------|------|----------|----------|
| <div style="width: 32px; height: 10px; background-color: #FFC0CB;"></div> | Pink | #FFC0CB | rgb(255, 192, 203) |
| <div style="width: 32px; height: 10px; background-color: #FFB6C1;"></div> | LightPink | #FFB6C1 | rgb(255, 182, 193) |
| <div style="width: 32px; height: 10px; background-color: #FF69B4;"></div> | HotPink | #FF69B4 | rgb(255, 105, 180) |
| <div style="width: 32px; height: 10px; background-color: #FF1493;"></div> | DeepPink | #FF1493 | rgb(255, 20, 147) |
| <div style="width: 32px; height: 10px; background-color: #C71585;"></div> | MediumVioletRed | #C71585 | rgb(199, 21, 133) |
| <div style="width: 32px; height: 10px; background-color: #DB7093;"></div> | PaleVioletRed | #DB7093 | rgb(219, 112, 147) |

### Orange HTML Color Names

| Color | Name | Hex Code | RGB Code |
|-------|------|----------|----------|
| <div style="width: 32px; height: 10px; background-color: #FFA07A;"></div> | LightSalmon | #FFA07A | rgb(255, 160, 122) |
| <div style="width: 32px; height: 10px; background-color: #FF7F50;"></div> | Coral | #FF7F50 | rgb(255, 127, 80) |
| <div style="width: 32px; height: 10px; background-color: #FF6347;"></div> | Tomato | #FF6347 | rgb(255, 99, 71) |
| <div style="width: 32px; height: 10px; background-color: #FF4500;"></div> | OrangeRed | #FF4500 | rgb(255, 69, 0) |
| <div style="width: 32px; height: 10px; background-color: #FF8C00;"></div> | DarkOrange | #FF8C00 | rgb(255, 140, 0) |
| <div style="width: 32px; height: 10px; background-color: #FFA500;"></div> | Orange | #FFA500 | rgb(255, 165, 0) |

### Yellow HTML Color Names

| Color | Name | Hex Code | RGB Code |
|-------|------|----------|----------|
| <div style="width: 32px; height: 10px; background-color: #FFD700;"></div> | Gold | #FFD700 | rgb(255, 215, 0) |
| <div style="width: 32px; height: 10px; background-color: #FFFF00;"></div> | Yellow | #FFFF00 | rgb(255, 255, 0) |
| <div style="width: 32px; height: 10px; background-color: #FFFFE0;"></div> | LightYellow | #FFFFE0 | rgb(255, 255, 224) |
| <div style="width: 32px; height: 10px; background-color: #FFFACD;"></div> | LemonChiffon | #FFFACD | rgb(255, 250, 205) |
| <div style="width: 32px; height: 10px; background-color: #FAFAD2;"></div> | LightGoldenrodYellow | #FAFAD2 | rgb(250, 250, 210) |
| <div style="width: 32px; height: 10px; background-color: #FFEFD5;"></div> | PapayaWhip | #FFEFD5 | rgb(255, 239, 213) |
| <div style="width: 32px; height: 10px; background-color: #FFE4B5;"></div> | Moccasin | #FFE4B5 | rgb(255, 228, 181) |
| <div style="width: 32px; height: 10px; background-color: #FFDAB9;"></div> | PeachPuff | #FFDAB9 | rgb(255, 218, 185) |
| <div style="width: 32px; height: 10px; background-color: #EEE8AA;"></div> | PaleGoldenrod | #EEE8AA | rgb(238, 232, 170) |
| <div style="width: 32px; height: 10px; background-color: #F0E68C;"></div> | Khaki | #F0E68C | rgb(240, 230, 140) |
| <div style="width: 32px; height: 10px; background-color: #BDB76B;"></div> | DarkKhaki | #BDB76B | rgb(189, 183, 107) |

### Purple HTML Color Names

| Color | Name | Hex Code | RGB Code |
|-------|------|----------|----------|
| <div style="width: 32px; height: 10px; background-color: #E6E6FA;"></div> | Lavender | #E6E6FA | rgb(230, 230, 250) |
| <div style="width: 32px; height: 10px; background-color: #D8BFD8;"></div> | Thistle | #D8BFD8 | rgb(216, 191, 216) |
| <div style="width: 32px; height: 10px; background-color: #DDA0DD;"></div> | Plum | #DDA0DD | rgb(221, 160, 221) |
| <div style="width: 32px; height: 10px; background-color: #EE82EE;"></div> | Violet | #EE82EE | rgb(238, 130, 238) |
| <div style="width: 32px; height: 10px; background-color: #DA70D6;"></div> | Orchid | #DA70D6 | rgb(218, 112, 214) |
| <div style="width: 32px; height: 10px; background-color: #FF00FF;"></div> | Fuchsia | #FF00FF | rgb(255, 0, 255) |
| <div style="width: 32px; height: 10px; background-color: #FF00FF;"></div> | Magenta | #FF00FF | rgb(255, 0, 255) |
| <div style="width: 32px; height: 10px; background-color: #BA55D3;"></div> | MediumOrchid | #BA55D3 | rgb(186, 85, 211) |
| <div style="width: 32px; height: 10px; background-color: #9370DB;"></div> | MediumPurple | #9370DB | rgb(147, 112, 219) |
| <div style="width: 32px; height: 10px; background-color: #8A2BE2;"></div> | BlueViolet | #8A2BE2 | rgb(138, 43, 226) |
| <div style="width: 32px; height: 10px; background-color: #9400D3;"></div> | DarkViolet | #9400D3 | rgb(148, 0, 211) |
| <div style="width: 32px; height: 10px; background-color: #9932CC;"></div> | DarkOrchid | #9932CC | rgb(153, 50, 204) |
| <div style="width: 32px; height: 10px; background-color: #8B008B;"></div> | DarkMagenta | #8B008B | rgb(139, 0, 139) |
| <div style="width: 32px; height: 10px; background-color: #800080;"></div> | Purple | #800080 | rgb(128, 0, 128) |
| <div style="width: 32px; height: 10px; background-color: #4B0082;"></div> | Indigo | #4B0082 | rgb(75, 0, 130) |
| <div style="width: 32px; height: 10px; background-color: #483D8B;"></div> | DarkSlateBlue | #483D8B | rgb(72, 61, 139) |
| <div style="width: 32px; height: 10px; background-color: #6A5ACD;"></div> | SlateBlue | #6A5ACD | rgb(106, 90, 205) |
| <div style="width: 32px; height: 10px; background-color: #7B68EE;"></div> | MediumSlateBlue | #7B68EE | rgb(123, 104, 238) |

### Green HTML Color Names

| Color | Name | Hex Code | RGB Code |
|-------|------|----------|----------|
| <div style="width: 32px; height: 10px; background-color: #ADFF2F;"></div> | GreenYellow | #ADFF2F | rgb(173, 255, 47) |
| <div style="width: 32px; height: 10px; background-color: #7FFF00;"></div> | Chartreuse | #7FFF00 | rgb(127, 255, 0) |
| <div style="width: 32px; height: 10px; background-color: #7CFC00;"></div> | LawnGreen | #7CFC00 | rgb(124, 252, 0) |
| <div style="width: 32px; height: 10px; background-color: #00FF00;"></div> | Lime | #00FF00 | rgb(0, 255, 0) |
| <div style="width: 32px; height: 10px; background-color: #32CD32;"></div> | LimeGreen | #32CD32 | rgb(50, 205, 50) |
| <div style="width: 32px; height: 10px; background-color: #98FB98;"></div> | PaleGreen | #98FB98 | rgb(152, 251, 152) |
| <div style="width: 32px; height: 10px; background-color: #90EE90;"></div> | LightGreen | #90EE90 | rgb(144, 238, 144) |
| <div style="width: 32px; height: 10px; background-color: #00FA9A;"></div> | MediumSpringGreen | #00FA9A | rgb(0, 250, 154) |
| <div style="width: 32px; height: 10px; background-color: #00FF7F;"></div> | SpringGreen | #00FF7F | rgb(0, 255, 127) |
| <div style="width: 32px; height: 10px; background-color: #3CB371;"></div> | MediumSeaGreen | #3CB371 | rgb(60, 179, 113) |
| <div style="width: 32px; height: 10px; background-color: #2E8B57;"></div> | SeaGreen | #2E8B57 | rgb(46, 139, 87) |
| <div style="width: 32px; height: 10px; background-color: #228B22;"></div> | ForestGreen | #228B22 | rgb(34, 139, 34) |
| <div style="width: 32px; height: 10px; background-color: #008000;"></div> | Green | #008000 | rgb(0, 128, 0) |
| <div style="width: 32px; height: 10px; background-color: #006400;"></div> | DarkGreen | #006400 | rgb(0, 100, 0) |
| <div style="width: 32px; height: 10px; background-color: #9ACD32;"></div> | YellowGreen | #9ACD32 | rgb(154, 205, 50) |
| <div style="width: 32px; height: 10px; background-color: #6B8E23;"></div> | OliveDrab | #6B8E23 | rgb(107, 142, 35) |
| <div style="width: 32px; height: 10px; background-color: #808000;"></div> | Olive | #808000 | rgb(128, 128, 0) |
| <div style="width: 32px; height: 10px; background-color: #556B2F;"></div> | DarkOliveGreen | #556B2F | rgb(85, 107, 47) |
| <div style="width: 32px; height: 10px; background-color: #66CDAA;"></div> | MediumAquamarine | #66CDAA | rgb(102, 205, 170) |
| <div style="width: 32px; height: 10px; background-color: #8FBC8B;"></div> | DarkSeaGreen | #8FBC8B | rgb(143, 188, 139) |
| <div style="width: 32px; height: 10px; background-color: #20B2AA;"></div> | LightSeaGreen | #20B2AA | rgb(32, 178, 170) |
| <div style="width: 32px; height: 10px; background-color: #008B8B;"></div> | DarkCyan | #008B8B | rgb(0, 139, 139) |
| <div style="width: 32px; height: 10px; background-color: #008080;"></div> | Teal | #008080 | rgb(0, 128, 128) |

### Blue HTML Color Names

| Color | Name | Hex Code | RGB Code |
|-------|------|----------|----------|
| <div style="width: 32px; height: 10px; background-color: #00FFFF;"></div> | Aqua | #00FFFF | rgb(0, 255, 255) |
| <div style="width: 32px; height: 10px; background-color: #00FFFF;"></div> | Cyan | #00FFFF | rgb(0, 255, 255) |
| <div style="width: 32px; height: 10px; background-color: #E0FFFF;"></div> | LightCyan | #E0FFFF | rgb(224, 255, 255) |
| <div style="width: 32px; height: 10px; background-color: #AFEEEE;"></div> | PaleTurquoise | #AFEEEE | rgb(175, 238, 238) |
| <div style="width: 32px; height: 10px; background-color: #7FFFD4;"></div> | Aquamarine | #7FFFD4 | rgb(127, 255, 212) |
| <div style="width: 32px; height: 10px; background-color: #40E0D0;"></div> | Turquoise | #40E0D0 | rgb(64, 224, 208) |
| <div style="width: 32px; height: 10px; background-color: #48D1CC;"></div> | MediumTurquoise | #48D1CC | rgb(72, 209, 204) |
| <div style="width: 32px; height: 10px; background-color: #00CED1;"></div> | DarkTurquoise | #00CED1 | rgb(0, 206, 209) |
| <div style="width: 32px; height: 10px; background-color: #5F9EA0;"></div> | CadetBlue | #5F9EA0 | rgb(95, 158, 160) |
| <div style="width: 32px; height: 10px; background-color: #4682B4;"></div> | SteelBlue | #4682B4 | rgb(70, 130, 180) |
| <div style="width: 32px; height: 10px; background-color: #B0C4DE;"></div> | LightSteelBlue | #B0C4DE | rgb(176, 196, 222) |
| <div style="width: 32px; height: 10px; background-color: #B0E0E6;"></div> | PowderBlue | #B0E0E6 | rgb(176, 224, 230) |
| <div style="width: 32px; height: 10px; background-color: #ADD8E6;"></div> | LightBlue | #ADD8E6 | rgb(173, 216, 230) |
| <div style="width: 32px; height: 10px; background-color: #87CEEB;"></div> | SkyBlue | #87CEEB | rgb(135, 206, 235) |
| <div style="width: 32px; height: 10px; background-color: #87CEFA;"></div> | LightSkyBlue | #87CEFA | rgb(135, 206, 250) |
| <div style="width: 32px; height: 10px; background-color: #00BFFF;"></div> | DeepSkyBlue | #00BFFF | rgb(0, 191, 255) |
| <div style="width: 32px; height: 10px; background-color: #1E90FF;"></div> | DodgerBlue | #1E90FF | rgb(30, 144, 255) |
| <div style="width: 32px; height: 10px; background-color: #6495ED;"></div> | CornflowerBlue | #6495ED | rgb(100, 149, 237) |
| <div style="width: 32px; height: 10px; background-color: #7B68EE;"></div> | MediumSlateBlue | #7B68EE | rgb(123, 104, 238) |
| <div style="width: 32px; height: 10px; background-color: #4169E1;"></div> | RoyalBlue | #4169E1 | rgb(65, 105, 225) |
| <div style="width: 32px; height: 10px; background-color: #0000FF;"></div> | Blue | #0000FF | rgb(0, 0, 255) |
| <div style="width: 32px; height: 10px; background-color: #0000CD;"></div> | MediumBlue | #0000CD | rgb(0, 0, 205) |
| <div style="width: 32px; height: 10px; background-color: #00008B;"></div> | DarkBlue | #00008B | rgb(0, 0, 139) |
| <div style="width: 32px; height: 10px; background-color: #000080;"></div> | Navy | #000080 | rgb(0, 0, 128) |
| <div style="width: 32px; height: 10px; background-color: #191970;"></div> | MidnightBlue | #191970 | rgb(25, 25, 112) |

### Brown HTML Color Names

| Color | Name | Hex Code | RGB Code |
|-------|------|----------|----------|
| <div style="width: 32px; height: 10px; background-color: #FFF8DC;"></div> | Cornsilk | #FFF8DC | rgb(255, 248, 220) |
| <div style="width: 32px; height: 10px; background-color: #FFEBCD;"></div> | BlanchedAlmond | #FFEBCD | rgb(255, 235, 205) |
| <div style="width: 32px; height: 10px; background-color: #FFE4C4;"></div> | Bisque | #FFE4C4 | rgb(255, 228, 196) |
| <div style="width: 32px; height: 10px; background-color: #FFDEAD;"></div> | NavajoWhite | #FFDEAD | rgb(255, 222, 173) |
| <div style="width: 32px; height: 10px; background-color: #F5DEB3;"></div> | Wheat | #F5DEB3 | rgb(245, 222, 179) |
| <div style="width: 32px; height: 10px; background-color: #DEB887;"></div> | BurlyWood | #DEB887 | rgb(222, 184, 135) |
| <div style="width: 32px; height: 10px; background-color: #D2B48C;"></div> | Tan | #D2B48C | rgb(210, 180, 140) |
| <div style="width: 32px; height: 10px; background-color: #BC8F8F;"></div> | RosyBrown | #BC8F8F | rgb(188, 143, 143) |
| <div style="width: 32px; height: 10px; background-color: #F4A460;"></div> | SandyBrown | #F4A460 | rgb(244, 164, 96) |
| <div style="width: 32px; height: 10px; background-color: #DAA520;"></div> | Goldenrod | #DAA520 | rgb(218, 165, 32) |
| <div style="width: 32px; height: 10px; background-color: #B8860B;"></div> | DarkGoldenrod | #B8860B | rgb(184, 134, 11) |
| <div style="width: 32px; height: 10px; background-color: #CD853F;"></div> | Peru | #CD853F | rgb(205, 133, 63) |
| <div style="width: 32px; height: 10px; background-color: #D2691E;"></div> | Chocolate | #D2691E | rgb(210, 105, 30) |
| <div style="width: 32px; height: 10px; background-color: #8B4513;"></div> | SaddleBrown | #8B4513 | rgb(139, 69, 19) |
| <div style="width: 32px; height: 10px; background-color: #A0522D;"></div> | Sienna | #A0522D | rgb(160, 82, 45) |
| <div style="width: 32px; height: 10px; background-color: #A52A2A;"></div> | Brown | #A52A2A | rgb(165, 42, 42) |
| <div style="width: 32px; height: 10px; background-color: #800000;"></div> | Maroon | #800000 | rgb(128, 0, 0) |

### White HTML Color Names

| Color | Name | Hex Code | RGB Code |
|-------|------|----------|----------|
| <div style="width: 32px; height: 10px; background-color: #FFFFFF;"></div> | White | #FFFFFF | rgb(255, 255, 255) |
| <div style="width: 32px; height: 10px; background-color: #FFFAFA;"></div> | Snow | #FFFAFA | rgb(255, 250, 250) |
| <div style="width: 32px; height: 10px; background-color: #F0FFF0;"></div> | HoneyDew | #F0FFF0 | rgb(240, 255, 240) |
| <div style="width: 32px; height: 10px; background-color: #F5FFFA;"></div> | MintCream | #F5FFFA | rgb(245, 255, 250) |
| <div style="width: 32px; height: 10px; background-color: #F0FFFF;"></div> | Azure | #F0FFFF | rgb(240, 255, 255) |
| <div style="width: 32px; height: 10px; background-color: #F0F8FF;"></div> | AliceBlue | #F0F8FF | rgb(240, 248, 255) |
| <div style="width: 32px; height: 10px; background-color: #F8F8FF;"></div> | GhostWhite | #F8F8FF | rgb(248, 248, 255) |
| <div style="width: 32px; height: 10px; background-color: #F5F5F5;"></div> | WhiteSmoke | #F5F5F5 | rgb(245, 245, 245) |
| <div style="width: 32px; height: 10px; background-color: #FFF5EE;"></div> | SeaShell | #FFF5EE | rgb(255, 245, 238) |
| <div style="width: 32px; height: 10px; background-color: #F5F5DC;"></div> | Beige | #F5F5DC | rgb(245, 245, 220) |
| <div style="width: 32px; height: 10px; background-color: #FDF5E6;"></div> | OldLace | #FDF5E6 | rgb(253, 245, 230) |
| <div style="width: 32px; height: 10px; background-color: #FFFAF0;"></div> | FloralWhite | #FFFAF0 | rgb(255, 250, 240) |
| <div style="width: 32px; height: 10px; background-color: #FFFFF0;"></div> | Ivory | #FFFFF0 | rgb(255, 255, 240) |
| <div style="width: 32px; height: 10px; background-color: #FAEBD7;"></div> | AntiqueWhite | #FAEBD7 | rgb(250, 235, 215) |
| <div style="width: 32px; height: 10px; background-color: #FAF0E6;"></div> | Linen | #FAF0E6 | rgb(250, 240, 230) |
| <div style="width: 32px; height: 10px; background-color: #FFF0F5;"></div> | LavenderBlush | #FFF0F5 | rgb(255, 240, 245) |
| <div style="width: 32px; height: 10px; background-color: #FFE4E1;"></div> | MistyRose | #FFE4E1 | rgb(255, 228, 225) |

### Gray HTML Color Names

| Color | Name | Hex Code | RGB Code |
|-------|------|----------|----------|
| <div style="width: 32px; height: 10px; background-color: #DCDCDC;"></div> | Gainsboro | #DCDCDC | rgb(220, 220, 220) |
| <div style="width: 32px; height: 10px; background-color: #D3D3D3;"></div> | LightGray | #D3D3D3 | rgb(211, 211, 211) |
| <div style="width: 32px; height: 10px; background-color: #C0C0C0;"></div> | Silver | #C0C0C0 | rgb(192, 192, 192) |
| <div style="width: 32px; height: 10px; background-color: #A9A9A9;"></div> | DarkGray | #A9A9A9 | rgb(169, 169, 169) |
| <div style="width: 32px; height: 10px; background-color: #808080;"></div> | Gray | #808080 | rgb(128, 128, 128) |
| <div style="width: 32px; height: 10px; background-color: #696969;"></div> | DimGray | #696969 | rgb(105, 105, 105) |
| <div style="width: 32px; height: 10px; background-color: #778899;"></div> | LightSlateGray | #778899 | rgb(119, 136, 153) |
| <div style="width: 32px; height: 10px; background-color: #708090;"></div> | SlateGray | #708090 | rgb(112, 128, 144) |
| <div style="width: 32px; height: 10px; background-color: #2F4F4F;"></div> | DarkSlateGray | #2F4F4F | rgb(47, 79, 79) |
| <div style="width: 32px; height: 10px; background-color: #000000;"></div> | Black | #000000 | rgb(0, 0, 0) |
