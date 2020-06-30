# Vue Color

This bundle allows you to use vue-color components in your map.apps bundle
It uses xiaokaike's Vue Color Pickers: https://github.com/xiaokaike/vue-color

[vue-color Documentation](https://github.com/conterra/mapapps-vue-color/tree/master/src/main/js/bundles/vue-color)

## Development Guide
### Define the mapapps remote base
Before you can run the project you have to define the mapapps.remote.base property in the pom.xml-file:
`<mapapps.remote.base>http://%YOURSERVER%/ct-mapapps-webapp-%VERSION%</mapapps.remote.base>`

### Other methods to to define the mapapps.remote.base property.
1. Goal parameters
`mvn install -Dmapapps.remote.base=http://%YOURSERVER%/ct-mapapps-webapp-%VERSION%`

2. Build properties
Change the mapapps.remote.base in the build.properties file and run:
`mvn install -Denv=dev -Dlocal.configfile=%ABSOLUTEPATHTOPROJECTROOT%/build.properties`
