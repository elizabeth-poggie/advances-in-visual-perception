# Seeing Features and Objects 

### Edges in cave paintings, cartoons, children's art
- edges are important for recognition 
- first artworks are just edge drawings that reflect this importance (as well as these other examples)
- you can convey an object from just its outline

### Edges in processed images
- take 2 tone images (black and white). Use this to make a high-passed filtered image. edges on either side of the border have the same luminance but because of the lines shading, it appears different in luminance. 
- if we reverse the polarity of the edge, the image no longer looks as easily recognizable. 
- this is known as the Cornsweet illusion 

### Receptive field 
- the region of the visual space within which a stimulus will alter the firing rate of a neuron. 

### Receptive field in the Retinal Ganglion cells
- There are on center - off surround receptive fields as well as off center  - on surround receptive fields

### Receptive field in the Cortex - Simple cells
- elongated receptive fields that are orientationally selective. Many neurons combine to create this receptive field

### Receptive field - Response Profiles
- Circularly symmetric (in the retina and early stages of the cortex - an on or off center with an on or off surround)
- Odd Symmetric Oriented (on one side its excitatory and the other side is inhibitory)
- Even Symmetric oriented (even center and 2 inhibitory sides)

### Convolution of a even symmetric oriented receptive field
- zero crossing = the edge of a line 
- biphasic 
- the wider the field (tuned to lower SF) will create a wider biphasic response profile plot. in other words, the line that goes through the zero crossing will be less steep. 

### David Marr - Zero Crossings in filter output
- you can recognize an image by just a pattern of zero-crossings 
- the issue with the problem of zero crossings = you must work out where the crossings are (which requires lots of computations .... this is non trivial)

### Zero crossings at different scales
- if you use 3 different sizes of a circular symmetric filter to find crossings from an image, the larger sizes have less detail. 
- given that zero crossings are noisy, he came up with the spatial coincidence rule

### Spatial Coincidence Rule
1. if zero-crossings are spatially co-incident in the responses of 2 or more channels of different scales in the image, then this indicates the presence of a feature
2. if zero-crossings in course-scale channels are spatially coincident with zero crossings at finer-scale channels, then the features that you see are those represented in the finer scale channels. (as long as you have 2 channels which produce 0 crossings that are coincident then you are happy to choose the finer one to tell you that there is a feature there! We can see fine detail in images!)

... there is not a lot of evidence for this though!

### Blocked Image 
- Course quantification 
- takes a particular region and averages the luminance in that region to plot it over the whole of the square

### Blocked Image and Zero Crossing
- taking the zero crossings of a blocked image results in a smooth representation of the image with a wide scale.
- You gradually go from course to fine as you increase in scale. THe small scale zero crossings pick up all the details in the blocked image that are not important