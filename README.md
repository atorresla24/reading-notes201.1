# Class-02 reading

## Chapter 2: Text

* An e-commmerce website will rarely use html, head, or body tags since they are usually run off of a specific template. The required infortmation will simply be input and then organized by the tmeplate
* Advantage is people who don't know how to utilize html can easily process and make changes
* HTML uses tags
* Tags come in pair to open and close around pieces of content
* Opening tags can carry attributes that can tell us more about the content
* Attributes require a name and value
* Structural markup- the elements that you can use to describe both headings and paragraphs
* Semantic markup- provides extra info wihtin quotation marks
* Headers can be given a value from 1-6 and will determine size 
* Surround content with a p tag to define a paragraph which is a group of text that contains one or more sentences
* Enclosing content in b tags will make it **bold** and enclosing content in i tags will make it *italicized*
* The 'sup' tags will define a superscript such as suffixes of dates or mathematical concepts
* The 'sub' tags are for subscript characters
* White space collapsing- is when two or more spaces is counted as only one space
* A 'br" line will break off a line to start it off at the next line
* An 'hr' will create a break between theme
* Visual editors resemble word processors but differ with features
* Code views shows the code of the visual editor
* There are some text elements that will not effect structure such as em and blockquote
* Those elements listed above are used for describing content 
* The strong tag is used to indicate importance
* The q tag is used for shorter quotes that sit withint a paragraph
* The 'abbr' tag is used for abbreviations
* A cite tag is used when referencing a pice of work 
A dfn tag is used to define some new terminology
* The address tag is used to contain a physical address or phone number or email address

## Chapter 10: Intro to CSS

### Understanding CSS

* Key to understanding CSS is by imagining an invisible box around every HTML element
* CSS allows the creation of rules that control the way each box is presented
* Examples:
  - Boxes:
    * Width and height
    * Borders
    * Background
    * Position in browser
  - Text:
    * Typeface
    * Size
    * Color
    * Italics
  - Specific:
    * Elements can also be styled such as lists, tables and forms
* CSS rule contains two parts: selector and declaration
  - **Selector**- indicates which element the rule appplies to 
  -**Declaration**- indicates how the element is referred to and split into: property and value
    -**Property**- indicates the aspect that is going to br changed
    -**Values**- specifies the settings that is chosen for the property
* External CSS is added by using link tags with href, type and rel attributes
  - href- specifies path to CSS file
  - type- specifies the type of dicument
  - rel- specifies the relationship between the html page and file
* Types of selectors:
  - Universal selector
  - Type selector
  - Class selector
  - ID selector
  - Child selector
  - Descendant selector
  - Adjacent sibling selector
  - General sibling selector
* Properties such as font-family can be inherited by children but not background-color
* By creating an external CSS page it allows for it to be used on multiple HTML pages

## Chapter 2: Basic JavaScript

* A script is a series of step-by-step instructions and each step is called a statement
* JavaScript is case sensitive
* Comments can be written to explain what parts of the code do and it won't interfere with the code
* Data variables are used to store bits of information that can be reused as long as they are defined correctly
* There are two parts to a variable:
  - Variable keyword- is used to identify a variable
  - Variable name- is the name of the keyword
* Once a name is assigned a value is the next thing to give to the variable
* Data types:
  - Numeric 
  - String
  - Boolean
* Array- a special type of variable that stores a list of values
* Values are put inside square brackets and the technique for creating an array is called **array literal**
* Expressions evaluate into a single value and there are two types:
  - Expressions that assign a value to a variable
  - Expressions that use two or more values to return a single variable
* Expressions rely on operators such as: 
  - Assignment operators
  - Arithmetic operators
  - String operators
  - Comparison operators
  - Logical operators

  ## Chapter 4: Decisions and loops

  * Create and control the flow of data in scripts with:
    - Evaluations
    - Decision
    - Loops
  * There are different places where a decision is going to be made in the code which will determine what code is ran
  * Two components to a decision:
    - An expression is evaluated which will return a value
    - A conditional statement that says what to do in a given situation
  * Comparison operators:
    * (==) is equal to
    * (!=) is not equal to 
    * (>) is greater than
    * (<) is less than
    * (>=) is greater than or equal to 
    * (<=) is less than or equal to 
  * A condition consists of two operands seperated by a comparison operator
  * Logical operators return a true or false result
    - (&&) logical and
    - (||) logical or 
    - (!) logical not
  * An *if* statement will only be executed if the condition is met
  * An *if-else* statement executes the first set of code if the first part is true but if not then the second part is executed
  * Switch statement- starts with a variable and depending on which value of the variable is chosen is which code will be ran
  * Loops will run a piece of code until it becomes false
  * *For loops* can use a counter as a condition such as:
    - initialization
    - condition 
    - update
  * Key loop concepts:
    - keywords
    - break 
    - continue
    - loops & arrays
    - performance issues
  
  ## Things I want to know more

  * How to better utilize loops 
  * How to better understand variables to be able to make my code more reusable
  * Learn how to properly use arrays
  * Figure out how specific I need to be with selectors
