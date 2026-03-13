# Gradient Anisotropic Diffusion Experiments

I tested the Gradient AD filter on the MRHead data.

Iterations : More iterations mean more smoothing. 5 iterations gives a solid result, but 10 or 15 makes it super smooth.
Conductance : This acts like an edge-detection threshold. 
Time Step: Controls how fast it diffuses per step. Kept it at 0.0625 to ensure mathematical stability for 3D images.

Best settings for my test: `--iterations 5 --conductance 2.0 --timeStep 0.0625`. It gave a clean image without making the brain structures look like mush.