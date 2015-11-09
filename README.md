# CSS Speech Bubble

This is a demo of a responsive speech bubble.

###### index_ver1
The tip is a scalable vector graphic (SVG) positioned in a pseudo element (::after).
The speech bubble works best with a minimum font size of 30px.

###### index_ver2
The tip is a skewed rectangle and works without any SVG. 
But the connection point of the tip and box isn't perfect.

###### index_ver3
Newest version of the speech bubble. The tip is a scalable vector graphic. Its now possible to select the tip direction.
* Usage: 
	* Add the classes "speech-bubble" and "tip-left" / "tip-right" / "tip-none" to your div.
	* The bubble needs a wrapper class to adjust the font-size and positioning.

Example:
```css
<div id="position-bubble">
	<div class="speech-bubble tip-left">Made wiht love!</div>
</div>
```
