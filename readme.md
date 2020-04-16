# Pure data subpatch cloner
Using dynamic patching, it creates a subpatch that contains sevreal copies of you original subpatch, wired to inlets and outlets, in a similar way to the [clone] object. Usefull if you quickly need several instances of a subpatch without having to create an extra-abstraction for that.

### instructions : 
* put this folder in your 'externals' folder for puredata
* open pdc-help.pd

Update ! Support for both signal or control inlets / outlets in the subpatch.


before :

<img src="https://raw.githubusercontent.com/jyg/pdc/master/pd-clone.jpg" alt="pd-clone.jpg" >


after :

<img src="https://raw.githubusercontent.com/jyg/pdc/master/pd-cloned.jpg" alt="pd-cloned.jpg" >
