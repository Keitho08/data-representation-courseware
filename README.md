# Data-Representation-Courseware

Repository for assignments as part of Data Represenation module on the Computer Science with Data Analytics Course at GMIT.

# Programming for Data Analysis - Project 2020

## Galway Mayo Intitute of Technology - HDip Data Analytics 2020-2021
***
### Keith Brazill - G00387845
***

**Assignment 1.1 Brief:**

Create an XML file that stores data for a library. 

The library has two catalogues (technical books, and for cookery books).

Each catalogue can contain a number of books (say 2 for the purpose of this exercise) . 

Books will have an ISBN, title and author.

Upload your .xml file to your github repository called data-representation-courseware and copy your link.

**Summary of Repository**

The README and XML file,  is prepared in response to the brief assigned for an assignment in the module of Data Representation as part of the postgraduate diploma in Computer Science with Data Analytics at Galway Mayo Institute of Technology. The code required to respond to the task is provided below and in the seperate XML file in this repository.

```xml
<Library>
	<Catalogues>
		<Catalogue name="Technical Books">
			<Books>
				<Book ISBN="0415699320">
					<author>Chadderton, David V.</author>
					<title>Building Services Engineering</title>
				</Book>
				<Book ISBN="9780415644594">
					<author>Charleson, Andrew</author>
					<title>Structure as Architecture</title>
				</Book>
			</Books>
		</Catalogue>
		<Catalogue name="Cooking Books">
			<Books>
				<Book ISBN="9781444756692">
					<author>Ramsey, Gordon</author>
					<title>GORDON RAMSAY'S ULTIMATE COOKERY COURSE</title>
				</Book>
				<Book ISBN="9781473652279">
					<author>Ramsey, Gordon</author>
					<title>GORDON RAMSAY'S ULTIMATE FIT FOOD</title>
				</Book>
			</Books>
		</Catalogue>
	</Catalogues>
</Library>
```

A good XML file should follow a certain set of rules as specified by W3Schools. These include the root element which in our case is the Library which has an open and closing section and contains all elements nested inside the root. Within the root element we have created two catologues one for Technical and one for Cooking books. The catalogues in this case is refereed to as "child" elements in the root folder. We have created "sub-child" folders under both catologues for each book we add which is identified by its ISBN, author and title. 


**References** 

*A complete list of all references used in this repository is included below:*
1. W3schools.com. 2021. XML Syntax. [online] Available at: <https://www.w3schools.com/xml/xml_syntax.asp> [Accessed 20 October 2021].
2. 3schools.com. 2021. XML Tutorial. [online] Available at: <https://www.w3schools.com/xml/default.asp> [Accessed 20 October 2021].
3. W3schools.com. 2021. XML Elements. [online] Available at: <https://www.w3schools.com/xml/xml_elements.asp> [Accessed 20 October 2021].
4. W3schools.com. 2021. XML Attributes. [online] Available at: <https://www.w3schools.com/xml/xml_attributes.asp> [Accessed 20 October 2021].
5. Codegrepper.com. 2021. .md xml code Code Example. [online] Available at: <https://www.codegrepper.com/code-examples/whatever/.md+xml+code> [Accessed 20 October 2021].
6. eatty, A., 2021. GitHub - andrewbeattycourseware/datarepresentation2021. [online] GitHub. Available at: <https://github.com/andrewbeattycourseware/datarepresentation2021> [Accessed 20 October 2021].


***
# End