# Getting Started

## Installation 

To start using the Logging Toolkit, simply import the package from the Unity Asset Store page. It should contain the package and the required Resource assets.

After the package import, include the namespace in one of your scripts:

```c#
using skner.LoggingToolkit.Loggers
```

This should automatically update your associated .csproj to have the following entry:

```xml
<Reference Include="skner.LoggingToolkit">
  <HintPath>Packages\com.skner.loggingtoolkit\Runtime\skner.LoggingToolkit.dll</HintPath>
</Reference>
```

This can also be included manually. The path for the .dll is the default as taken by the package import.

After this has been included, go to your project settings and find the Logging Toolkit's entry. If the resource files were not imported, the panel will display as follows: 

![Initial project settings view](/images/project-settings-initial.png)

This is because the Logging Toolkit requires two configuration files in the Resources folder to work properly. The location of these two resources are static and cannot be changed.

Click in both buttons to create it and the toolkit will generate these automatically with the default settings. They will be created in the Resources folder of your project:

![Location of the required resource files](/images/resource-files.png)
