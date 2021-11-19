The LensedSN124imagesLCs repository contains the code and data accompanying the manuscript 
"Out of One, Many: Distinguishing Time Delays from Lensed Supernovae", arXiv:2109.13282 
by Mikhail Denissenya, Satadru Bag, Alex G.~Kim, Eric V.~Linder, Arman Shafieloo.


* LCSimulator_MultiImage.ipynb is the main script used to generate the lightcurves of strongly lensed supernovae in the article.


* gslsne_data.zip includes 300  simulated  lightcurves  of  1, 2, and 4  image  systems in g, r, i bands.
Each file starts with a header listing the number of images n_image in the system. The lightcurve data are organized in columns:


1st col - observation time


2nd col - total flux (+noise)


3rd col - total flux measurement errors


4th col - 1st image flux


5th col - 2nd image flux (for n_image>1)


6th col - 3rd image flux (for n_image>2)


7th col - 4th image flux (for n_image>2)



Contact email: mikhail.denissenya@nu.edu.kz


