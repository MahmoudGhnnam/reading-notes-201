# form 

## Form Controls:

There are several types of form controls that
you can use to collect information from visitors
to your site.

* adding text
* making choices
* submitting forms
* uploadinf files

![element](/img/upload.png)

how forms work ?

1 - A user fills in a form and then presses a button
to submit the information to the server.

2 - The name of each form control is sent to the
server along with the value the user enters or
selects.

3 - The server processes the information using a
programming language such as PHP, C#, VB.net,
or Java. It may also store the information in a
database.

4 - The server creates a new page to send back to the
browser based on the information received.

## form structure :

* ```<form>```

Form controls live inside a
```<form>``` element. This element
should always carry the action
attribute and will usually have a
method and id attribute too.

* action

Every ```<form>``` element requires
an action attribute. Its value
is the URL for the page on the
server that will receive the
information in the form when it
is submitted.

* method

Forms can be sent using one of
two methods: get or post.

## list-style-type:  

The list-style-type property
allows you to control the shape
or style of a bullet point (also
known as a marker).
It can be used on rules that
apply to the ```<ol>```, ```<ul>```, and ```<li>```
elements.

# STYLE 

## list-style-image:

You can specify an image to act
as a bullet point using the
list-style-image property.
The value starts with the letters
url and is followed by a pair
of parentheses. Inside the
parentheses, the path to the
image is given inside double
quotes.
This property can be used on
rules that apply to the ```<ul>``` and
```<li>``` elements.

## list-style-position:

Lists are indented into the page
by default and the list-styleposition
property indicates
whether the marker should
appear on the inside or the
outside of the box containing the
main points. This property can take one of
two values:

* outside
The marker sits to the left of the
block of text. (This is the default
behaviour if this property is not
used.)

* inside
The marker sits inside the box of
text (which is indented).

## list-style:
As with several of the other CSS
properties, there is a property
that acts as a shorthand for list
styles. It is called list-style,
and it allows you to express
the markers' style, image and
position properties in any order.

* * * 

# EVENT 
When you browse the web, your browser registers different
types of events. It's the browser's way of saying, "Hey, this
just happened." Your script can then respond to these events.

## HOW EVENTS TRIGGER JAVASCRIPT CODE:
When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.
Together these steps are known as event handling.

1 - Select t he element
node(s) you want the
script to respond to.

2 - Indicate which event on
the selected node(s) will
trigger the response

3 - State the code you want
to run when the event
occurs.

## Here is the syntax to bind an event to an element using an event handler, and to indicate which function should execute when that event fires:

![event](/img/event.png)

## event flow 

HTML elements nest inside other elements. If you hover or click on a link, you will also be 
hovering or clicking on its parent elements.

![event](/img/event 2.png)

## why flow matters :

The flow of events only really matters when your code has event handlers on an element and one of 
its ancestor or descendant elements.


