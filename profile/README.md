# The Ultimate UI Ecosystem

The Lint Trap Media UI ecosystem is a powerful system for managing user interfaces with far less code and complexity than React, Angular, Vue, Htmx, or any other framework. Job listings for "react developers" is evidence enough that things have gotten out of control. There are much simpler ways to do things.

## The Three Tiered System
The Linttrap UI system includes three standalone (but complimentary) projects that solve different problems we all experience out in the wild. It can be viewed as a three tiered system. 

### [oem](https://oem.js.org) (Tier 1 - Manufacturing Plant)
#### A novel UI library for writing reactive html in vanilla javascript
OEM is a lightweight dom library that allows you to create your own template/s dsl. It's simple to write, easy to test and it follows the Locality-Of-Behavior principle which just makes everything easier to manange.

### [domx](https://domx.js.org) (Tier 2 - DOM & State Manipulation)
#### A novel UI library for managing the DOM without javascript
DOMX is a library for manipulating the dom without javascript. Think Htmx re-envisioned as a state machine defined and served from the backend. This allows you to completely control the UI from the backend without  needing javascript.

### [capui](https://capui.js.org) (Tier 3 - Parts and Styles)
#### A novel UI library of cut & paste components
CAP UI is just bunch of cut & paste components made up of vanilla js and css. Modern CSS is powerful and most components need little more than some good css and if needed, a touch of js.

## All Together Now
With these 3 libraries you can build anything. Copy CAP UI components into your project and they're yours, zero dependencies. Using DOMX you can easily add/remove classes, trigger events to your CAP UI components with ease which would work in any framework. If for some reason you really needed something special, write your own component using OEM. 
