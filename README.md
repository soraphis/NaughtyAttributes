# NaughtyAttributes
NaughtyAttributes is an extension for the Unity Inspector.

It expands the range of attributes that Unity provides so that you can create powerful inspectors without the need of custom editors or property drawers. It also provides attributes that can be applied to non-serialized fields or functions.

It is implemented by replacing the default Unity Inspector. This means that if you have any custom editors, NaughtyAttributes will not work with them. All of your custom editors and property drawers are not affected in any way.

## System Requirements
Unity 2018.3 or later versions. Feel free to try older version. Don't forget to include the NaughtyAttributes namespace.


## Installation 2018.3+

go to your projects `Packages/manifest.json` and add this:

     "dependencies": {
        ...
        "de.soraphis.naughtyattributes": "https://github.com/Soraphis/NaughtyAttributes#2019.03",
        ...
     }

## Documentation

You can find the documentation in the [repository wiki](https://github.com/soraphis/NaughtyAttributes/wiki/Drawer-Attributes)