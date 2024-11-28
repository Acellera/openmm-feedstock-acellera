# OpeMM Feedstock controlled by Acellera

This is a partial fork of the conda-forge feedstock for OpenMM. The idea is to be able to make OpenMM releases
from specific commits without having to wait for Peter to make a new release which can take months.

To create a new release you need to:

1. Update the git_rev version in the meta.yaml file in the source section to the desired commit.
2. Push your changes
