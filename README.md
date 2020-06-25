# melonloader-getting-started

This is a quick guide to getting up and running for developing mods to be used with [MelonLoader](https://melonwiki.xyz/#/) for [VRChat](https://vrchat.com/). I am not in any way affilliated with either VRChat or Team Lava. Note that modifying your game client 'via any method for any reason' is a bannable offense in VRChat, but has historically not been punished consistently. Thank you to (Hector Panzer)² of the [VRChat Modding Group Discord](https://discord.gg/rCqKSvR) for providing me with this information as well as some of the screenshots.

## Installation

### Visual Studio

Download and install [Visual Studio](https://visualstudio.microsoft.com/). Make sure to have the `.NET desktop development` workload selected, and the highlighted `individual components` enabled. 

![Workload selection](/images/workloads.png)

![Individual compoments selection](/images/individual-components.png)

### MelonLoader

Installation instructions taken from [MelonLoader Wiki](https://melonwiki.xyz/#/?id=getting-started). Download and install the [Microsoft Visual C++ 2015-2019 Redistributable](https://aka.ms/vs/16/release/vc_redist.x64.exe). Download [MelonLoader.zip](https://github.com/HerpDerpinstine/MelonLoader/releases/latest/download/MelonLoader.zip) and extract its contents into the VRChat game folder.

The game folder should now look like this:

![VRChat game folder](/images/post-extract.png)

## Setting up the environment

Run VRChat once to let MelonLoader extract the information we will need for development. Wait for it to finish doing so, then close VRChat. In Visual Studio, create a new project using the settings depicted below.

![Visual Studio project settings](/images/new-project.png)

Next, we need to add the references that MelonLoader generated before. They can be found at `VRChat\MelonLoader\`, `VRChat\MelonLoader\Managed\`, and `VRChat\MelonLoader\Dependencies\SupportModules\`.

![Add references](/images/add-references.png)

![Confirm references](/images/confirm-references.png)

Now we are ready to go through [MelonLoader Wiki's Quick Start guide](https://melonwiki.xyz/#/modders/quickstart)!

## Working on your own mods

![Yay!](/images/success.png)

After completing the quickstart guide, you are now in the position to work on whatever you desire! Use the [Unity Scripting API reference](https://docs.unity3d.com/ScriptReference/) to find out about the parts of the game you want to modify, and join us at the [VRChat Modding Group Discord](https://discord.gg/rCqKSvR) to talk to others in the VRChat modding community.
