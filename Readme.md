## Poisson Image Editing

William Emmanuel
Computational Photography Project
Combines a source image, target image, and mask to create a content-aware blend.


Based on Patrick Perez, Michel Gangnet, and Andrew Blake's original paper on Poisson Image Editing
http://www.cs.virginia.edu/~connelly/class/2014/comp_photo/proj2/poisson.pdf

![source](https://raw.githubusercontent.com/willemmanuel/poisson-image-editing/master/input/2/source.jpg) + 
![mask](https://raw.githubusercontent.com/willemmanuel/poisson-image-editing/master/input/2/mask.jpg) + 
![target](https://raw.githubusercontent.com/willemmanuel/poisson-image-editing/master/input/2/target.jpg) = 
![result](https://raw.githubusercontent.com/willemmanuel/poisson-image-editing/master/output/2/result.png)


USAGE:
vagrant up && vagrant ssh

python main.py

Dependencies: numpy, scipy.sparse, opencv

Place a target image, source image, and mask image in a directory in /input.
One directory is needed per image group to be processed.
The result will be placed in the /output directory

NOTE: To process the 3 examples provided in /input, this program takes about 35 seconds.
