# Day_03-Task1]. For the given JSON iterate over all for loop (for, for in, for of, forEach)


2]. Create your own resume data in JSON format
	let text = '{
		"student": [
			{ "firstName":"Preethi", "lastName": "Rathinam", "email": "abc@gmai.com", "age": "28", "education":"MBA", "job": "business analyst"}	]}';
			
			const obj = JSON.parse(text);

3]. Window, Screen and Document in Javascript

		Screen object contains information about visitor's screen
		
		Window.screen can be written without prefix
		
		Properties : 
		 	screen.width
		 	screen.height
		 	screen.availWidth
		 	screen.availHeight
		 	screen.colorDepth
		 	screen.pixelDepth
		
		Window Object :

	The window object is the topmost object of the DOM hierarchy. 
	The Window object is the JavaScript Global object.
	The window object represents the browser window or frame that displays the contents of the webpage.  
	It is the very first object that is loaded in the browser.
	
			Synntax : window.property_name;
			
			Methods of window Syntax: window.method_name;
			
			Methods in window elements that are commonly used are 
			
			alert(): It is used to display an alert box. It displays a specified message along with an OK button and used to make sure that the information comes through the user.
			close(): It is used for closing a certain window or tab of the browser which was previously opened.
			focus(): It is used to give focus to an element in the current window.
			open(): It is used to open a new tab or window with the specified URL and name.
			
	Document object :

	The document object represent a web page that is loaded in the browser.
	The document object can be accessed with a 
						window.document
	It is loaded inside the window.
	By accessing the document object, we can can access the element in the HTML page.
	The document object is a property of the window object.

			Syntax : document =.property_name;
		
