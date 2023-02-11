**clean all sub modules**
```groovy
allprojects {
    task cleanBuildDir(type: Delete) {
        delete "${projectDir}/build"
        delete "${projectDir}/out"
    }
}
```