# OpeMM Feedstock controlled by Acellera

This is a partial fork of the conda-forge feedstock for OpenMM. The idea is to be able to make OpenMM releases
from specific commits without having to wait for Peter to make a new release which can take months.

I only build the openmm package for python 3.10 and cuda 12.0 which is what we mostly need for our apps.

To create a new release you need to:

1. Update the version in the meta.yaml file.
2. Update the git_rev in the source section to the desired commit.
3. Push your changes to the remote repository.
