### Drink Water

This JavaScript code is responsible for generating a Liquid Fill Effect i.e. when the user clicks on one of the cups, the amount of water in the big cup gets updated and the small cups get highlighted accordingly.

The code first selects all the elements with class "cup-small" and the container elements (liters, percentage, and remained) which will display the output to the user.

Then, using the updateBigCup() function, the amount of liquid in the big cup is calculated based on the filled small cups. This function also updates the height and visibility of the percentage and remained containers.

Next, using the forEach() method, an event listener is added to each cup-small element that triggers the highlightCups(idx) function when clicked. This function then highlights the cups by selectively adding or removing the "full" class from the small cups.

In the end, the updateBigCup() function is called again to calculate the amount of liquid in the big cup and update the display accordingly.
