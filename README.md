# < l2t-paper-slider >

Polymer element for displaying slides in a carousel.
Have a quick look at the [Component page](http://link2twenty.github.io/l2t-paper-slider) 

## Examples

Each slide must be within a paper-slide tag, but other than that you have complete control.

```html
  <l2t-paper-slider total-slides="4">
    <paper-slide>#1</paper-slide>
    <paper-slide>#2</paper-slide>
    <paper-slide>#3</paper-slide>
    <paper-slide>#4</paper-slide>
  </l2t-paper-slider>
```
  
You can set a different default start position, the first start postion is 0 (as opposed to 1)

```html
  <l2t-paper-slider total-slides="2" position="1">
    <paper-slide>#1</paper-slide>
    <paper-slide>#2</paper-slide>
  </l2t-paper-slider>
```
  
## Styling

The following custom properties are available for styling:

| Custom property | Description | Default |
|----------------|-------------|-------------|
| --paper-slide-dot | Color of unselected Nav Dot | rgba(255, 255, 255, .5) |
| --paper-slide-dot-selected | Color of selected Nav Dot | #FFF |
| --paper-slide-width | Width of slide container | 100% |
| --paper-slide-height | Height of slide container | 600px |

## Attributes

| Attribute Name | Functionality | Default |
|----------------|-------------|-------------|
| totalSlides* | Number for storing total number of slides | 1 |
| position | Number for storing start position of slides | 0 |
required*

## Methods

| Method Name | Action |
|----------------|-------------|
| createDots(t) | Create the nav dots 1 for each slide | alert("You need to set the action attribute") |
| insRules() | Styles the dots controls animation |
| listenerInit() | Adds onclick listener To update the position |
| setStyles() | Styles the slider does slide width and container width |
