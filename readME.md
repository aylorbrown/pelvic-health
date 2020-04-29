## ROOT Project Page 

### Project Description 
Landing page for an app I created call ROOT

### Code Example

Flying yogi is defined in html with the class ```.flier```

Adjusts animation duration to change the yogi's speed 
```css 
.flier > * {
    animation: fly 50s linear infinite;
    pointer-events: none !important;
	top: 0;
	left: 0;
	transform: translateX(-120%) translateY(-120%) rotateZ(0);
	position: fixed;
	animation-delay: 1s;
	z-index: 999999;
}
```

Keyframe values control where the element will begin and end its trajectory across the screen. Each rule represents a path the yogi follows across the screen. There are eight rules, here is one:
```css 
@keyframes fly {

	98.001%, 0% {
        display: block;
		transform: translateX(-200%) translateY(100vh) rotateZ(0deg)
	}
}
```

### Author 
[Aylor Brown](https://aylorbrown.com)