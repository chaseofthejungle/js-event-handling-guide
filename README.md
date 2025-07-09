# JavaScript Event Handling Properties Guide
  
**Description/Overview:** JavaScript (JS) events are signals that are triggered inside of web browsers, as alerts of web browser modifications and/or the environments of operating systems. The Document Object Model (DOM) properties of event handlers enable functions to be assigned to events, which are ran when such events occur for specified elements. 
  
#### Table of Contents
  
1. [Animating](#animating)
2. [DOM Mutating](#dom-mutating)
3. [Dragging and Dropping](#dragging-and-dropping)
4. [Focusing](#focusing)
5. [Form Handling](#form-handling)
6. [Key Pressing](#key-pressing)
7. [Media Handling](#media-handling)
8. [Mobile Touching](#mobile-touching)
9. [Page Visibility](#page-visibility)
10. [Selecting Items](#selecting-items)
11. [Transitioning](#transitioning)
12. [Window Handling](#window-handling)
13. [Miscellaneous Event Handling](#miscellaneous-event-handling)
14. [Supplemental Resources](#supplemental)
  
<hr />

## 1. <a name="animating">Animating</a>

* **onanimationstart:** Runs when a CSS animation begins.
* **onanimationiteration:** Runs when a CSS animation is finished its *specific iteration*.
* **onanimationend:** Runs when a CSS animation is finished its cycle/active period.
  
<hr />
  
## 2. <a name="dom-mutating">DOM Mutating</a>
  
* **onDOMNodeInserted:** Runs when a new node is added to the DOM.  
* **onDOMNodeRemoved:** Runs when a new node has been removed from the DOM.  
* **onDOMSubtreeModified:** Runs when a part of the DOM has been changed/edited.  
  
<hr />
  
## 3. <a name="dragging-and-dropping">Dragging and Dropping</a>
  
* **ondrag:** Continuously runs while an element is dragged.
* **ondragstart:** Runs when an element begins being dragged.
* **ondragend:** Runs when the dragging of an element is finished.
* **ondragover:** Runs when an element is dragged over a target/destination where it might be dropped.
* **ondrop:** Runs when an element is dropped onto a target/destination after being dragged.
  
<hr />

## 4. <a name="focusing">Focusing</a>
  
* **onfocus:** Runs when focus is placed upon an input field.  
* **onblur:** Runs when focus is removed from an input field.  
* **onfocusin:** Same as *onfocus*, but permits event delegeation by bubbling up from an element.  
* **onfocusout:** Same as *onblur*, but also bubbles up from an element.
  
<hr />

## 5. <a name="form-handling">Form Handling</a>

* **onfocus:** Runs when focus is placed upon an input field.  
* **onblur:** Runs when focus is removed from an input field.  
* **oninput:** Runs continuously while a user types input into a field.
* **onchange:** Runs when the input value of an element is modified.
* **onsubmit:** Runs upon user submission of a form.

<hr />

## 6. <a name="key-pressing">Key Pressing</a>
  
* **onkeypress:** Runs when a key is pressed and held down *(note: this feature is deprecated in contemporary web browsers)*.
* **onkeyup:** Runs when a key that was pressed has been released.
* **onkeydown:** Runs when a key is pressed.
  
<hr />

## 7. <a name="media-handling">Media Handling</a>
  
* **onplay:** Runs when media (e.g., audio, video) begins to play.
* **onended:** Runs when the media is finished playing.
* **onpause:** Runs when playing of the media is paused.

*(Note: **matchMedia** is an event that can be used for responsive design in media querying. It detects when a media query is modified or matched, as a callback is sent when a listener is triggered.)*
  
<hr />

## 8. <a name="mobile-touching">Mobile Touching</a>
  
* **ontouchstart:** Runs if a touch point is placed on a touch surface.
* **ontouchmove:** Runs if a touch point is dragged across a touch surface.
* **ontouchend:** Runs if a touch point is no longer/finished being on a touch surface.
* **ontouchcancel:** Runs if a touch gesture is cancelled (such as when a user moves over to another app).
  
<hr />

## 9. <a name="page-visibility">Page Visibility</a>
  
* **document.hidden:** Evaluates to true if a page is hidden/invisible.
* **onvisibilitychange:** Runs when the visibility state of a page is modified (such as when a user moves to a different web browser tab).
  
<hr />

## 10. <a name="selecting-items">Selecting Items</a>

* **onselect:** Runs when a user selects text from within a textarea or input element. 
* **onselectionchange:** Runs when a user has a new selection (such as text selection).
  
<hr />

## 11. <a name="transitioning">Transitioning</a>

* **ontransitionstart:** Runs when a CSS transition begins.
* **ontransitionend:** Runs when a CSS transition is over.
* **ontransitioncancel:** Runs when a CSS transition is cancelled.
  
<hr />

## 12. <a name="window-handling">Window Handling</a>

* **onload:** Runs when a webpage has completed loading.
* **onscroll:** Runs when a user scrolls on a webpage.
* **onresize:** Runs when the browser window's size has been adjusted.
* **onunload:** Runs when a user navigates away from ('unloads') a webpage.
* **onbeforeunload:** Runs prior to a webpage being unloaded, confirming the user's navigation away from it.

<hr />

## 13. <a name="miscellaneous-event-handling">Miscellaneous Event Handling</a>
  
* **addEventListener:** Adds a listener for a specified event to an element.
* **removeEventListener:** Deletes a specified listener from an element. 
* **oncontextmenu:** Runs when a user right clicks on an element, opening the context menu.
* **onerror:** Runs if an error happens (e.g., element fails to load).

<hr />

## 14. <a name="supplemental">Supplemental Resources</a>

* *[Intro to MERN and MEAN Stack Guide](https://github.com/chaseofthejungle/intro-to-mern-and-mean-stack)*
* *[JavaScript Concepts Guide](https://github.com/chaseofthejungle/js-concepts-guide)*
* *[Node.js JavaScript Runtime Environment Official Website](https://nodejs.org/en)*
