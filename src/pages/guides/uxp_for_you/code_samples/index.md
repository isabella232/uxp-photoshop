# Code Samples

Here are some examples of plugins you can create with UXP in Photoshop. On GitHub, they exist as fully formed projects that you can load immediately to get a flavor for how things work; then you can modify the projects so they become more your own code.

The samples are all available on GitHub [here](#) where you can clone or fork them. If you're not familiar with GitHub and just want to download the examples, click on the link above and just click the green `Code` button, then click "Download ZIP."

## Samples

These samples come in two flavors: one uses plain JavaScript with no extra frameworks, while the other uses the [React](https://reactjs.org) JavaScript framework. If you've never used React, definitely start with the vanilla JavaScript samples.

The React versions support richer, more complex user interactions, but contain code that will be foreign to you if you've never used React. The packaging of a React-based plugin is also more complex than one using plain JavaScript, due to the dependencies React requires.

If you're writing a plugin with a complex UI (for example, a UI that changes depending upon what item in a listbox is selected, or a UI that changes based on the user's selection in Photoshop), you probably want to use React.

There's also a [JavaScript example](#) that provides no UI ("headless"). If you want to create a plugin that does the same thing each time without any user input, or gets its parameters some other way (say, a configuration file or a website), this might be the way to go.

### Hello, world dialog
In the spirit of the gold standard for trivial examples since the publication of *The C Programming Language* book in 1978 (and [earlier](https://www.thesoftwareguild.com/blog/the-history-of-hello-world/)), this plugin example does nothing but display a dialog box. But it gives you the idea of the structure of simple plugins that use only pure JavaScript (no HTML or CSS).

### Hello, world panel
This is a variant on the plugin above that displays nothing but a panel with a button. When the button is clicked, the plugin displays a dialog. This plugin shows how you use an index.html file, some basic CSS, and how to capture UI events to trigger plugin actions.

### Layer creation and population
This panel-based plugin lets you type text into an input field, then press a button to create a layer containing that text. It also allows you to read the text from a file. This shows input field processing, file I/O, and some debugging techniques.

### Layer modification and export
Operations on layers are very common in most Photoshop workflows. This sample shows how to modify the contents of a selected layer, then export that layer to a file.

### Get data from a web service and place it on a layer
This plugin demonstrates the common use case of needing to talk to an external website (using `fetch`) to obtain some information that's then used in the document. [NOTE: LOOK AT XD DOCS FOR THIS]

### React example
[React](https://reactjs.org) is a very popular modern JavaScript framework. UXP plugins can be built using React to enable complex UIs which would otherwise require complex and difficult-to-maintain JavaScript.

If you've never used React, one of the best places to start is with the (React Tutorial)[https://reactjs.org/tutorial/tutorial.html].

### Theme awareness
The Photoshop UI supports multiple "themes," and you use CSS selectors to change the way your UI looks depending upon what the user picks in Photoshop preferences->Interface.

### Other contenders
 * Make grid of hexagons or other polygons
 * OAuth?