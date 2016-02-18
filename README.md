### ErrorFreeArithmetic.jl
Arithmetic using errorfree transformations

```
     Jeffrey A. Sarnoff © 2015-2016                           
                                                    2016-Feb-18 12:08:00 UTC in New_York 
```


| function | arity | returns | eft |
|----------|-------|---------|-----|
|----------|-------|---------|-----|
| eftRecip |   1   | 1.0 ⧄ x | no  |
|----------|-------|---------|-----|

All functions exported from this module are prefixed "eft" [ErrorFree Transformation].  Most functions exported from this module actually are errorfree transformations.  Given the nature of floating point arithmetic, these functions cannot be errorfree transformations: eftRecip, eftDiv, and eftSqrt.  The implementations here behave very nearly errorfree, and they are as accurate as theory allows.  

Rather roughly put, an errorfree transformation is good to the last bit of the residual value, while the nearly errorfree transformations are reliable to the penultimate bit of the residual value.

