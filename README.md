# 380v9mmSorter
A 3D printed bullet casing sorter for separating 9mm from .380 

All printed parts were printed in polymaker PLA+ with 3 perimiters and 15% infill. I used the "organic" supports
in the latest alpha build of PrusaSlice https://github.com/prusa3d/PrusaSlicer/releases/  to avoid supports causing 
parts to have unnessesary roughness. 

I printed the main sorter body oriented upright with the face of the .380 outlet down on the build plate. 
This gave me the best print quality results. 

POC video - https://youtu.be/RARQG4GygJQ

This project is not in a tested nor final form, expect things to change as problems are identified and addressed. 

Here is a list of all of the non-printed parts I have used for this project:

Motor - https://www.amazon.com/gp/product/B07XMFLSPB/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1

Power Jack - https://www.amazon.com/gp/product/B08CMMQMP6/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&psc=1

Wire - https://www.amazon.com/gp/product/B07F111X9J/ref=ppx_yo_dt_b_asin_title_o04_s00?ie=UTF8&psc=1

Power adapter - https://www.amazon.com/gp/product/B08GCMJH31/ref=ppx_yo_dt_b_asin_title_o06_s01?ie=UTF8&psc=1

Power Switch - https://www.amazon.com/gp/product/B0BCV7V3RQ/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1

Tenetive Addition:
RC car shock absorber - https://www.amazon.com/gp/product/B0BLC4NCK9/ref=ewc_pr_img_3?smid=AJ0RJEXY6CYX2&psc=1

I am experiencing an intermitant feed failure where the case does not fall in time and gets mashed by the plunger. 
I have ordered a couple of these shock absorbers to replace the crank shaft to see if I can remedy the failure by 
allowing the motor to complete its rotation by compressing the shock absorber I hope this will additionally prevent 
the machine from breaking itself or from deforming the jammed case. 

Please note that I made a decent effort to make things parametric and I definitly failed on the sorter body
but I redesigned the enclosure so that it is fully parametric to endusre that people could easily swap in 
different power jacks, buttons, etc. with ease. I built mine using all parts I had laying arround from other projects
and wanted to ensure that the greatest number of people could do the same. 

### Hardware
M3 hardware is used everywhere expect on the motor. M2 is used on the motor both for mounting and as a cross pin
 to hold the wheel to the motor shaft.

I used a flat washer on each side of the crank shaft to reduce friction and use a drop of locktite to 
keep the nut from walking itself off. maybe I can work on embedding a nylock nut and shoulder bolt or something
in the future but this is were its at now. 