# freelap
These options only apply when rebuilding the base system and kernel. Make sure to compile your kernel using:

    make buildkernel KERNCONF=GENERIC-NODEBUG

You'll need to install the packages for some of those daemons. Install the following:

    print/cups
    audio/sndio
    multimedia/webcamd
