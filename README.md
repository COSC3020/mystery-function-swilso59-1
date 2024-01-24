[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/GDPVb20V)
# Mystery Function

What does the `mystery()` function in the following piece of code do? Add your
answer to this markdown file.

```javascript
function mystery(a) { // This function takes in an array.
    if(a.length == 1) return a[0]; // If the length of the array is comparatively equal to 1 then the function returns the value at the 0 index position of the array. 
    var foo = mystery(a.slice(1, a.length)) // The variabel foo is set equal to the 
    if(foo > a[0]) return foo;
    else return a[0];
}
```
