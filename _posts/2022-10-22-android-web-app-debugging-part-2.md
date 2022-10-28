---
title: Android web debugging part-2
permalink: /blogs/android-web-app-debugging-part-2
---

## Chrome dev tool
After we enabled debugging option on the device from [part-1](https://jessie-pastan.github.io/blogs/web-app-debugging-part-1). Turn off Adblog and VPN on the device and make sure that the Wifi connection is the same as the windows computer.

**Step-1**: Connect the device to the computer using a USB cable.

> You may see an alert on the mobile device to allow the connection, always make sure to check the box Always allow from this computer and tap on Allow

**Step-2**: Go to ‘Chrome browser and enter ‘URL’ of debugging Web app.

**Step-3**: On Windows computer open Chrome browser and  type URL  Chrome://inspect and Enter.
<div class="center-align-text">
<img src="../assets/img/2022-10-22-android-web-app-debugging-part-2/3.png" width="100%">
</div>

**Step-4**: Then will get redirected to this page, click `inspect` on the debugging URL.
<div class="center-align-text">
<img src="../assets/img/2022-10-22-android-web-app-debugging-part-2/4.png" width="100%">
</div>

**Step-5**: The device screen and the inspect panel will show up on the right side.
<div class="center-align-text">
<img src="../assets/img/2022-10-22-android-web-app-debugging-part-2/5.png" width="100%">
</div>

**Step-6**: After the inspection, there are some errors that indicate a high latency.
<div class="center-align-text">
<img src="../assets/img/2022-10-22-android-web-app-debugging-part-2/6.png" width="100%">
</div>

**Step-7**: To save log, right-click on any console area and choose `save as`. Save as type should be `Text document`, `.txt` file, then click save..
<div class="center-align-text">
<img src="../assets/img/2022-10-22-android-web-app-debugging-part-2/6.png" width="100%">
</div>

**Step-8**: An example of the console log in `.txt`.
<div class="center-align-text">
<img src="../assets/img/2022-10-22-android-web-app-debugging-part-2/6.png" width="100%">
</div>
