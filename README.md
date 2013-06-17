
Freedesktop's Tango! icon set
-----------------------------

Plugin page: [http://artifacts.griffon-framework.org/plugin/tangoicons](http://artifacts.griffon-framework.org/plugin/tangoicons)


Provides a shortcut for adding icons based on Freedesktop's [Tango! icon set][1].

Usage
-----

The following nodes will become available on a View script upon installing this plugin

| *Node*    | *Property* | *Type* | *Default*   | *Bindable* |
| --------- | ---------- | ------ | ----------- | ---------- |
| tangoIcon | icon       | String |             | no         |
|           | size       | int    | `16`        | no         |
|           | category   | String | `actions`   | no         |

Valid values for `icon` can be obtained by running **tango-icon-selector** and inspecting the tooltip of the chosen icon.

Valid values for `size` property are: 16, 22, 32.

Valid values for `category` property are: actions, apps, categories, devices, emblems, emotes, mimetypes, places, status.

Scripts
-------

 * **tango-icon-selector** - launches a window that displays all available icons (Hover an icon to see the icon name)

[1]: http://tango.freedesktop.org/Tango_Icon_Library

