# EPSG-WKT2
Repository to hold archives of the EPSG WKT dataset to be used in [CoordRefSystems.jl](https://github.com/JuliaEarth/CoordRefSystems.jl/)

CoordRefSystems uses DataDeps.jl to grab the `zip` from here. Individial files are then accessed on-demand.



### Steps to update the dataset to the latest version
1. **Login** to [epsg.org/download-dataset.html](https://epsg.org/download-dataset.html)
2. **Download** an updated version of the WKT dataset (for example `EPSG-v12_004-WKT.Zip`)
3. **Rename** the file to `EPSG-latest-WKT.Zip`
   - Note: this name is hardcoded in CoordRefSystems.jl so they need to match
5. **Commit** it with a message such as `Update dataset to v12_004` 

