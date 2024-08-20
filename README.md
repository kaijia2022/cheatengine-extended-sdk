# cheatengine-extended-sdk

The only differnce between this version and [cheat engine 7.5](https://github.com/cheat-engine/cheat-engine) from the master branch is an extra export function for `isWow64Process` in `plugin.pas`. 

# Build

Lazarus IDE, see [cheat engine 7.5](https://github.com/cheat-engine/cheat-engine)


# Usage
- If you just want to use [DMA plugin](https://github.com/kaijia2022/Cheat-Engine-DMA-Plugin/) with cheat engine 7.5:
    -   Download the cheat engine executables with customized sdk in the release folder.

- For future user who want to use the latest version from the master branch:
    - Clone [cheat engine](https://github.com/cheat-engine/cheat-engine) source code from master branch
    - Copy [`plugin.pas`](https://github.com/kaijia2022/cheatengine-extended-sdk/blob/main/Cheat%20Engine/plugin.pas) 
    - replace `plugin.pas` in the source code you just cloned.
    - Build the cheat engine with lazarus IDE.


