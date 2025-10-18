---
generator: doxide
---


# Array3D

**template&lt;typename Type&gt; class Array3D**

Helper class to handle 3 dimensional arrays.

!!! note

    Stores a flat C array.


## Functions

| Name | Description |
| ---- | ----------- |
| [Resize](#Resize) | Resizes the array in all three axis. |

## Function Details

### Resize<a name="Resize"></a>
!!! function "void Resize(uint32 SizeX, uint32 SizeY, uint32 SizeZ)"

    Resizes the array in all three axis.
    
    
    !!! warning
    
        Resize will delete all currently stored data and create a new array.
    

