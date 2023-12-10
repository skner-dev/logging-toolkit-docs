# Examples

## Overview

The logging toolkit package comes with a demo that contains examples on how to use the tool. 

To access the demo project, navigate into the Package Manager. In the Logging Toolkit's entry, find the project in the Samples tab and import it:

![Importing the demo sample](/images/demo-import.png)

## Logging Examples

In the demo project, a SampleScene exists with the following objects:

- __Player__: Contains a PlayerController script to allow for 2D movement.
- __3 Collision Boxes__: Represent the default log levels, used in the demonstration.
- __Main Camera__: just a camera.

The Player object contains the following scripts:

- __PlayerController__: Used to control the movement and a collision check to trigger log calling.
- __GameObjectLogger__: An instance of the [GameObjectLogger](loggers/game-object-logger.md) logger type.

The __PlayerController__ will make three separate calls to all the available logger types. These are created and used in the script. They provide a functioning example on how the logging toolkit can be setup.

Refer to the documentation in the [loggers](loggers) folder for detailed instructions on how to configure and use the different logger types.

## Resource Examples

The demo project also contains example logging resources (ScriptableObjects). These resources contain:

- An example logger settings instance.
- Three sample output settings for the different natively supported file types.

These might be useful in what to consider when creating your own settings. 

Refer to the documentation in the [settings](settings) folder for more information on these settings.