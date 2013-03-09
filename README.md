TagTag
======

A jQuery plugin that provide tag input.

Usage:
  
   $("#tags").tagtag({      // use .tagtag() on an <input> element
    width: 400,             // width of the tag input area
    height: 100,            // height of the tag input area
    delimiter: ', ',        // delimiters, every chars in the string will be used as a delimiters
                            // and the first char will be used as the connector when put data
                            // back into original <input>.
    onAddTag: callback,     // called after user added a tag.
                            // callback(originalInputElement, tagElement, tagContent)
    validator: callback     // called to verify if a tag is valid.
                            // callback(tagContent)

