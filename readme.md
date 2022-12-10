The Dom is the browsers visual representation of your page
The browser gives us access to this structure via the DOM API
The DOM API gives us many methods we can use to access the DOM
We typically use JavaScript to execute these methods

## Acessing the Dom

    To Acess the dom , we can use ## document object

    document.getElementById()  it returns an element object
    document.getElementByClassName()   it return an HTML collection
    document.getElementByTagName()      it reutrn an Html Collection
    document.querySelector()        it return an elemnt object
    document.querySelectorAll()     it returns an Nodelist

## Node

Every Node had a nodeType, nodeName and nodeValue property

## Traversing the DOM

traversing the dom vs accessing the dom

###

## parent

A parent of any node is the node immediately above it
There are 2 main methods we can use to get the parent node
parentNode
parentElement

## sibling

A sibling of a node is any node in the same lavel

<!DOCTYPE html>     refers 3 things

1.window
2.document
3.html (let HtmlElement = document.documentElement)

firstChild
firstElementChild
lastChild
parentNode
children
nextSibling
nextElementSibling
previousSibling
previousElementSibling

Child Nodes vs children
child Nodes return NodeList

children return Html Collection
