## global environment, global object

- use bracket, reference app.js
- click app.js folder and the 'thunder'
- chrome pops up. type this and window, see what shows.
althought we have no code, the execution context has created the global object and the variable 'this' for us.
- global object (= window, where we run the code) = this, at the global level
- global: not inside the function

- put this code:
'''
var a= "hello world!"
function b ={}
'''

run this. put window.
we can see variable a and function b inside the description below.
put a, it shows our string.
put window.a, it gives us the same result.

