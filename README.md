# Integration-Nugets
Some nuget projects I maintain


1. BUILD

    Run Command
    ```bash
    nuget pack <package name>.nuspec
    ```

2. Testing

    You need to add the directory which contains the package as a NuGet Package Source. In Visual Studio do the following

    * Tools -> Options
    * Package Manager -> Package Sources
    * Add the file system location and hit "Update"

    After this the local package should appear in the Package Library Manager

    See also [Link](https://stackoverflow.com/a/15749728/6229797).
