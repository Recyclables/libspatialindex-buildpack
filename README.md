# libspatialindex-buildpack

This installs libspatialindex on Heroku, which allows you to use geopandas, rtree, etc. with Python! The difference between this one and others that you might find on GitHub, is that I am pretty sure that this is the only one (that I could find, at least) that works with the [heroku-geo-buildpack](https://elements.heroku.com/buildpacks/heroku/heroku-geo-buildpack)

This is sort of the bare minimum to get things to work. I think that a better approach was started by @rodolfoocampo [here](https://github.com/rodolfoocampo/libspatialindex-buildpack), which installs the lib from osgeo instead of from some random s3 bucket, but I used the s3 artifact that @julianfr112 used [here](https://github.com/julienfr112/libspatialindex-buildpack) because it had the .so file that I needed, easily accessible.

