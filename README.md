# virtuous-cycle
To kick off my coding journey in 2019, I developed a simple static site here, deployed on a Mercury server for renting great bicycles (hence, the name).
[virtuous-cycle.zip](https://github.com/claratangfl/virtuous-cycle/files/6993387/virtuous-cycle.zip)

This is done through HTML5 content and CSS presentation, which are kept separate. 
Accessibility guidelines have been followed, especially for media, tables and forms.

On my site are the following web pages linked by a common menu:  
1. An introductory / home page *(index.html)*  
2. A product description page detailing three bicycle options *(product.html)*  
3. A product enquiry page for interested parties to detail their request in a form *(enquire.html)* 
		* All inputs should have labels.  
		* All form values, except the comment textarea are ‘required’ or have a default value (e.g. select, checkbox, radio).  
		* The user should not be able to submit the form if any of these required fields are blank.  
		* The form will have the following form controls:    
			* 1. First name: type text , maximum of 25 characters, alphabetical only  
			2. Last name: type text, maximum of 25 characters, alphabetical only  
			3. Email address: type email
			4. Address (group these inputs with a fieldset and label)
			5. Street address: type text, maximum of 40 characters
			6. Suburb/town: type text, maximum of 20 characters
			7. State: use a select list with options VIC,NSW,QLD,NT,WA,SA,TAS,ACT
			8. Postcode: exactly 4 digits
			9. Phone number: type text, maximum of 10 digit. I've used a placeholder.
			10. Preferred contact: (email, post, phone). I've used radio.
			11. Product - from the range the user wants to enquire about. I've used select.
			12. Product features: use checkboxes
			13. Comment field, for example, allowing the reader to specify particular aspect they are interested in: use textarea, use a placeholder
* A page about me as an individual *(about.html)* 
* A page that lists an enhancement that I tried to implement, with little success *(enhancements.html)* 
* A CSS file that styles my site *(style.css)* across all the pages
