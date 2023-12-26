# Notes About Button Textures

## Missing from HD pack

684b95069f2af7e9-c6020d54a1daeab3-00005553
c90794d0f0988ac2-99f532662aa4f3aa-00005593

## Fixing UI Sign Aspect Ratio

* Resize canvas to 512x512 and center the image
* Rotate the sign layer (which should be 256x256) 45 degrees
* Resize the sign layer to 428 pixels width, leave height alone
* Rotate the sign layer -45 degrees back to original position
* Resize canvas back to 256x256
* Resize layer to image
* Filters > Enhance > Sharpen, set Amount to 1.0, leave rest default
* Export as DDS DXT3
