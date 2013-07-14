LN2D
====

An example container that shared [LN2D-Libraries] with other projects. 

For details on the library itself, please refer to [LN2D-Libraries].



[LN2D-Libraries]: https://github.com/yulan6248/LN2D-Libraries


Install
-------

1. clone this repo

    ~~~sh
    mkdir -p ~/Developer/LN2D
    cd ~/Developer/LN2D
    git clone --recursive https://github.com/yulan6248/LN2D
    ~~~

2. drag your cocos2d project into your workspace folder (`~/Developer/LN2D` for the example)
3. open `LN2D.xcworkspace` in Xcode
4. click on your project added just now, navigate to the **Build Phase** tab of the appropriate target, and add the libraries you need for in the **Link binaries with Libraries** phase
5. to import the right set of headers, you need to use the build settings included in the [LN2D-Libraries] project; take a look at the `BuildSettings/HeaderSearchPaths.xcconfig`, either apply these settings using Xcode's project and setting editor or make a new `.xcconfig` file and import these settings in your own project
