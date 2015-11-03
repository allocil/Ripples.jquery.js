# Ripples.jquery.js
jQuery plugin for adding ripples on buttons when clicked

## Usage

Add jQuery script.
Add ripples.jquery.js script.
Use it `$(element).ripples();`

## Options

###Color
The color of the ripples. Ex: `#ffffff`

###Timing
the time it will take to finish the ripples in seconds. Ex: `0.75`

###Mode
`circle`, `gradient`, `polygon`, `rectangle`

###Callback
The callback function to call on click.

## Example
```	$("button").ripples();
	$("a").ripples({
		"color": "#ffffff",
		"timing": 0.75,
		"mode": "gradient",
		callback: function(){
			$("div.content").append("<p>CLICK</p>");
			return true;
		}
	});```


