# Buttons Lite

Buttons Lite is a trimmed subset of Buttons with only flat (or top level) classes.

## Customize Buttons (Recommended uses Sass & Autoprefixer)
0. Clone the Buttons repository.
0. Make sure you have [node.js](http://nodejs.org/) installed.
0. From the command line cd into the root for the Buttons directory
0. Run ```npm install``` or ```sudo npm install``` (depending on your system permissions).
0. On the command line run ```grunt dev```, this will open a browser with Buttons
0. Locate **scss** in the root directory
0. You can modify the _options.scss where you can customize colors, typography, and …
0. Anytime you save your changes the Buttons showcase page will live reload with your changes!

## Customize Buttons with only Sass or Compass
0. Clone the Buttons repo
0. Make sure you have Sass installed
0. Run `npm install` from your terminal
0. Edit the `_options.scss` with your own custom values (see example values below)
0. Buttons now works with–or without–Compass. So choose one of the following examples accordingly and run from the command line in Buttons's root directory:
  For Sass run: `$ sass --watch --scss scss/buttons.scss:css/buttons.css`
  For Compass run: `$ compass watch`
0. The `css/buttons.css` file should now be updated

## Button Options

To edit Buttons simply change values within the `_options.scss` file. After you make your edits recompile your sass file and your changes will get processed.

* **$ubtn:** This prefix stands for Unicorn Button and prevents namespace collisions that could occur if you import buttons as part of your Sass build process. We kindly ask you not to use the prefix $ubtn in your project in order to avoid possilbe name conflicts. Thanks!
* **$ubtn-namespace:**  Desired CSS namespace for your buttons (default .button)
* **$ubtn-glow-namespace:** Desired CSS namespace for your glow effect (default .glow)
* **$ubtn-colors:** List of colors in format like `(name, background, color)`.
* **$ubtn-glow-color:** Default glow color (#2c9adb, light blue)
* **$ubtn-shapes:** List of shapes in format like `(square 0px)`. You can use Sass maps if you're using 3.3. See `_options.scss` for details.
* **$ubtn-sizes:** List of sizes in format like `(jumbo 1.5)`. You can use Sass maps if you're using 3.3. See `_options.scss` for details.
* **$ubtn-bgcolor:** Default button background color (#EEE, light gray)
* **$ubtn-height:** Default height, also used to calculate padding on the sides (32px)
* **$ubtn-font-family:**  Default font family
* **$ubtn-font-color:** Default font color (#666, gray)
* **$ubtn-font-weight:** Default font weight
* **$ubtn-font-size:** Default font size (14px). You can also specify a value of `inherit` and it will be respected.
