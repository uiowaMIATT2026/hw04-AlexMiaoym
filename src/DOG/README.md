# Difference of Gaussians (DOG) Experiments

I tested the DOG filter to extract edges from the MRHead data.

* Small difference *: Extracts very fine, thin edges, but picks up some noise artifacts.
* Large difference *: Extracts thicker, more pronounced edges, ignoring tiny noise details and focusing strictly on major anatomical boundaries.

In short, a larger difference between the two sigmas captures thicker and broader edges.