# drum-kit

A beginner friendly webiste made by usnig HTML CSS and JS .

Here you get to learn abount DOM manipulation and all about event listener a very important concept in JS. the webiste plays an audio on every button click as well as plays sound on a paticular "keypress". 

we get to learn about :

1- EVENT LISTENER 
document.addEventListener("keypress",function(event) {
    makeSound(event.key);  //used to key the key which is pressed i.e the event which triggers the eventListener
    buttonAnimation(event.key);
})

2- AUDIO IS JS
var audio = new Audio("sounds/tom-1.mp3");
audio.play();

3- SET TIMEOUT IN JS
setTimeout(function() {
        activeButton.classList.remove("pressed")
    }, 100);
