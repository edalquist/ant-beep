Ant Beep
===============

About
-----

*Ant Beep* generates a terminal bell when the build completes. One bell for a successful build and
two for a failed build.


Installing
--------

    mvn clean package
    mkdir -p ~/.ant/lib
    cp target/*.jar ~/.ant/lib

    
Configuring Ant
--------

In your shell profile (.profile, .bashrc, ...) add the following line:

    alias ant='ant -logger net.ebd.util.ant_beep.BeepListener'

Copyright
---------

Copyright (c) Eric Dalquist
