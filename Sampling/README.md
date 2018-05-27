## simple_sampling

Without using sampling libraries/functions, <br />
-- Implement sampling from continuous distributions:  <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- uniform (min, max, sample_size) <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- gaussian (mu, sigma, sample_size)<br />
-- Implement sampling from a 2-dim Gaussian Distribution (2d mu, 2d sigma, sample_size)

## stevens_sampling

Implement without-replacement sampling from a discrete non-uniform distribution (given as input) following the Steven's method. <br /><br />
Test it on desired sample sizes N significantly smaller than population size M (for example N=20 M=300)

## gibbs_sampling

Implement Gibbs Sampling for a multi-dimensional gaussian generative joint, by using the conditionals which are also gaussian distributions.  <br /><br />
The minimum requirement is for joint to have D=2 variables and for Gibbs to alternate between the two.
