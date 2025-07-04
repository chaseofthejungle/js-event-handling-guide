# JavaScript Event Handling Properties Guide
  
#### Table of Contents
  
1. [Animating](#animating)
2. [DOM Mutating](#dom-mutating)
3. [Dragging and Dropping](#dragging-and-dropping)
4. [Focusing](#focusing)
5. [Form Handling](#form-handling)
6. [Key Pressing](#key-pressing)
7. [Media Handling](#media-handling)
8. [Miscellaneous Event Handling](#miscellaneous-event-handling)
9. [Mobile Touching](#mobile-touching)
10. [Page Visibility](#page-visibility)
11. [Selecting Items](#selecting-items)
12. [Transitioning](#transitioning)
13. [Window Handling](#window-handling)
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

## 8. <a name="miscellaneous-event-handling">Miscellaneous Event Handling</a>

(TODO)

<hr />

## 9. <a name="mobile-touching">Mobile Touching</a>

(TODO)

<hr />

## 10. <a name="page-visibility">Page Visibility</a>
  
* **document.hidden:** Evaluates to true if a page is hidden/invisible.
* **onvisibilitychange:** Runs when the visibility state of a page is modified (such as when a user moves to a different web browser tab).
  
<hr />

## 11. <a name="selecting-items">Selecting Items</a>

(TODO)

<hr />

## 12. <a name="transitioning">Transitioning</a>

(TODO)

<hr />

## 13. <a name="window-handling">Window Handling</a>

(TODO)

<hr />

## 14. <a name="supplemental">Supplemental Resources</a>

* *[Intro to MERN and MEAN Stack Guide](https://github.com/chaseofthejungle/intro-to-mern-and-mean-stack)*
* *[JavaScript Concepts Guide](https://github.com/chaseofthejungle/js-concepts-guide)*
* *[Node.js JavaScript Runtime Environment Official Website](https://nodejs.org/en)*
  
<hr />

**TODO:** Fill in sections 8, 9, 11, 12, and 13 with initial information.
