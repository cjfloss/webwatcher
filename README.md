<div align="center">
  <span align="center"> <img width="80" height="70" class="center" src="https://github.com/kjlaw89/site-monitor/master/data/images/com.github.kjlaw89.site-monitor.png" alt="Icon"></span>
  <h1 align="center">Site Monitor</h1>
  <h3 align="center">Know when your websites are misbehaving!</h3>
</div>

<br/>

<p align="center">
   <a href="https://github.com/kjlaw89/site-monitor/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-GPL--3.0-blue.svg">
   </a>
  <a href="https://github.com/kjlaw89/site-monitor/releases">
    <img src="https://img.shields.io/badge/Release-v%200.0.1-orange.svg">
   </a>
  <a href="https://github.com/kjlaw89/site-monitor/releases/download/0.0.1/com.github.kjlaw89.site-monitor_0.0.1_amd64.deb">
     <img src="https://img.shields.io/badge/Download-%20Package .deb-yellow.svg">
    </a>
</p>

<p align="center">
    <img  src="https://github.com/kjlaw89/site-monitor/master/data/images/screenshot.png" alt="Screenshot"> <br>
  <a href="https://github.com/kjlaw89/site-monitor/issues/new"> Report a problem! </a>
</p>

## Installation

### Dependencies
These dependencies must be present before building
 - `meson (>=0.40)`
 - `valac (>=0.16)`
 - `debhelper (>= 9)`
 - `libgranite-dev`
 - `libgtk-3-dev`

 
 ### Building

```
git clone https://github.com/kjlaw89/site-monitor.git && cd site-monitor
meson build && cd build
meson configure -Dprefix=/usr
ninja
sudo ninja install
com.github.kjlaw89.site-monitor
```

### Deconstruct

```
sudo ninja uninstall
```

### Contributing

To help, access the links below:

- [Guide on Code Style](https://github.com/kjlaw89/ciano/wiki/Guide-on-code-style)

- [Proposing Design Changes](https://github.com/kjlaw89/ciano/wiki/Proposing-Design-Changes)

- [Reporting Bugs](https://github.com/kjlaw89/ciano/wiki/Reporting-Bugs)

- [Translate](https://github.com/kjlaw89/ciano/wiki/Translate)


### License

This project is licensed under the GPL3 License - see the [LICENSE](LICENSE.md) file for details.
