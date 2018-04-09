# ubuntu-artful-jupyter
A recipe for a Singularity container that uses Ubuntu Artful Aardvark to run Jupyter.

## Construction
Build the container with something like ```singularity build jupyter-artful.img Singularity```

## Invocation
Run ```singularity exec jupyter-artful.img jupyter notebook```

Visit the URL that is returned

## The Quicker Way
Run ```singularity run jupyter-artful.img```

Browse to the URL that is returned
