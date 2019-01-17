# JerUnchained
> This is a project for school where I'm trying to see whether or not it's possible to start a brand within one semester. The brand wouldn't be complete without a website so that's what I'm uploading here. 

## Table of Contents
- [Parallax](#parallax)
- [Introtext](#introtext)
- [Socialicons](#socialicons)
- [Listanimation](#listanimation)

## Parallax
In Parallax1 you can see an example of "fake" parallax scrolling with css. 
In Parallax2 you can see an example of actual parallax scrolling with javascript.

## Introtext
Changing the intro text happens in the HTML. Each letter needs to be a seperate <li> so that every letter gets animated independently.
If you want to change the time between the subtext appearing after the title, change the number in the setTimeout(function().

```javascript
setTimeout(function(){
                    welcomeSection.removeClass('content-hidden');
                },800);
```

If you want to change the position of the animating letters, change the translate3d position in css.
```css
.content-hidden .fly-in-text li:nth-child(1) {
    transform: translate3d(-60px, 0, 0);
}
```

## Social icons
If you want to use it in another project, just add the css and replace the current social icon with the complete unordered list + social code so: 
```html
<ul>
            <li>
                <a href="#">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <i class="fa fa-facebook" aria-hidden="true"></i>
                </a>
            </li>
</ul>
```

## Listanimation
Completely made with css, just add the HTML and css. If you want anything changed, edit the css.
