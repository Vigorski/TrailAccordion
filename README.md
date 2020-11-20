# TrailAccordion
TrailAccordion is a very simple JavaScript plug-in intended to handle annoyingly long content in a more pleasant and user friendly manner.
-------
If your website has a collection of items with very long content, instead of landing in the middle of the newly expanded item and losing track of your position, trailAccordion allows you to "trail" along the very beginning of each expanded item.

### CDN
You can start using trailAccordion right away. No download necessary:
- https://vigorski.github.io/TrailAccordion/trailAccordion.js
- https://vigorski.github.io/TrailAccordion/trailAccordion.min.js


### Setup
Using TrailAccordion is very easy.

1. Download the regular or minimal version of the plugin and copy the file to your app.
2. Activate the plugin on the parent element of the collection of items: $(".trail-accordion-parent").trailAccordion()
3. Sit back and relax.

### Settings
In the current version, you can change the behaviour of the accordion slightly with the following optional properties:

Option | Type | Default | Description
------ | ---- | ------- | -----------
animated | boolean | true | Toggles expanding accordion items with animation
aniSpeed | number | 300 | Specify speed of animation in ms
trailToSelection | boolean | true | Toggles option to follow the expanded item or remain stationary (why choose this plug-in if you turn this off??)
multiExpanded | boolean | false | Toggles expanding multiple items
active | number | null | Specify to have an expanded item on load (starts from 0)
------

#### Example
Check out this working version of the plug-in:
[https://codepen.io/Vigorski/pen/Pozvgqy](https://codepen.io/Vigorski/pen/Pozvgqy)

#### Dependencies

jQuery 3.4

#### License

Copyright (c) 2020 Igor Veleski

Licensed under the MIT license.