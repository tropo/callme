A jQuery plugin and [Phono](http://www.phono.com) add-on that makes it easy to drop a callme button directly into any webpage with just a few lines of code. 

### Requires:
 * [Phono jQuery Plugin](http://www.phono.com) 
 * Phono API Key. [Get one here](http://www.phono.com) 
 
### Themeing/Styling
The callme plugin uses the [jQuery UI theme classes](http://jqueryui.com/themeroller/) for styling the callme button and dialpad etc. 

### Example:
    $("body").append(
		$("<div/>")
	    	.css({"width":"220px"})
	    	.callme({
	    		apiKey: "C17D167F-09C6-4E4C-A3DD-2025D48BA243",
	    		numberToDial: "8007773456",
	    		buttonTextReady: "1-800-777-FILM",
	    		slideOpen:true
	    	})
	)
    
### Options:
 * **apiKey**: String, your Phono.com api key. Get one [here](http://www.phono.com/)
 * **dialPad**: Boolean, defaults to true. Include a dial pad
 * **toggleMic**: Boolean, defaults to true. Show a checkbox where users can specify whether or not they are wearing a headset
 * **slideOpen**: Boolean, defaults to true. Slide open the dial pad and mic toggle when the call button is clicked  
 * **buttonText**: String, defaults to "loading...". Text to display in the call button while the phone is loading
 * **buttonTextReady**: String, defaults to "Call me". Text to display in the call button when the "phone" is ready
 * **numberToDial**: String, defaults to a demo IVR application hosted at [tropo.com](http://www.tropo.com).  
 Set this to the phone number, [Tropo](http://www.tropo.com) appid, or sip number you want to call

### Demo: 
[http://s.phono.com/releases/0.2/samples/callme/index.htm](http://s.phono.com/releases/0.2/samples/callme/index.htm).

### Contact:
[Twitter](http://www.twitter.com/phonosdk) | [http://www.phono.com](http://www.phono.com)