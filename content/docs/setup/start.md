---
title: "Start Application"
date: 2021-09-28T15:07:34+02:00
draft: false
---

# Starting the application

## Requisitions

- Unity Hub
- Unity 2020.3.14f1
- Steam
- Steam VR

## Preferred Way 

The game is found in the `Documents` folder of the pc. Double click it and everything should work. If Steam Vr is 
not starting up, start it up manually. For starting steam vr look into [SteamVR]({{< ref "/docs/setup/steamvr" >}}
"SteamVR").

## Build it yourself

If the Application executable is not available you can build and run it yourself. Start Unity Hub and you should 
find the project `BeamVR` under the projects in the menu.

![Unity Hub](/images/unity-hub.png)

Once the unity editor is open you can build the application under `edit > Build And Run`.

![Build and Run](/images/build-and-run.png)

It will ask you the location you want ot put the executable into and will build the application into this directory 
and run it.

## Not ideal way

If something is really not working you can just start it through the editor.
This should only be required when you are debugging a problem.

![Build and Run](/images/start-editor.png)
