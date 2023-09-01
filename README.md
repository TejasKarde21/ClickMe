# ClickMe  https://tejaskarde21.github.io/ClickMe/CatchME/index.html

const button = document.getElementById("btn");: This line fetches an HTML element with the id "btn" using the getElementById
method and assigns it to the button constant. This element is assumed to be a button or any other HTML element you want to move around.
button.addEventListener("mouseover", () => { ... });: This line adds an event listener to the button element.
It listens for the "mouseover" event, which occurs when the mouse cursor is moved over the button.
Inside the event listener function, the following actions occur:
const top = Math.floor(Math.random() * 500) + 1;: This line generates a random integer between 1 and 500
(inclusive) and assigns it to the top variable. This value will be used to set the new vertical position of the button.
const left = Math.floor(Math.random() * 1300);: This line generates a random integer between 0 and 1299 
(inclusive) and assigns it to the left variable. This value will be used to set the new horizontal position of the button.
button.style.left = left + "px"; and button.style.top = top + "px";: These lines update the CSS styles of
the button element to move it to the new random position. The left and top properties are set to the random values 
we generated earlier, and "px" is added to specify the unit as pixels.
