---
layout: page
title: Lib Proxy Helper Android App
description: Helps with accessing literature via a library proxy
img: assets/img/lib2link_logo.png
importance: 3
category: software
related_publications: false
---

[![Join the Test HERE](/assets/img/Join_the_Test-HERE-green.svg)](https://groups.google.com/g/testers-for-lib-proxy-helper)
[![Latest Release HERE](/assets/img/Latest_Release-HERE-blue.svg)](https://github.com/frieseneggerf/link2lib/releases/latest)

## What it does

**Lib Proxy Helper** makes it easier to access articles licensed by your library on the phone. After selecting the proxy url of your library, you can pass links to articles to the app which will then redirect you to your libraries sign-on. If your library grants access, you can read the full-text without having to click through the publishers sign-on dialogue.

_This app WILL NOT give you access to articles that aren't already licensed by your library, it only makes the access easier/more comfortable._

## How it works

Many university libraries provide access to most of the journals they license using a proxy prefix (called "EZProxy", "E-Media Login", etc.), which means a url snippet (e.g. `https://emedien.ub.uni-muenchen.de/login?url=`) is prepended to the link of an article, the user then gets redirected to the universities sign-in page and can then access the paper after authentication.

**Lib Proxy Helper** semi-automates the task of prepending the url. Links can be sent to the app using the system share dialogue, pasted from the clipboard and some publishers links can even be automatically processed upon clicking them.

## Where to get it

The app is currently in a closed testing phase in the Google Play Store, you can join as a tester (which provides me feedback and helps me get the app published to the general public) by joining
the ["Testers for Lib Proxy Helper" Google Group](https://groups.google.com/g/testers-for-lib-proxy-helper).
You can also view the source code and download it directly from [GitHub](https://github.com/frieseneggerf/link2lib).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lib2link_screenshot_light.png" title="Light Mode" width="250px" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lib2link_screenshot_dark.png" title="Dark Mode" width="250px" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
