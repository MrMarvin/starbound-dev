---
layout: base
title: Starbound Reverse Engineering
---

Welcome to the Starbound reverse engineering hub! This is a community-maintained, unofficial website to collect information
about reverse engineering [Starbound](http://playstarbound.com). This website is open-source - you can help us reverse engineer
the game and offer your discoveries by submitting a pull request to [SirCmpwn/starbound-dev](https://github.com/SirCmpwn/starbound-dev).

Have you got questions, or do you want to get help with Starbound dev? Join our IRC channel,
<a target="_blank" href="http://webchat.freenode.net/?channels=##starbound-dev">##starbound-dev on irc.freenode.net</a>.

Though some of the information here may be valuable to modders, this website is **not** meant to document information for modding
the game. It is instead meant for reverse engineering the game and creating entirely new software based on that research.

## Projects

Want your project listed? Submit a pull request! Projects here should have some degree of usability, though they may not
yet be complete.

<!-- 
    These lists are for open-source projects only.
    Maintain these lists first by supported Starbound version, and second alphabetically. Don't compete for room here.
    External links should have target="_blank"
    Add categories when appropriate. I expect there to be a "server" and "client" section eventually, and probably a
    "libraries" section. Make an "other" section if your stuff doesn't fit into the existing categories.
-->

<table class="table">
    <thead>
        <tr>
            <th>Project</th>
            <th>Description</th>
            <th>Starbound</th>
            <th>Stability</th>
            <th>Languages</th>
            <th>License</th>
        </tr>
    </thead>
    <tbody>
        <tr> <!-- MultiBound -->
            <td><a target="_blank" href="https://github.com/ROFLCopter64bit/MultiBound">ROFLCopter64bit/MultiBound</a></td>
            <td>Full recode of a server.</td>
            <td><span class="label label-success">Furious Koala</span></td>
            <td><span class="label label-danger">Unstable</span></td>
            <td>VB.NET</td>
            <td><a target="_blank" href="https://github.com/ROFLCopter64bit/MultiBound/blob/master/LICENSE">GPL v2</a></td>
        </tr>
        <tr> <!-- py-starbound -->
            <td><a target="_blank" href="https://github.com/blixt/py-starbound">blixt/py-starbound</a></td>
            <td>Parser for Starbound's file formats (.pak, .player, .world, …)</td>
            <td><span class="label label-success">Furious Koala</span></td>
            <td><span class="label label-success">Stable</span></td>
            <td>Python</td>
            <td><a target="_blank" href="https://github.com/blixt/py-starbound/blob/master/LICENSE">MIT</a></td>
        </tr>
        <tr> <!-- starbounded -->
            <td><a target="_blank" href="https://github.com/blixt/starbounded">blixt/StarboundEd</a></td>
            <td>Web app for loading and display worlds</td>
            <td><span class="label label-success">Furious Koala</span></td>
            <td><span class="label label-danger">Unstable</span></td>
            <td>JavaScript</td>
            <td><a target="_blank" href="https://github.com/blixt/starbounded/blob/master/LICENSE">MIT</a></td>
        </tr>
        <tr> <!-- starbound-research -->
            <td><a target="_blank" href="https://github.com/McSimp/starbound-research">McSimp/starbound-research</a></td>
            <td>Scripts for reading various starbound data files in 010 Editor</td>
            <td><span class="label label-success">Furious Koala</span></td>
            <td><span class="label label-danger">Unstable</span></td>
            <td>010 Editor</td>
            <td><a target="_blank" href="https://github.com/McSimp/starbound-research/blob/master/LICENSE">MIT</a></td>
        </tr>
        <tr> <!-- StarDB -->
            <td><a target="_blank" href="https://github.com/McSimp/StarDB">McSimp/StarDB</a></td>
            <td>A Python library for manipulating Starbound database files.</td>
            <td><span class="label label-success">Furious Koala</span></td>
            <td><span class="label label-danger">Unstable</span></td>
            <td>Python</td>
            <td><a target="_blank" href="https://github.com/McSimp/StarDB/blob/master/LICENSE">MIT</a></td>
        </tr>
        <tr> <!-- StarDB-for-Java -->
            <td><a target="_blank" href="https://github.com/KrazyTheFox/StarDB-for-Java">KrazyTheFox/StarDB-for-Java</a></td>
            <td>A Java port of StarDB.</td>
            <td><span class="label label-success">Furious Koala</span></td>
            <td><span class="label label-success">Stable</span></td>
            <td>Java</td>
            <td><a target="_blank" href="https://github.com/KrazyTheFox/StarDB-for-Java/blob/master/LICENSE">MIT</a></td>
        </tr>
        <tr> <!-- StarNet -->
            <td><a target="_blank" href="https://github.com/SirCmpwn/StarNet">SirCmpwn/StarNet</a></td>
            <td>Starbound multiplayer network infrastructure.</td>
            <td><span class="label label-success">Furious Koala</span></td>
            <td><span class="label label-danger">Unstable</span></td>
            <td>C#</td>
            <td><a target="_blank" href="https://github.com/SirCmpwn/StarNet/blob/master/LICENSE">MIT</a></td>
        </tr>
        <tr> <!-- StarryboundServer -->
            <td><a target="_blank" href="https://github.com/AvilanceLtd/StarryboundServer/">AvilanceLtd/StarryboundServer</a></td>
            <td>Starrybound Proxy Wrapper for Starbound Servers.</td>
            <td><span class="label label-success">Furious Koala</span></td>
            <td><span class="label label-danger">Unstable</span></td>
            <td>C#</td>
            <td><a target="_blank" href="https://github.com/AvilanceLtd/StarryboundServer/blob/master/LICENSE">GPLv3</a></td>
        </tr>
        <tr> <!-- StarryPy -->
            <td><a target="_blank" href="https://github.com/CarrotsAreMediocre/StarryPy">CarrotsAreMediocre/StarryPy</a></td>
            <td>Plugin-driven Starbound proxy server built using Twisted.</td>
            <td><span class="label label-success">Furious Koala</span></td>
            <td><span class="label label-success">Stable</span></td>
            <td>Python</td>
            <td><a target="_blank" href="https://github.com/CarrotsAreMediocre/StarryPy/blob/master/LICENSE">WTFPL</a></td>
        </tr>
    </tbody>
</table>
