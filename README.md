# kapt-cli
A tool for invoking the **Kotlin Annotation Processor** (kapt) from the command line. This project is a work in progress.

## Requirements
Kotlin 1.1.3+

### Directions:
1. Modify the `args` file and provide values for all variables. (TODO: provide more description)
2. Modify the `module-template.xml` file and add values. (TODO: provide an xml generator for fields set in `args`)
3. Patch your `kotlinc` file to add java `tools.jar` to the compiler classpath. (TODO: provide this as an arg)
4. *Optional*: If you've run step 4 previously, you may choose to run `./clean` to start fresh.
5. Invoke `./kapt`. (TODO: complete all steps)

### References
https://kotlinlang.org/docs/reference/kapt.html

https://stackoverflow.com/questions/45217399/how-to-use-kapt-from-command-line-with-kotlinc

https://github.com/facebook/buck/issues/956
