ORBIT v6.1 by Malel - Skyworth 55 inch Google TV (Android 11).
1. Unzip, upload the CONTENTS to your GitHub repository (overwrite existing files).
2. Check .github/workflows/build.yml exists (copy in build-workflow-copy.txt).
3. Actions tab: wait for the green tick. Releases: download OrbitTV.apk.
4. TV: Downloader > the release link > Install. Same signing key as before, so it updates v3/v4/v5 in place.

What is new in v6.1 (full TV launcher)
- Top-right bar: clock, network status, Search/Assistant button, Inputs button and a Quick Settings dropdown.
- Quick Settings: Network, Bluetooth, Inputs, Sound (with volume slider), Display, Screensaver, Theme, Apps, Accessibility, Cast, About.
- Settings page in the Orbit look: Orbit options (screensaver delay, 24-hour clock, reset), a This TV card (model, Android,
  IP, storage, memory) and shortcuts to every system screen. Deep system screens are drawn by Android and open on top.
- Inputs: HDMI/AV/TV inputs listed by the TV (with CEC names such as PlayStation) and one press to switch.
- Clock and Weather widgets (weather by Open-Meteo), Recent apps row on the Apps page.
- Tiles for settings a given TV does not have are hidden automatically.

What was new in v6
- Home is its own page: empty top, a widget strip (hide/show with the chip above it) and exactly 9 apps.
  Hold OK on a Home app to choose which app sits in that slot. Hold OK on a widget for move/remove.
- Press the arrow button next to Home to line up Apps, Widgets, Discover, Biglel and Theme. Home collapses them again.
- Widgets show real photos: scenic places, Marvel, DC, anime and wild animals. "Add widget" can also use
  photos from the TV gallery, a link, or an online search.
- Theme and Biglel use real photos only (no drawn illustrations): thousands of photos in Scenic, Marvel, DC,
  Anime and Wildlife, plus My photos (TV gallery or link) and Search online.
- Biglel: left/right browse, up/down switch collection, Back closes.

Online photos come from Wikimedia Commons (free licenses) and need internet. Photos you add from the gallery
or by link are kept in My photos.
Optional home screen: adb shell cmd package set-home-activity com.orbit.tv/.MainActivity
Undo: adb uninstall com.orbit.tv
