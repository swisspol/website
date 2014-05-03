---
name: Pol Versioning System
image: pol-versioning-system.jpg
release: August 2002
---

PolVersioning is a developer tool for Project Builder that automatically stores build information into a file inside the resulting package.

The created file has the name "PolVersionInfo" and will be created in the resources folder of the package. Since it is stored as a .plist, you can extract the information easily with Cocoa methods.

- The file contains the following information:
- build date,
- build number (incremented by 1 each time you make a build),
- the full name of the user who did the build,
- the product name.
