Installation needs:
https://sass-lang.com/install
1. Install the nodejs. Then on command prompt run:

npm install -g sass

2. Use the following command for converting scss into css file:

sass style.scss style.css

************************************************************************************************************************************
https://codepen.io/Shearwater/pen/RwwYWyN?editors=1100

We have a pre-built image upload component which we need to modify in order to use in a different part of our UI. We want to achieve this so that the component can be switched between its two possible display modes by modifying the class(es) on the "rt-image-upload" div. The original state should continue to work.

The component already supports the ability to display the image if one is uploaded, by adding the "--has-image" class to "rt-image-upload__controls". This will need to be supported in both display modes.

The modified component should be able to display the below states: Remember the existing display method should still work.
There are a few requirements:

•	The user can click on the "empty" image to launch the file dialog.
•	The user cannot click the image after it is attached.
•	The user can click the "replace" button to change the image in all states.
•	The user should only see a delete button if there is an attached image.
•	The original mode has a hover state when an image is attached. This should not exist in the smaller state.

You do not need to use javascript to make the component functional - use the dummy content provided in the HTML. The CSS for the original state has been provided and you are free to modify it in any way to achieve the goal. We want to see a simplified CSS at the end of this test. SCSS preprocessing is allowed.

Do not alter the HTML, except to change the classes as mentioned.
