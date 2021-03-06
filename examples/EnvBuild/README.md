## Customizable Environment Binary Files 
This folder contains the following Unity3D environment builds: 
- [DroneDelivery](./DroneDelivery.md) - the agent is a drone trying to deliver a package.
- [SafeDroneDelivery](./SafeDroneDelivery.md) - a variation of the DroneDelivery environment that ensures
safety from collisions.

Each environment is configurable with a [`env_config.json`](./env_config.json) file. 

You can dowload pre-compiled binaries from the [Release section](https://github.com/IBM/vsrl-examples/releases/tag/v0.1)

## Configuration file location
The config file must be placed in a different folder according to the architecture:
- MacOS. The config file must be in the same directory as the compiled Unity Scene. 
- Linux. The config file must be in the directory where the python script is executed.

You can find example python scripts running the Unity environments in [`../unity-simple-examples/`](../unity-simple-examples).
