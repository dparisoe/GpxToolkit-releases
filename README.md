# GPX Toolkit

A Windows motorcycle trip planner, built as a friendlier alternative to Garmin BaseCamp, for riders who
plan rides on pavement, on dirt, or a mix of both.

## Plan the ride you want
The **Route** panel (the Roads button beside the map) gives every group the ride it wants:
- **Paved only** keeps the route off gravel and dirt entirely, for groups that want to avoid unpaved roads at all costs.
- **Any road** mixes pavement and dirt for the best route.
- **Dirt roads** seeks dirt out.

You can also avoid motorways, toll roads and ferries, favour curvy roads, mark areas the router must never use,
and check a route for closed roads before you ride. If a route still uses a toll road or a ferry, the route card
warns you and the map marks where. The same panel starts and edits routes, and shows the selected route's
distance, riding time, climb, dirt share and bends as you draw it.

## Loop rides
Pick a start and a length (miles or hours) and GPX Toolkit finds a loop that brings you back where you started.
Choose a direction or let it surprise you, and pick the surface: paved only, any road, or dirt. You can lean it
towards twisty back roads, keep it out of towns, make it pass a place you choose, and add a gas or lunch stop near
half-way. It also checks you'll be back before sunset and that you won't run short of fuel. The best three loops
show on the map in their own colours. Add the one you like to your trip, and it's a normal route you can edit and
send to your GPS. **Feeling lucky** picks the direction for you, but never changes the surface.

## See where the dirt is
**Highlighting unpaved roads while zoomed out** shows where the dirt is across a whole region at a glance.
I couldn't find another planner that did this, and it's what started the project. **Check dirt** then shows
exactly how much of a route is paved, unpaved or unknown, plus the longest dirt stretch. It works on one trip
or a whole folder at once. A paved-only group can confirm a route is clean, and a dirt group can use the
built-in list of more than 2,000 shared dirt roads (thanks to Dan Miller, FCAR, and Regulators Dual Sport)
to find more. Results are saved in the GPX file, so anyone you share it with sees them too.

## Everything in one place
- **Trip library:** your trips are plain GPX files in folders, saved automatically.
- **Editing:** edit tracks, routes and waypoints on the map; merge, reverse, and turn a recorded track into a route.
- **Loop rides:** a ride out and back to your start, of the length you pick, from the Loop ride button.
- **3D terrain:** tilt the map over the hills.
- **Elevation profile and day-by-day trip plan:** distance, time and dirt share for each day.
- **Offline maps and routing:** download whole states, big areas or long routes and keep planning with no signal.
- **Your GPS:** send trips to Garmin, BMW Nav and TomTom units, or share the GPX with friends.

## Install
1. Open the [latest release](https://github.com/dparisoe/GpxToolkit-releases/releases/latest) and, under **Assets**,
   click **GpxToolkitApp-win-Setup.exe** to download it. Ignore the other files.
2. Your browser may warn about the download:
   - **Edge** may say *"isn't commonly downloaded"*. Point at the message, click the **⋯** (three dots) → **Keep**.
     If it asks again, click **Show more** → **Keep anyway**.
   - **Chrome** may say *"Suspicious download blocked"*. Click the download, then **Download suspicious file** or **Keep**.
3. Open the downloaded file, from the browser's downloads list or your **Downloads** folder.
4. Windows shows a blue box: **"Windows protected your PC."** This is because the app isn't code-signed (signing
   costs money); it isn't a virus warning. Click **More info** (the small link under the text), then **Run anyway**.
5. It installs by itself in a few seconds, with no questions, and GPX Toolkit opens. It adds a Start menu entry
   and a desktop shortcut.

You only do this once. If **Run anyway** isn't there, the PC (often a work computer) only allows apps from the
Microsoft Store.

**Updates:** the app checks here when it starts and offers new versions by itself. Each
[release](https://github.com/dparisoe/GpxToolkit-releases/releases) lists what's new in it.

This repository holds only the installer and update packages.
