jQuery plugin that makes it easy to drop a phone directly into any webpage with just a few lines of code. 

### Requires:
 * [Phono jQuery Plugin](http://www.phono.com) 
 * Phono API Key. [Get one here](http://www.phono.com) 
 * [jQuery UI Theme](http://jqueryui.com/themeroller/) - *For phone styling*

### Example:
    $("body").append(
		$("<div/>")
	    	.css({"width":"220px"})
	    	.phone({
	    		apiKey: "C17D167F-09C6-4E4C-A3DD-2025D48BA243",
	    		numberToDial: "8007773456",
	    		buttonTextReady: "1-800-FILM (Moviefone)",
	    		slideOpen:true
	    	})
	)
    
### Options:
 * **apiKey**: String, your Phono.com api key. Get one [here](http://http://www.phono.com/)
 * **dialPad**: Boolean, defaults to true. Include a dial pad in the phone
 * **toggleMic**: Boolean, defaults to true. Show a checkbox where users can specify whether or not they are wearing a headset
 * **slideOpen**: Boolean, defaults to true. Slide open the dial pad and mic toggle when the call button is clicked  
 * **buttonText**: String, defaults to "loading...". Text to display in the call button while the phone is loading
 * **buttonTextReady**: String, defaults to "Call me". Text to display in the call button when the phone is ready
 * **numberToDial**: String, defaults to a demo IVR application hosted at [tropo.com](http://www.tropo.com).  
 Set this to the phone number, [Tropo](http://www.tropo.com) appid, or sip number you want to call

### Demo: 
[http://s.phono.com/releases/0.2/samples/phone/index.htm](http://s.phono.com/releases/0.2/samples/phone/index.htm).

### Contact:
[Twitter](http://www.twitter.com/phonosdk)

[http://www.phono.com](http://www.phono.com)