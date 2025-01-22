# Uncommon HTML Bug: Accessing innerHTML.textContent

This repository demonstrates a subtle bug related to accessing the innerHTML property of an HTML element. The bug arises from an attempt to access the `textContent` property of the `innerHTML` property, which is incorrect and throws an error.  The solution shows the correct way to access and manipulate innerHTML.

## Bug Description

The bug lies in how the innerHTML of a div element is accessed.  The `innerHTML` property already returns a string representing the HTML content within the element.  Therefore, trying to further access `textContent` on this string results in a TypeError.

## Solution

The solution demonstrates the correct way to access and manipulate the content of the div element.  The correct approach is to directly use the `innerHTML` property to read or modify the HTML content. No need for `.textContent`
