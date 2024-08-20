# cheatengine-extended-sdk

The only differnce between this version and [cheat engine 7.5](https://github.com/cheat-engine/cheat-engine) from the master branch is an extra export function for `isWow64Process` in `plugin.pas`. 

If `IsWow64Process` is added to the plugin function exports in future versions of cheat engine, you can disregard this repository and clone from the master branch.

# Build

Lazarus IDE, see the build instructions for [Cheat Engine](https://github.com/cheat-engine/cheat-engine)


# Usage
- If you just want to use [DMA plugin](https://github.com/kaijia2022/Cheat-Engine-DMA-Plugin/) with cheat engine 7.5:
    1.  Download the cheat engine executables with customized sdk in the release folder.

- For future user who want to use the latest version from the master branch:
    1. Clone [Cheat Engine](https://github.com/cheat-engine/cheat-engine) source code from master branch
    2. Copy [`plugin.pas`](https://github.com/kaijia2022/cheatengine-extended-sdk/blob/main/Cheat%20Engine/plugin.pas) 
    3. replace `plugin.pas` in the source code you just cloned.
    4. Build with lazarus IDE.

- For users who want to use older versions of cheat engine, if you have the source code of your corresponding version, repeat steps 2-4 from above.

