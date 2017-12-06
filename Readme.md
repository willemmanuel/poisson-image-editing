## Poisson Image Editing

William Emmanuel
Computational Photography Project


Based on Patrick Perez, Michel Gangnet, and Andrew Blake's original paper on Poisson Image Editing
http://www.cs.virginia.edu/~connelly/class/2014/comp_photo/proj2/poisson.pdf

USAGE:
vagrant up && vagrant ssh

python main.py

Dependencies: numpy, scipy.sparse, opencv

Place a target image, source image, and mask image in a directory in /input.
One directory is needed per image group to be processed.
The result will be placed in the /output directory

NOTE: To process the 3 examples provided in /input, this program takes about 35 seconds.
