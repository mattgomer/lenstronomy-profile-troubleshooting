# lenstronomy-profile-troubleshooting
Public space to share troubleshooting findings using lenstronomy notebooks


The main notebook of interest is chameleon_troubleshooting.ipynb, which shows the case that the Dutton et al. 2011 prescription does not create a Chameleon profile which matches the Sersic input to the quoted precision. Instead, a modification is required to the alpha paramter, which is able to reproduce the figure in Dutton et al.

The kinprofiles_comparison_demo.ipynb shows a test to make sure the chameleon profile kinematics work. When the MGE is included (specifically for the light component), the values change if the ellipticity is nonzero and the curves don't match.
