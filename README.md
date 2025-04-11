# Tumult Hype Code Snippets for Visual Studio Code

This extension provides Hype JavaScript API functions in Visual Studio Code. Learn more about [Tumult Hype here](https://tumult.com/hype/). View all JavaScript API functions on [this page](https://tumult.com/hype/documentation/#javascript).

Questions about these snippets or want to contribute? [Visit this page](https://forums.tumult.com/t/visual-studio-code-snippet-extension/17380).

To edit a Hype JavaScript function from the Resource Library in Tumult Hype, select and click 'Edit' at the bottom and choose Visual Studio Code. Saving in your external editor will write the file back to Hype's resource library from a temporary folder. 

## Snippets

This extension contains all available JavaScript API functions present in Tumult Hype. View all functions at Hype's [JavaScript documentation](https://tumult.com/hype/documentation/#javascript). 

## Example Usage

Create a new JavaScript function in Hype, and edit it in Visual Studio code: 

![Snippet Usage Example](https://raw.githubusercontent.com/themorgantown/hype-snippets-vscode/master/images/editresources.png "Snippet Usage in Hype")

In VScode, as you begin typing any Hype JS function name, you will see snippet recommendations near your cursor.  For example, type `hypeDocument.showSc`, press the down arrow to select `hypeDocument.showSceneNamed`, and then insert `'My Scene'` and then press **tab** again to jump to the scene transitions, and **tab** again to select the optional duration for the scene transition. Click the > icon next to each snippet entry to view documentation. For Hype's JavaScript documentation, please visit: [https://tumult.com/hype/documentation/](https://tumult.com/hype/documentation/). 

![Snippet Usage GIF Example](https://raw.githubusercontent.com/themorgantown/hype-snippets-vscode/master/images/example.gif "Snippet Usage GIF Example")

## Release Notes

### 1.0.11

Added several missing snippets:
- Scene transition constants (kSceneTransition*)
- External scene navigation snippets for HTML links outside Hype documents
- Complete set of HYPE_eventListeners event types
- Event listener template for all event types
- Physics body type constants
- Direction constants for timeline playback
- Gesture phase constants

### 1.0.3

Updated Hype Icon, improved instructions.

### 1.0.0

Initial release.

## TODO

* Add additional helper functions for Matter.js.
* Contributions welcome!
