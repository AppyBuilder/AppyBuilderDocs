# Snackbar

Using **Snackbar** , you could have feedback on  an operation. Snackbar  shows a brief message at the bottom of the screen, above all other elements. Only one can be displayed at a time. Snackbar disappear after user interaction.

Snackbar includes an event-block called AfterAction. It will be automatically triggered when Snackbar action is clicked. This block contains a parameter called "action". It can be used to determine type action that user selected. For example, we can use if-then-else, to check user's response as below:

![](../../../.gitbook/assets/image%20%2832%29.png)

**Creating Snackbar.** You can create a Snackbar using the following block, in message you should add one-message and up to two actions. The message will appear on left-side and the actions will display on right side. If you want to have only one-action, just plug an empty text block into socket.

![](../../../.gitbook/assets/image%20%2824%29.png)

**Opening Snackbar.** Use block below to determine if Snackbar is open or not

![](../../../.gitbook/assets/image%20%2845%29.png)

**Closing Snackbar.** Use block below to force closing of Snackbar. 

![](../../../.gitbook/assets/image%20%2839%29.png)

Image below shows how Snackbar looks when 2 actions are provided. Note: For this example, we used Snackbar.TextColor to change the default color:

![](../../../.gitbook/assets/image%20%2826%29.png)

![](../../../.gitbook/assets/image%20%2821%29.png)



