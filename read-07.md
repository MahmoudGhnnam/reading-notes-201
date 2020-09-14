# TABLES
A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.

## basic table structure 

1 - to create table we use ```<table>``` element . the contents of the table are written out now by row


You indicate the start of each
row using the opening ```<tr>``` tag.
(The tr stands for table row.)
It is followed by one or more
```<td>``` elements (one for each cell
in that row).
At the end of the row you use a
closing ```</tr>``` tag.

Each cell of a table is
represented using a ```<td>```
element. (The td stands for
table data.)
At the end of each cell you use a
closing ```</td>``` tag.


The ```<th>``` element is used just
like the ```<td>``` element but its
purpose is to represent the
heading for either a column or
a row. (The th stands for table
heading.)

## Spanning ColumnS
Sometimes you may need the
entries in a table to stretch
across more than one column.
The colspan attribute can be
used on a ```<th>``` or ```<td>``` element
and indicates how many columns
that cell should run across.

## Spanning Rows
You may also need entries in
a table to stretch down across
more than one row.
The rowspan attribute can be
used on a ```<th>``` or ```<td>``` element
to indicate how many rows a cell
should span down the table.

## Long Tables
to make tables lone we used one of this three elements :
* ```<thead>```
* ```<tbody>```
* ```<tfoot>```

## Border & background 
The border attribute was used
on both the ```<table>``` and ```<td>```
elements to indicate the width of
the border in pixels.

* * * 

# OBJECT 
The new keyword and the object constructor create a blank object. You can then add properties and 
methods to the object.

![object](/img/object.png)

## updating an object
To update the value of properties, use dot notation or square brackets. They work on objects 
created using literal or constructor notation.
To delete a property, use the delete keyword.

To update a property, use the same technique that was shown on the left-hand page to add properties 
to the object, but give it a new value.

![update](/img/object update.png)

## CREATING MANY OBJECTS : 

Sometimes you will want several objects to represent similar things.
Object constructors can use a function as a template for creating objects.
First, create the template with the object's properties and methods.

![update](/img/many.png)

## CREATING  AN  INSTANCE OF THE DATE OBJECT

In order to work with dates, you create an instance of the Date object. You can then specify the 
time and date that you want it to represent.

![update](/img/2.png)




