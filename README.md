# Sigma-56mm-F1.4
Data calibration for lens Sigma 56mm F1.4 Contemporary
I tested my Sigma 56mm f/1.4 art contemporary on my sony alpha 6600 following step by step the procedure found in
https://pixls.us/articles/create-lens-calibration-data-for-lensfun/ by andreas schneider on a pc with linux ubuntu 20.04.
In doing so, as far as vignetting is concerned, I calculated the correction for every aperture 1.4,2,2.8, 4,5.6,8,
11, 16 at a  distance of 0.5m, 1m, 3m, and inf.
Putting the lensfun.xml file into $HOME/.local/share/lensfun directory and using darktable, 
the correction of distortion, tca, and vignetting turned out to be absolutely satisfactory to me.
