# what is an object?
Objects are a grouped set of variables (properties) and functions (methods) to create models.
 The most popular way to create objects is by a literal notion.
  Objects are stored in a variable; the object itself is the curly braces and their contents.


* IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES

* IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS  

  ![object](/img/exam.png)

 * * * 

# DOM 

DOM is the Document Object Model. The DOM specifies how a browser creates a model of an HTML page and the way JavaScript can access and update the page while it is in the browser. This is represented in a DOM tree which is stored in the browser’s memory.

# DOM tree
### DOM trees consist of four main types of nodes:

- The document Node (represents the entire page)
- Element Node (represents HTML elements)
- Attributes Node (represents attributes of elements)
- Text Nodes (represents text within elements)

### traversing the DOM. select another element in relation to it using these five properties

- parentNode
- previousSibling
- nextSibling
- firstChild
- lastChild


## SELECTING AN ELEMENT FROM A NODELIST
There are two ways to select an element from a Nodelist:

1. The item() method
array syntax. Both require the index number of the element you want.
repeating actions for an entire nodelist
``` var hotelItem= document.querySelectorA11('li.hot'); for (var i=0;i< hotelItem.length; i++){ hotelItem[i].className='cool'; }```

2. **ACCESSING & CHANGINGA TEXT NODE**
```java var itemTwo document.getElementByld('two'); var elText itemTwo.firstChild .nodeValue; elText = elText.replace( ' pine nuts', ' kal e '); itemTwo .firstChi ld.nodeValue = elText;```

to adding and removing HTML content
there are two ways:

* DOM tree.
* innerHTML 

* * * 