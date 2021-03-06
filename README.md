cannonball-pkgsrc
=================

NetBSD [pkgsrc][3] script for Cannonball: An Enhanced OutRun Engine.

You can find Cannonball [here][1]

Installation
------------

Copy `emulators/cannonball` folder to `/usr/pkgsrc` directory.

NOTE: If your pkgsrc directory is different from above, copy to the respective
place.

Usage
-----

Once you have copied the folder, install it as you would do for any port.

`$ cd /usr/pkgsrc/emulators/cannonball`<br>
`$ make install clean`

For a list of dependencies for the build check [here][2]

NOTE: If you are using pkgsrc in a non NetBSD system, replace `make` with
`bmake` in the above example.

Credits
-------

* Cannonball is developed and maintained by Chris White and Arun Horne.
* Thanks to `nia@` for  suggesting fixes to the package.

License
-------

BSD 2-clause. See LICENSE.

[1]: https://github.com/djyt/cannonball/wiki
[2]: https://github.com/djyt/cannonball
[3]: http://www.pkgsrc.se/emulators/cannonball
