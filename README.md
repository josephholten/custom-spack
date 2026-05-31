# custom-spack

my custom spack packages

## packages

- petsc: adds new pastix variant

## usage

clone repo somewhere, then `spack repo add <PATH/TO/REPO> <NAME>`
to verify it was picked up do `spack repo ls` to list all found repos and their search order
if the `pastix` variant is picked up, then clearly the correct package is selected

use

`spack spec -N petsc +pastix`

to test if the pastix variant can be concretized and in which repo it is located
