# JavaScript Drum Kit

## About
This project is a practice in writing vanilla JavaScript. It is part of the **JavaScript30** course by Wes Bos. It is a free course (at least at the writing of this file) and can be found at [javascript30.com](https://javascript30.com). 

### View Project
View the live project here: [junclemente.github.io/j30-drumkit](https://junclemente.github.io/j30-drumkit/).

#### Lesson takeaways
* Use of addEventListener for 'keydown' event
* Use of 'transitionend' to trigger another function after a transition has completed
* The following code are equivalent to each other, one using `=>`:
```
keys.forEach(function(key) {
	key.addEventListener('transitionend', removeTransition);
}
```
and: 
```
keys.forEach(key => key.addEventListner('transitionend', removeTransition);
```
