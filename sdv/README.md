This is the location store the feature flags for the SDV (software defined vehicle) project.
Here we store the flags that are part of our `*s2a` & `trunk_staging` release configs.

Both of these release configs inherit from there AAOS counterpart:

`cs2a` -> `cp2a`
`trunk_staging` -> `trunk_staging` (here we rather extend the `trunk_staging` config with the SDV feature flags)

These feature flags are then used in the SDV devices defined in `device/google/sdv`.
