# TrailAccordion
TrailAccordion is a very simple JavaScript plug-in intended to handle annoyingly long content in a more pleasant and user friendly manner.
If your website has a collection of items with very long content, instead of landing in the middle of the newly expanded item and losing track of your position, trailAccordion allows you to "trail" along the very beginning of each expanded item.

*The plug-in is built using jquery-3.4.1, so you will need to include it in your project.


Setup
Using TrailAccordion is very easy.

1. Download the regular or minimal version of the plugin and copy the file to your app.
2. Activate the plugin on the parent element of the collection of items: $(".trail-accordion-parent").trailAccordion()
3. Sit back and relax.

Options
In the current version, you can change the behaviour of the accordion slightly with the following optional properties:

Name                Type            Default         Description

animated:           boolean         true            Toggles expanding accordion items with animation
aniSpeed:           number          300             Specify speed of animation in ms
trailToSelection:   boolean         true            Toggles option to follow the expanded item or remain stationary (why choose this plug-in if you turn this off??)
multiExpanded:      boolean         false           Toggles expanding multiple items
active:             number          null            Specify to have an expanded item on load (starts from 0)


Example:
Check out this working version of the plug-in:
https://codepen.io/Vigorski/pen/Pozvgqy