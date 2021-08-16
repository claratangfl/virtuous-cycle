# virtuous-cycle
To kick off my coding journey, I developed a simple static site here, deployed on a Mercury server for renting great bicycles (hence, the name).
[virtuous-cycle.zip](https://github.com/claratangfl/virtuous-cycle/files/6993387/virtuous-cycle.zip)
This is done through HTML5 content and CSS presentation, which are kept separate. 
Accessibility guidelines have been followed, especially for media, tables and forms.

On my site are the following web pages linked by a common menu: 
* An introductory / home page *(index.html)* 
* A product description page detailing three bicycle options *(product.html)*
* A product enquiry page for interested parties to detail their request in a form *(enquire.html)* 
		* All inputs should have labels. All form values, except the comment textarea are ‘required’ or have a default value (e.g. select, checkbox, radio). The user should not be able 				to submit the form if any of these required fields are blank.
		* The form will have the following form controls:
						a. First name: type text , maximum of 25 characters, alphabetical only
						b. Last name: type text, maximum of 25 characters, alphabetical only
						c. Email address: type email
						d. Address (group these inputs with a fieldset and label)
						i. Street address: type text, maximum of 40 characters
						ii. Suburb/town: type text, maximum of 20 characters
						iii. State: use a select list with options VIC,NSW,QLD,NT,WA,SA,TAS,ACT
						iv. Postcode: exactly 4 digits
						e. Phone number: type text, maximum of 10 digit. Use a placeholder
						f. Preferred contact: (email, post, phone). use radio.
						g. Product - from the range the user wants to enquire about. use select.
						h. Product features: use checkboxes
						i. Comment field, for example, allowing the reader to specify particular aspect they are interested in: use textarea, use a placeholder
* A page about me as an individual *(about.html)* 
* A page that lists an enhancement that I tried to implement, with little success *(enhancements.html)* 
* A CSS file that styles my site *(style.css)* across all the pages
