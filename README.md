<p align="center"><img src="./docs/images/terasology-logo.png" height=400px/></>
<div align="center">
    <a href="https://github.com/MovingBlocks/Terasology/releases/latest">
        <img src="https://img.shields.io/github/release/MovingBlocks/Terasology.svg" alt="Release" />
    </a>
    <a href="http://www.apache.org/licenses/LICENSE-2.0">
        <img src="https://img.shields.io/badge/license(code)-Apache%202.0-blue.svg" alt="License (Code)" />
    </a>
    <a href="http://creativecommons.org/licenses/by/4.0/">
        <img src="https://img.shields.io/badge/license(art)-CC%20BY%204.0-blue.svg" alt="License (Art)" />
    </a>
    <a href="https://codeclimate.com/" target="_blank" alt="Code climate">
        <img src="https://img.shields.io/codeclimate/maintainability/MovingBlocks/Terasology" alt="Code climate maintainability" />
    </a>
    <a href="https://codeclimate.com/" target="_blank" alt="Code climate" >
        <img src="https://img.shields.io/codeclimate/tech-debt/MovingBlocks/Terasology" alt="Code climate tech debt" />
    </a>
     <a href="https://codeclimate.com/" target="_blank" alt="Code climate">
        <img src="https://img.shields.io/codeclimate/issues/MovingBlocks/Terasology" alt="Code climate issues" />
    </a>
</div>

<h3 align="center"><b>
    <a href="#community">Community</a> | 
    <a href="#installation">Installation</a> | 
    <a href="#development">Development</a>  | 
    <a href="#license">License</a> 
</b></h3>

The _BedroomDogs_ project was born from a Mafia and Driver mixture tech demo and is becoming a stable platform for various types of settings in a open  world third person shooter.


## Community

If you want to get in contact with the **BedroomDogs** community and the whole **MovingCrimes** team, you can easily connect with us, share your ideas, report and solve problems.
We are present in nearly the complete round-up of social networks. Follow/friend us wherever you want, chat with us and tell the world.

&nbsp;

<p align="center">
    <a title="Discord" href="https://discord.gg/terasology">
        <img src="./docs/images/discord.png" width="48px"/>
    </a>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <a title="Twitter" href="https://twitter.com/Terasology">
    <img src="./docs/images/twitter.png" width="48px"/>
    </a>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <a title="Facebook" href="https://www.facebook.com/Terasology">
        <img src="./docs/images/facebook.png" width="48px"/>
    </a>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <a title="Reddit" href="http://www.reddit.com/r/Terasology">
        <img src="./docs/images/reddit.png" width="48px"/>
    </a>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <a title="Youtube" href="https://www.youtube.com/user/blockmaniaTV">
        <img src="./docs/images/youtube.png" width="48px"/>
    </a>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <a title="Patreon" href="https://www.patreon.com/Terasology">
        <img src="./docs/images/patreon.jpg" width="48px"/>
    </a>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <a title="Terasology Forum" href="https://forum.terasology.org">
        <img src="./docs/images/forum.png" width="48px"/>
    </a>
</p>


## Installation

<table>
    <tr>
        <td></td>
        <th>Minimum Requirements</th>
    </tr>
    <tr>
        <td>System (OS)</td>
        <td>Windows, MacOS, Linux (64 bit)</td>
    </tr>
    <tr>
        <td>Processor (CPU)</td>
        <td>dual-core CPU</td>
    </tr>
    <tr>
        <td>Memory (RAM)</td>
        <td>4 GB</td>
    </tr>
    <tr>
        <td>Graphics* (GPU)</td>
        <td style="vertical-align:top">
            Intel HD Graphics (Gen 7)<br/>
            GeForce 8xxx series (or higher) or<br/>
            Radeon HD 2000 series (or higher)<br/>
            with OpenGL 3.3
        </td>
    </tr>
    <tr>
        <td>Storage (HDD)</td>
        <td>1 GB</td>
    </tr>
</table>

\* _Please note, that if you have both integrated (chip) and dedicated (card) graphics, you should make sure that you're actually using your dedicated graphics when running BedroomDogs._

For more information about playing, like hot keys or server hosting, see the [dedicated page](docs/Playing.md) or check out the [modules](docs/Modules.md).


### Alternative Installation Methods

If you already have a Unity3D Engine installed, you may use a direct download release as an alternative to using the [launcher](https://github.com/MovingBlocks/TerasologyLauncher/releases). Unity3D version 2021 is required.


## Development

Development is possible on all common platforms (Windows, Linux, MacOS) as long as the Unity3D is properly set up.

### Requirements

- Download this repos
  <br>Using newer Unity3D versions may cause issues (see [#3976](https://github.com/MovingBlocks/Terasology/issues/3976)).
- Git to clone the repo and commit changes.

Non-Technical Requirements:
- familiarity with Git. Have a look at https://learngitbranching.js.org/ if you're not familiar with Git yet.
- familiarity with GitHub, _especially forks_. Have a look at [GitHub's "Working with Forks" Guide](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks) if you don't know how to work with forks yet.

### Workspace Setup

To be able to run **BedroomDogs** from source, you'll need to setup your workspace.
Follow the [Contributor Quick Start Guide](https://github.com/MovingBlocks/Terasology/wiki/Contributor-Quick-Start).

> :warning: _Note, that a BedroomDogs workspace is a **multi-repo workspace**._

While your workspace itself is a clone of [MovingCrimes/BedroomDogs](https://github.com/MovingCrimes/BedroomDogs), every subdirectory in your workspace directory `./modules/` is a clone of a [BedroomDogs module repo](https://github.com/BedroomDogs).

Accordingly, if you want to contribute to modules, you'll need to navigate into the respective subdirectory and work with Git from in there.
Any Git commands executed in your workspace root will target [MovingCrimes/BedroomDogs](https://github.com/MovingCrimes/BedroomDogs).

For more information, see our wiki entry on [Understanding Terasology's Git Setup](https://github.com/MovingCrimes/BedroomDogs/wiki/Developing-Modules#understanding-bedroomdogsys-git-setup).


### Contributing

Detailed information on how to contribute can be found in [CONTRIBUTING.md](./.github/CONTRIBUTING.md). Remember, that all submissions must be licensed under [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

If you find errors or issues in any of our resources, please report them using GitHub issues and help fix them.

For developers that have not worked with complex software systems or dealt with the intricacies of Java yet, we recommend to start with [Good First Issues in Module Land](https://github.com/search?l=&q=org%3ATerasology+label%3A%22Good+First+Issue%22+state%3Aopen&state=open&type=Issues).

Developers with previous experience in rendering, physics and other less trivial aspects of game development are welcome to give the [Good First Issues in Engine](https://github.com/MovingCrimes/BedroomDogs/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3A%22Good+First+Issue%22) a go.
