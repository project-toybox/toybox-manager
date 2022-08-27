<p align="right">
<img alt="GitHub" src="https://img.shields.io/github/license/project-toybox/toybox-manager">
</p>

<p align="center">
    <h1 align="center">
        <img src="https://raw.githubusercontent.com/project-toybox/toybox-assets/main/images/toybox-icon.png" width="50" height="50">
        <p>Toybox Manager</p>
    </h1>
    <p align="center">A high-performance game compressor for adults.<br>Let's clean up your toys!</p>
    <br>
</p>

## Build
1. Open a '__Developer PowerShell for VS 2022__' from the solution root.
2. Run this command.
```
[x86]
dotnet publish Toybox.Manager\Toybox.Manager.csproj /p:PublishProfile=Toybox.Manager\Properties\PublishProfiles\x86.pubxml

[x64]
dotnet publish Toybox.Manager\Toybox.Manager.csproj /p:PublishProfile=Toybox.Manager\Properties\PublishProfiles\x64.pubxml
```
3. A built application will be stored in '__/Toybox.Manager/bin/publish__'.

## Usage
[View the documentation](README.md) for usage information.

## License
The contents are available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
