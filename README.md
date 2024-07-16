<div align="center">
  <img src="https://github.com/jean0t/archon/assets/127698173/835e829d-7707-4925-bc14-6fed239b2700" alt="cat" width="150px">
  <h1>ARCHON PACKAGE MANAGER</h1>
  <h2>A minimalist low level package manager for your linux</h2>
</div>
Created entirely in Bourne Shell, it is guarateed portability with all unix systems.  
Manipulates its own extension `.archon`  

Wants to create your own linux distro and want a low level package manager with its custom type of package? Why not use Archonpkg? It offers all you need to install packages, from creating to installing.

## How to use

### creating a package
You use the command:
```
createpkg -c <name of the package>-<version>-<build>.archon
``` 

### installing a package
you use the command:
```
installpkg -i <name of the package>.archon
```
## Creator: Jean0t
