Checkbox
type="checkbox": Checkboxes allow users to select (and unselect) one or more options in answer to a question.
value:The value attribute indicates the value sent to the server if this checkbox is checked.
Drop Down List Box: < select >
The < select > element is used to create a drop down list box. It contains two or more < option> elements.
< option >: The < option > element is used to specify the options that the user can select from. The words between the opening < option > and closing < /option > tags will be shown to the user in the drop down box.
drop list

File Input Box
type="file": This type of input creates a box that looks like a text input followed by a browse button. When the user clicks on the browse button, a window opens up that allows them to select a file from their computer to be uploaded to the website.
Lists Tables Forms
Bullet point styles:list-style-type
The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker).It can be used on rules thatapply to the < ol >, < ul >, and < li > elements.
Unordered Lists: for an unordered list you can use the following values:
none

disc

circle

square

Ordered Lists: For an ordered (numbered) list you can use the following values:
decimal 1 2 3

decimal-leading-zero 01 02 03

lower-alpha a b c

upper-alpha A B C

lower-roman i. ii. iii.

upper-roman I II III

Table properties
width:to set the width of the table.
padding:to set the space between the border of each table cell and its content.
text-transform: to convert the content of the table headers to uppercase.
letter-spacing, font-size to add additional styling to the content of the table headers.
border-top, border-bottom: to set borders above and below the table headers.
text-align to align the writing to the left of some table cells and to the right of the others.
background-color to change the background color of the alternating table rows.
Events
TRADITIONAL DOM EVENT HANDLERS
All modern browsers understand this way of creating an event handler, but you can only attach one function to each event handler.
event

USING DOM EVENT HANDLERS
event example

EVENT LISTENERS
Event listeners are a more recent approach to handling events. They can deal with more than one function at a time but they are not supported in older browsers.
even l

THE EVENT OBJECT
When an event occurs, the event object tells you information about the event, and the element it happened upon.
even object

EVENT DELEGATION
Creating event listeners for a lot of elements can slow down a page, but event flow allows you to listen for an event on a parent element.
event d
