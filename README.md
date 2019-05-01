#AMP HTML

**Requirements:**

	* start with the doctype <!doctype html>. 
	* contain a top-level <html ⚡> tag (<html amp> is accepted as well). 
	* contain <head> and <body> tags (They are optional in HTML). 
	* contain a <link rel="canonical" href="$SOME_URL"> tag inside their head that points to the regular HTML version of the AMP HTML document or to itself if no such HTML version exists. 
	* contain a <meta charset="utf-8"> tag as the first child of their head tag. 
	* contain a <meta name="viewport" content="width=device-width"> tag inside their head tag. It's also recommended to include minimum-scale=1 and initial-scale=1. 
	* contain a <script async src="https://cdn.ampproject.org/v0.js"></script> tag inside their head tag. 
	* contain the AMP boilerplate code (head > style[amp-boilerplate] and noscript > style[amp-boilerplate]) in their head tag. 

**Links:**  
https://amp.dev/documentation/guides-and-tutorials/learn/spec/amphtml?referrer=ampproject.org#required-markup
https://css-tricks.com/taking-amp-for-a-spin/

**Test Link**  
https://search.google.com/test/amp?id=nYfFWttJubwJEHlfY-lgIQ
