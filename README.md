# Smooth-Images-Zoom-Transition

## Initially we have to set the image color to gray by using filter: grayscale(1).  And the when we hover over the image-wrapper we have to scale the image and revert back to the original image color [filter:grayscale(0)] and add a ease-in-out transition timing function to make the effect smoother. The scaling only works because the overflow property is set to hidden on the parent container
