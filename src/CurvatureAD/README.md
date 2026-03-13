# Curvature Anisotropic Diffusion Experiments

I tested the Curvature AD filter on the MRHead data. It's very similar to the Gradient AD filter.

Observations: Compared to Gradient AD, this filter does a slightly better job at preserving fine, continuous structures (like natural curves and thin tissue boundaries) while still aggressively removing noise in the flat regions.
Tuning: The parameters behave similarly. Higher `iterations` = smoother; lower `conductance` = keeps more edges. 

Best settings for my test: `--iterations 5 --conductance 2.0 --timeStep 0.0625`. It gives a very natural-looking smooth image.