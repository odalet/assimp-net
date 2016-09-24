# assimp-net

This fork of [https://github.com/assimp/assimp-net](https://github.com/assimp/assimp-net) updates the version of Mono.Cecil (and references it through nuget).
It also embeds the last version of [https://github.com/assimp/assimp](https://github.com/assimp/assimp) targetting VS2015 x86/x64. Artifacts are found on Assimp's AppVeyor: [https://ci.appveyor.com/project/kimkulling/assimp](https://ci.appveyor.com/project/kimkulling/assimp)

## Retrieving Assimp binaries

At the moment, the x64 build of Assimp on appveyor generates x86 binaries. I've fixed this and submitted a PR ([https://github.com/assimp/assimp/pull/1006](https://github.com/assimp/assimp/pull/1006)). In the meantime, x86/x64 for VS2013/VS2013 are available on my Appveyor: [https://ci.appveyor.com/project/odalet/assimp](https://ci.appveyor.com/project/odalet/assimp)