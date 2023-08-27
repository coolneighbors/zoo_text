# Backyard Worlds: Cool Neighbors #

## Our Mission ##
Through this project, we hope to identify brown dwarfs in the Sun's local cosmic neighborhood. By studying these objects, we will learn more about giant exoplanet atmospheres, the star formation process, what compounds are prevalent throughout the galaxy, and how the composition of proto-stellar material shapes the development of stars in our galaxy.

Together we can discover new nearby cool neighbors of the Sun, known as [brown dwarfs](+tab+https://en.wikipedia.org/wiki/Brown_dwarf). Through the use of telescope data and the human brain's ability to distinguish patterns with relative ease, we can identify real brown dwarfs hidden among other stars, galaxies, and detector noise.

Brown dwarfs are celestial objects with masses in between those of stars and those of giant planets like Jupiter. Below is an artist rendering of a brown dwarf. You can think of them like oversized versions of Jupiter, but floating around all alone in interstellar space rather than orbiting a star.

![Artist’s_conception_of_a_brown_dwarf_like_2MASSJ22282889-431026.jpg](https://panoptes-uploads.zooniverse.org/project_attached_image/7d011f5f-be97-4e93-8132-37788ea7b023.jpeg =1000x550)
*(Credit: NASA/JPL-Caltech)*

Unfortunately, finding examples of [Y dwarfs](+tab+https://en.wikipedia.org/wiki/Brown_dwarf#Spectral_class_Y) -- the coldest known class of brown dwarfs -- has posed a major bottleneck for this line of research. These objects are incredibly faint, and as a result, we have to look for ones close to our solar system, where they will appear the brightest. 

Using machine learning algorithms, we identified a number of locations across the WISE database that appear to have some degree of movement. However, these algorithms  can be tricked by artifacts like detector noise and diffraction spikes. The most efficient way to vet these potential brown dwarf candidates is by utilizing the power of citizen science to analyze huge amounts of data in a short amount of time.

## Why should we care about brown dwarfs? ## 
Brown dwarfs are celestial objects that exist in between the size of planets and stars, often characterized as "failed stars." These objects have masses between that of Jupiter and the lowest mass hydrogen-fusing stars, resulting in them sharing properties with both stars and exoplanets!

Stars are celestial bodies with sufficient mass such that the gravitational pressure of their interiors is strong enough to support hydrogen fusion - the reaction that causes stars like our Sun to shine, or in technical terms, emit visible light. Their light makes stars relatively easy to find in space. Planets, on the other hand, do not have enough mass to sustain fusion of any kind, and do not emit their own visible light, making them very difficult to detect. Brown dwarfs ride this boundary between planet and star, having too little mass to sustain hydrogen fusion, but still having enough mass to glow faintly from their formation (making them invisible to the human eye). They do, however, emit light in the [infrared](https://en.wikipedia.org/wiki/Infrared) which we can detect using specialized telescopes!

The atmospheres of brown dwarfs are very similar to those of giant exoplanets, but can be observed in detail without the glare of a much brighter host star interfering. These brown dwarf atmospheres show strong signatures of water and methane, which are important molecules for the development of the organic compounds we see on Earth. Some brown dwarfs may even be rogue planets that were ejected from their original star system! Exploring these objects can provide valuable insights into the formation of other star systems and the abundance of various compounds across the universe.

**Because brown dwarfs are so dim, it's possible that there could be an as-yet overlooked brown dwarf closer to us than Proxima Centauri!** (Proxima Centauri is the nearest known star to our Sun). This would be a historic discovery, and you could be the first one to spot it!

In the Backyard Worlds: Cool Neighbors project, we search for brown dwarfs in infrared images taken by NASA's [Wide-field Infrared Survey Explorer](+tab+https://en.wikipedia.org/wiki/Wide-field_Infrared_Survey_Explorer) (WISE) telescope. The WISE satellite and telescope was launched in 2009, and continues to help us learn more about the origin of exoplanets, stars, and galaxies throughout our universe. 

![NEOWISEinOrbit.jpg](https://panoptes-uploads.zooniverse.org/project_attached_image/35b2f534-47c3-472b-bf24-9a0e4ceb213d.jpeg =1000x500)
*(Credit: NASA/JPL-Caltech)*

**[Watch the launch of the WISE telescope here!](+tab+https://www.youtube.com/watch?v=45NAENHol24)**


# Discovering New Neighbors of the Sun #

## Brown Dwarfs are Rare! ##

Compared to normal ("main sequence") stars and galaxies, and even image artifacts, brown dwarfs are very rare. For instance, WISE has detected billions of galaxies and normal stars, but probably only a few thousand brown dwarfs. To discover a new brown dwarf, you'll likely need to look through roughly 100-500 flipbooks. Approximately 10% of our flipbooks contain previously discovered moving objects, to help you get a sense for what a real mover will look like and to help our research team understand the accuracy of classifications we receive.

## Proper Motion of Celestial Bodies ##

Brown dwarfs are cold and dim, so they can only be detected when nearby to us. All inhabitants of the Milky Way Galaxy are moving relative to the Sun. However, we perceive the objects close to us as moving much faster than ones farther away. For an example of this effect you can try right now, take your finger and put it about 10 inches from your eyes. Close one eye, and move your finger about 6 inches from left to right. Now, take your finger and extend it as far away from your eye as you can. Move it the same 6 inches from left to right again.

You should be able to see that your finger appears to move a larger angular distance when it is closer to you than when it is farther away. Essentially the same thing is happening with brown dwarfs, but on the scale of light years rather than inches!

[**Barnard's Star**](+tab+https://en.wikipedia.org/wiki/Barnard%27s_Star) is a red dwarf star relatively close to the Earth at a distance of approximately 6 lightyears. As such, it has a fairly high apparent motion. Here's what Barnard's Star looks like in telescope data:
![Barnard2005.gif](https://panoptes-uploads.zooniverse.org/project_attached_image/6e25937e-8173-4f96-9ecb-d06e1aa84b50.gif)

Note that the above animation is on a loop; Barnard's star doesn't actually "jump backward" at any point, it just keeps moving along essentially a straight line trajectory.

For a star moving at a speed v perpendicular to our line of sight with a distance d from Earth, the angular velocity is proportional to
![Proportionality.png](https://panoptes-uploads.zooniverse.org/project_attached_image/883f20e4-339a-4686-8d30-a11cc3679e55.png)

Here, v would be in units of distance over time (like m/s or km/s), d is the distance between us and the star (in units like light years) and μ is the rate of apparent motion across the sky, which astronomers refer to as [proper motion](+tab+https://en.wikipedia.org/wiki/Proper_motion). Proper motion has units of angular displacement per unit time. It turns out that the convenient unit of proper motion for nearby stars is [arcseconds](+tab+https://en.wikipedia.org/wiki/Minute_and_second_of_arc) per year, where one arcsecond is 1/3600th of a degree. Barnard's Star has the highest proper motion of any currently known star or brown dwarf, at roughly 10.4 arcseconds per year. It is possible that through searches like Backyard Worlds: Cool Neighbors, we could discover a speedy brown dwarf that breaks this proper motion record!

### Parallax ###

The apparent movement of nearby stars is usually dominated by proper motion, but there is also another component of their trajectories across the sky called "[parallax](+tab+https://en.wikipedia.org/wiki/Parallax)". Parallax measures the annual perceived "wobble" of the nearby star or brown dwarf caused by the Earth's motion around the Sun.

Catalogs (such as Gaia) often quote parallax in units of milliarcseconds. The conversion from parallax in milliarcseconds to distance from the solar system in parsecs is as follows:

distance in parsecs = 1000 / (parallax in milliarcseconds)

**A large parallax means that an object is nearby, and a small parallax means that an object is distant.** A parallax value of 50 milliarcseconds corresponds to a distance of 20 parsecs (~65 light years) from the solar system, which would be very nearby by astronomical standards. A parallax of 5 milliarcseconds (sometimes abbreviated as "mas") corresponds to a distance of 200 parsecs. Generally, for Cool Neighbors, we are most interested in dwarfs that are within a distance of ~100 parsecs of the solar system.


## Temperature and Color ##

If you've looked at the night sky, you've probably noticed that stars come in different colors. The color of a star is indicative of its temperature. A blue/white looking star is relatively hot, while a cool star star (say, a red dwarf like Barnard's Star) will look more red/orange in color. The light emitted by an object due to its temperature is known as [blackbody radiation](+tab+https://en.wikipedia.org/wiki/Black-body_radiation).
This phenomenon isn't just limited to stars though. Your typical incandescent lightbulb works the exact same way -- electricity causes the filament inside the bulb to heat up to around 2300 degrees Kelvin and it emits blackbody radiation in the visible spectrum (for reference, the Sun has a surface temperature of 5800 degrees Kelvin). Objects don't have to be thousands of degrees to emit light though - the human body is warm enough to emit light too! However, the light you (and other cooler objects like brown dwarfs) emit is in the infrared wavelength range and is outside humans visual spectrum. 

![BlackbodySpectrum_gif.gif](https://panoptes-uploads.zooniverse.org/project_attached_image/34ae2391-c89b-4a1b-9e0e-b3cc59fd1194.gif =1200x300)

Thankfully, modern wide-area surveys like WISE (and its extension, [NEOWISE](+tab+https://www.jpl.nasa.gov/missions/neowise)) are sensitive enough to detect brown dwarfs in the ~3-5 micron wavelength range where they emit light most strongly. So, the data you will be analyzing in Cool Neighbors aren't visible light pictures like you might take using a normal camera, they are actually capturing light that would be invisible to human observers. The data is then transformed to visible light through data manipulation, where we can then analyze them easily.

## More Information ##

For more information about the science of brown dwarfs and how we detect them, be sure to check out the [FAQ](https://www.zooniverse.org/projects/coolneighbors/backyard-worlds-cool-neighbors/about/faq) section.

***We hope you make a big discovery!***

## Acknowledgments ##

Thanks to NASA, which has funded this work through the Citizen Science Seed Funding Program, Grant 80NSSC21K1485.

The work of Cool Neighbors personnel has been supported by NOIRLab, which is managed by the Association of Universities for Research in Astronomy (AURA) under a cooperative agreement with the National Science Foundation.

Backyard Worlds: Cool Neighbors makes use of the [WiseView](+tab+https://ascl.net/1806.004) image cutout tool.
