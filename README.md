# UIScrollView with masked content

Mimicks the scolling behaviour of the iOS8 Weather app (not to be confused with the popular Yahoo weather app). Basically, when the user scrolls past a certain point, the scroll content (weather data) becomes masked, leaving space at the top to display a minimised masthead.

![](https://raw.githubusercontent.com/doug-proctor/UIScrollView-with-masked-content/master/screenshots/recording.gif)

It has the appearance of two nested same-direction scrollviews, but its really just one. This allows for continuous scrolling/dragging across the clipping threshold.
