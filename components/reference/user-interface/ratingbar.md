# RatingBar

A RatingBar is a component that shows a rating in stars. The user can touch/drag or use arrow keys to set the rating:

![](../../../.gitbook/assets/tutratingbar1.png)

This is a User Interface component that can be added to screen layout. It contains default properties such as number of stars, the current selection, color, etc:

![](../../../.gitbook/assets/tutratingbar2.png)

For this tutorial, as shown above, we are setting defaults NumStars to 5, a start-up Rating of 4.5, StepSize of .5 \(half stars selection\) , StarColor of Red, and AllowSelection to true, allowing user to touch & drag & select number of stars for rating.

## Blocks

Event block AfterSelecting gets triggered when user touches and drags the stars. As dragging is done, this block will return the Rating \(number of stars\) selected.

![](../../../.gitbook/assets/tutratingbar3.png)

In this event-block, we can add other blocks to display additional information:

![](../../../.gitbook/assets/tutratingbar1%20%281%29.png)

This component includes many other blocks that can be used to programatically set or update the component settings:

![](../../../.gitbook/assets/tutratingbar4.png)

