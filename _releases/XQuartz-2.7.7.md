---
title: XQuartz 2.7.7

version: 2.7.7
date: 2014.08.18
filename: XQuartz-2.7.7.dmg
download_url: https://github.com/XQuartz/XQuartz/releases/download/XQuartz-2.7.7/XQuartz-2.7.7.dmg
required_os_version: 10.6.3
emphasis: First release supported on Yosemite
status: release
---

### Changes in {{ page.version }} ###
  * All changes in [2.7.6](XQuartz-2.7.6.html) plus:
  * app:
    * [xcursorgen 1.0.6](https://lists.x.org/archives/xorg-announce/2014-May/002438.html)
    * [xrandr 1.4.3](https://lists.x.org/archives/xorg-announce/2014-August/002467.html)
    * [xscope 1.4.1](https://lists.x.org/archives/xorg-announce/2014-June/002443.html)
    * [xterm 309](https://lists.x.org/archives/xorg/2014-July/056747.html)
  * lib:
    * [cairo 1.12.16](http://cairographics.org/news/cairo-1.12.16)
    * [libICE 1.0.9](https://lists.x.org/archives/xorg-announce/2014-June/002442.html)
    * [libxcb 1.11](https://lists.x.org/archives/xorg-announce/2014-August/002469.html)
    * [libXext 1.3.3](https://lists.x.org/archives/xorg-announce/2014-July/002464.html)
    * [libXft 2.3.2](https://lists.x.org/archives/xorg-announce/2014-June/002441.html)
    * [libXi 1.7.4](https://lists.x.org/archives/xorg-announce/2014-July/002458.html)
    * [pixman 0.32.6](https://lists.x.org/archives/xorg-announce/2014-July/002452.html)
    * [xcb-util-renderutil 0.3.9](https://lists.x.org/archives/xorg-announce/2014-June/002446.html)
  * proto:
    * glproto 1.4.17
    * [inputproto 2.3.1](https://lists.x.org/archives/xorg-announce/2014-May/002437.html)
    * [xcb-proto 1.11](https://lists.x.org/archives/xorg-announce/2014-August/002468.html)
  * server:
    * [xorg-server 1.15.2](https://lists.x.org/archives/xorg-announce/2014-June/002450.html) plus [other patches](https://github.com/XQuartz/xorg-server/commits/XQuartz-2.7.7)
      * Fixes multimonitor support on Mavericks (#832, #1876)
      * Fix Xephyr "failed to create root window" bug (#822)
      * Fix a crash resulting from a rare race condition in fd handoff (#869)
