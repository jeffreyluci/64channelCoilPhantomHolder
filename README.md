# 64 Channel Coil Phantom Holder for FUNSTAR Phantom
Development resources for creating a FUNSTAR phantom holder for a Siemens 64 channel Head/Neck coil

The analysis I perform for QA monitors individual coil elements, and the phantom's position in the coil affects loading and sensitivities of all the elements. Placing the phantom reproducibly within the coil housing enables more rigorous monitoring and comparison of long-term metrics. To that end, I have used CAD files of the coil housings to create my custom phantom holders. Unfortunately, having just moved to Rutgers and switching to a Prisma, my primary coil for QA is now the 64 channel head/neck. Previously, I had used the 32 head. Snice I don't have, and didn't want to wait for the (approximately) 284 lawyers it takes to obtain the CAD files for this coil, I acquired a high resolution CT of the coil housing, and modeled the surface in AutoCAD Inventor. From that, I created a holder that meshes with the surface of the coil, and has a shperoid cutout that matches the Funstar outer diameter.

A few caveats. This phantom holder is in direct contact with the coil housing and does not provide any effective vibration mitigation measures. I am still trying to rigorously characterize the mechanical vibrations, and how much they affect the results of QA (if at all). I am also trying to get the CAD files for the 64 channel head/neck coil. If/when I am able to do that, I will create a revised version of this holder and update this posting.

I 3D printed the holder on an FDM printer using ABS as the filament material. My plan was to use this print as a prototype to see if my modeled coil surface needed any significant tweaks to resolve mismatched features. Once those tweaks were made, I would reprint the holder using a SLA or SLS printer. While placement of the center of the phantom ended up off center by about 2 mm, I was very pleased with the surface matching, and decided that I didn't need to improve upon the design or material.

The coil was printed with the flat surface down. That left the phantom mating depression quite rough from lack of enough supports. However, using a Dremmel tool on medium speed with a polishing wheel cleaned it up very nicely. That process took only a few minutes. I recommend wearing a mask for this part of the process to prevent inhaling any ABS dust. I sure hope you can find a facemask somewhere. 

I coated the coil and phantom mating surfaces with (please don't laugh) Flex Seal spray. (I figured if it's good enough to float a fishing boat . . .) I used 8 coats for the coil mating surface, and 5 coats for the phantom side. The rubberized surface provides excellent grip to prevent sliding, yet leaves no sticky residue or discoloration of the coil or phantom. I plan on peeling off the Flex Seal coating to reapply when/if it becomes brittle or loses its grippy properties. It peels off easily from the ABS, but it adheres strong enough that I'm not overly concerned about durability under normal use.

I have attached a zip file with photos of the holder after printing at various stages of finishing. I chose to mask off the flat surface of the holder, but if I had it to do over again, I wouldn't do that. It was unnecessary, and I probably reduced the lifetime of the rubber by creating "sharp" edges where the rubber could peel. The photos of the holder in the coil are a little misleading. The rubber intentionally curls up just a bit around the surface, and that makes it look as though there is a shadow indicating a gap between the holder and the coil surface. There isn't one. It's a very tight fit.

I have also attached STL files. One at "low" resolution for FDM printers, and one at "high" resolution for SLA or SLS printers. I used the FDM printer version, and its "smoothness" is more than adequate after rubberization. 

Finally, I have attached the AutoCAD Inventor model I created that subsequently produced the STL files. DM for my Venmo for gratuities!

I hope these help you, and if you have questions or need help using these resources, feel free to contact me. I'm always happy to help and collaborate.

## LICENSE TO USE

All information contained in this reposiroty is copyrighted by Jeffrey Luci, 2021. Jeffrey Luci grants non-exclusive, revoakble license to use the information contained in this repository to all persons for non-commercial use. Works using information in this respositry (including those that build upon or improve the design) in publication or presentation must reference this repository formally, in accordance with the accepted practices, procedures, and styles of the relevant publishing entity. **ALL** commercial use must be separately and individually licensed from Jeffrey Luci.

## DISCLAIMERS

The information and technical files provided by Jeffrey Luci on this repository is for general informational purposes only. All information in the repository is provided in good faith, however I make no representation ot warranty of any kind - express or implied - regarding the accuracy, adequqcy, validity, reliability, availability, appropriateness, or completeness of any information in this repository.

Your access to and use of the information in this repository or any of its content is at your own risk. Jeffrey Luci is not responsible or liable for any damages arising or resulting from use of this repository or use or inability to use the repository or any information contained in it, or from any action or decision taken as a result of using this repository.
