[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/GDPVb20V)
# Mystery Function

What does the `mystery()` function in the following piece of code do? Add your
answer to this markdown file.

```javascript
function mystery(a) { // This function takes in an array.
    if(a.length == 1) return a[0]; // Checks if the length of the array is comparatively equal to 1, then the function returns the value at the index 0 of the array. 
    var foo = mystery(a.slice(1, a.length)) // The variable foo recursively calls the mystery function except this time taking a slice of the array from index 1 to the end of the array. 
    if(foo > a[0]) return foo; // checks if foo is greater than the index 0 of the orignal input array, then the function will return foo which recursively calls the mystery function this time with a slice of the new array.
    else return a[0]; // else the function will return the value stored at the index 0. 
}
```
// This function uses a recursive method to search a through a list of numbers for the highest value. The recusive method allows for the iteration through the entire list of numbers. While slicing the array down in size 
// until foo becomes the highest value in the list and the list is equal to length of 1. The slice method returns the selected elements as a new array this does not change the original array. 

// https://www.w3schools.com/jsref/jsref_slice_array.asp
// I recieved help from the TA and reviewed my repository from last semester. 

