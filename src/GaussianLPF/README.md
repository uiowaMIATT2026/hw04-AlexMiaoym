# Gaussian LPF Experiments

For this part, I tested different sigma values on the MRHead data.

* Sigma = 1.0: The image is still pretty sharp and keeps the resolution, but it doesn't remove much noise.
* Sigma = 2.5: This feels like a sweet spot. It smooths out the noise nicely while keeping the main structures of the brain clear. 
* Sigma = 5.0: The noise is completely gone, but the image becomes way too blurry. All the sharp edges and details are lost.

In short, a larger sigma gives you a smoother image (less noise), but you sacrifice a lot of image resolution and lose important edge details.