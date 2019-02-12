IMPORTANT
---
    Current version: 3.3578.1860
---


1. BEFORE BUILD PACKAGE:

    To reduce the source files size submited to github, please copy the CEF runtime lib files to theses folder.

    * For x86, copy Release and Resources folders to ./build/cef

    * For x64, copy Release and Resources folders to ./build/cef64

    CEF Runtime builds: http://opensource.spotify.com/cefbuilds/index.html

2. BUILD

    Run Command
    ```bash
    nuget pack Unofficial.ChromiumFx.for.Integration.nuspec
    ```

3. Testing

    You need to add the directory which contains the package as a NuGet Package Source. In Visual Studio do the following

    * Tools -> Options
    * Package Manager -> Package Sources
    * Add the file system location and hit "Update"

    After this the local package should appear in the Package Library Manager

    See also [Link](https://stackoverflow.com/a/15749728/6229797).