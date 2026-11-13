# GPX Toolkit

A Windows motorcycle trip planner, built as a friendlier alternative to Garmin BaseCamp, for riders who
plan rides on pavement, on dirt, or a mix of both.

## Plan the ride you want
The **Route** panel (the Roads button beside the map) gives every group the ride it wants:
- **Paved only** keeps the route off gravel and dirt entirely, for groups that want to avoid unpaved roads at all costs.
- **Any road** mixes pavement and dirt for the best route.
- **Dirt roads** seeks dirt out.

You can also avoid motorways, toll roads and ferries, favour curvy roads, mark areas the router must never use,
and check a route for closed roads before you ride. State wildlife management areas (WMAs) show on the map, and
you can keep routes out of any of them, always or during hunting season; in Georgia, the WMA roads the state lists
as closed are avoided for you. If a route still uses a toll road or a ferry, the route card
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
In Florida, stretches of dirt that appear to dead-end are drawn gray, so you can pick the roads that lead somewhere.
Also in Florida, the closed-roads check warns about roads on conservation and military land, which are usually gated, and in Lake and Volusia counties about roads that look private. Point at a dirt road on Florida conservation or military land and the map tells you too.

## Find the twisty roads
The **Twisty roads** layer in the Map menu marks the clearly twisty paved roads across a whole region, coloured
twisty, very twisty or extremely twisty. Point at one to see its name and how twisty it is. Each road is scored
from its bends, the way roadcurvature.com does it, and only named roads of 2 miles or more are kept. It downloads
with the dirt data for each state or province, so it works offline too.

## Plan the days
The **Trip** panel lays the whole trip out day by day: miles, riding time, start and finish, sunset (it warns if
you'd arrive after dark), dirt share, and where your fuel range runs out. Routes and tracks both count, so a BDR's
sections show as days, and you can start a loop on any section or ride it backwards (and save a reversed copy for
your GPS). **Suggest overnight stops** finds real hotels or campgrounds near each night, with a link to their
reviews, and **Find** shows gas, food and places to stay along the way in a second or two. Places you add carry
their phone number and address onto your Garmin.

## Everything in one place
- **Trip library:** your trips are plain GPX files in folders, saved automatically.
- **Editing:** edit tracks, routes and waypoints on the map; merge, reverse, and turn a recorded track into a route.
- **Loop rides:** a ride out and back to your start, of the length you pick, from the Loop ride button.
- **3D terrain:** tilt the map over the hills.
- **Elevation profile:** climbs and descents along a route or track.
- **Offline maps and routing:** download whole states, big areas or long routes and keep planning with no signal.
  Dirt and twisty road data download per state or province.
- **Your GPS:** send trips to Garmin, BMW Nav and TomTom units, or share the GPX with friends.
  On a Garmin, shaping points keep the unit on the roads you planned, and the exact line goes along as a track for the dirt.

## Install
**Easiest: [get GPX Toolkit from the Microsoft Store](https://apps.microsoft.com/detail/9N4HKCF52MXB).** Click **Get**; there are no
Windows warnings, and the Store keeps it up to date. New versions reach the Store a few days after they appear here.

Or install it with the setup file:

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

You only do this once.

### If Windows won't let you install it

Some Windows 11 PCs are set to allow only Microsoft Store apps. The simple answer is to
[get GPX Toolkit from the Microsoft Store](https://apps.microsoft.com/detail/9N4HKCF52MXB) instead; nothing needs changing. If you'd
rather use the setup file, the message you see tells you what to change:

- **"The app you're trying to install isn't a Microsoft-verified app"** (with a button to get apps from the Store):
  open **Settings → Apps → Advanced app settings → Choose where to get apps** and pick **Anywhere**. Then run the
  setup file again. You can set it back afterwards; GPX Toolkit keeps working and updating.
- **"Smart App Control blocked an app that may be unsafe"** (and no Run anyway button): open **Windows Security →
  App & browser control → Smart App Control settings** and pick **Off**. Then run the setup file again. Note: on
  many PCs, Smart App Control can't be turned back on without resetting Windows, so think about it first.
- **"For security and performance, this mode of Windows only runs verified apps from the Store"**: the PC is in
  **S mode**. Leaving S mode is free but one-way: in the Microsoft Store, search for **Switch out of S mode** and
  click **Get**.
- On a **work or school PC**, these settings are often locked by the IT department; try the Microsoft Store copy,
  ask them, or use a personal PC.

**Updates:** the app checks here when it starts and offers new versions by itself (a Microsoft Store copy is updated by the Store). Each
[release](https://github.com/dparisoe/GpxToolkit-releases/releases) lists what's new in it.

This repository holds only the installer and update packages.
