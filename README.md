ACCESS-CM 1.0 Compilation Scripts
=================================

On Accessdev download the source code to the current directory with

    ./extract-accesscm10

Copy the source code to Gadi with e.g.

    rsync -av ./ gadi:/scratch/$PROJECT/$USER/accesscm10

On Gadi go to that directory and run

    ./build-accesscm10

The resulting executables will be put in ./bin

To run the model see the instructions at http://climate-cms.wikis.unsw.edu.au/ACCESS1.0_CMIP


