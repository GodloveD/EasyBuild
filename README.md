# EasyBuild
An experimental approach to creating [Singularity](ttps://github.com/singularityware/singularity) containers using [EasyBuild easyconfig files](https://github.com/easybuilders/easybuild-easyconfigs).

Just make a new directory, copy an easyconfig file into that directory, copy the [build.def](/build.def) file to the same directory, cd to that location and finally `create` and `bootstrap` a Singularity container there. The contents of your easyconfig file will be executed inside the container to build and install your app within the Singularity image.   
