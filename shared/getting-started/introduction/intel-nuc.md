In this guide we will build a simple **{{ $language.name }}** web server project on an **{{ $device.name }}**. 

__Note:__ The Intel NUC image provides generic x86 device support. While the instructions below refer specifically to the Intel NUC device, you can follow the same steps to provision other devices with an x86 architecture.

At its most basic, the process for deploying code to an **{{ $device.name }}** consists of two major steps:

- Setting up your **{{ $device.name }}** with resinOS, the host OS that manages communication with resin.io and runs the core device operations.
- Pushing your **{{ $language.name }}** project to the resin.io image builder, which pulls in all necessary dependencies and creates the container image for your application.

Once these steps are finished, your **{{ $device.name }}** will download the container image, kick off your application, and begin sending logs to your resin.io dashboard!


