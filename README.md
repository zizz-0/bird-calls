### How to: Build, compile & run

> sh run main

#### Note that the run.sh file might not be executable

- If not executable then

    > chmod +x run

*Edit shell script for custom target to be launched*

The file binary file "main" comes from source/CMakeLists.txt

> "add_executable(**main** main.c)"

#### Note: Math has been linked to target "main" by default
> target_link_libraries(sharedLibrary INTERFACE ${MATH})
