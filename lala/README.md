# LaLa
A collection of random useful (probably) javascript classes and functions. No it wasn't named after Lala Satalin Deviluke (or it probably was, idk).
### Edit Initial
The only class currently is `Time` tho. And it's not really a Time class but rather a time object class. What's the difference? I don't know but the latter sounds more fitting for some reason. But I don't wanna rename `Time` into `TimeObj` or `TimeObject` since those are longer names and shorter names are more efficient (in being lazy yes).

### Edit 08-01-2022
* Ok now we have the `Collection` class that's just map but probably better. Maps are still smaller tho.
* Added `Gacha` class. Kinda complicated but works  ( ⓛ ω ⓛ )

### Edit 25-01-2022
* Added a random string generator. Generates a random string. Accepts a `length` parameter. 
* Added a random name generator which works the same as the string generator. Names do be weird tho.

### Edit 26-01-2022
* Added a random email generator. Accepts a `common` parameter which can be `true` or `false`. Setting to `true` uses a common email provider name instead of randomly generating one.
* Added a monster name generator. Basically the name generator but with a suffix.
* Added a chain mail generator. Kinda funni.
* Added a story generator which generates a fantasy plot with a mc and a villain.

### How to use?
Clone this repo inside your project directory and access it through index.js.

Open the command line in your project's directory.

```bash
$ git clone https://github.com/retraigo/lala
```

You can access everything with

```js
const lala = require("./lala")
```

as long as you don't have an existing file or folder named `lala`.

When you wish to update the code, just do a `git pull` inside the `lala` directory periodically.

### There's too many useless files in the repo. How do I reduce the size?
We use this magic called `copy/paste`. Copy whatever code you need and paste it directly into your project.

### Credits
Me. If you wanna credit me and you used the `copy/paste` method, leave a comment in the part of my code you used. Something like,

```js
/* 
  From retraigo/lala
*/
```