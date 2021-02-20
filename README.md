# SmoothRandom
This project is simply wrapping the [Perlin Noise](http://wiki.unity3d.com/index.php/Perlin_Noise) function from the [Unify Community Wiki](http://wiki.unity3d.com/index.php/Main_Page) into a DLL. Doing this allows use of the package within the [Elements Compiler](https://elementscompiler.com/elements/) without having to rewrite the script in Swift.

## Building
A reference to the UnityEngine library must be added for the project to build successfully. There should not be any issues with differing versions of the UnityEngine library, as it relies only on the Vector and Time classes.

## Documentation
Documentation for the project is found at the [wiki article](http://wiki.unity3d.com/index.php/Perlin_Noise).