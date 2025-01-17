# GPS

<img src="https://resources.gdevelop-app.com/assets/Icons/crosshairs-gps.svg" class="extension-icon"></img>
Adds a way to locate the player.

**Authors and contributors** to this community extension: [arthuro555](https://gd.games/arthuro555).

---

Adds an action to locate the player using the built-in GPS, or other techniques if unavailable. 
You can also track whether or not you've gotten the permission to use the GPS sensor, and track realtime player movement.

!!! tip
    Learn [how to install new extensions](/gdevelop5/extensions/search) by following a step-by-step guide.

## Actions

**Locate the player**  
Locates the player. If the permission status is pending, it will ask for user permission. Once the location is fetched, stores it in the callback variable.

**Watch the player**  
Detects when the player's device is moved and get its new location. If the permission status is pending, it will ask for user permission. Every time the location is updated, stores it in the callback variable.

## Expressions

| Expression | Description |  |
|-----|-----|-----|
| `Geolocation::PermissionStatus()` | Returns the status of the geolocation permission. ||

---

*This page is an auto-generated reference page about the **GPS** extension, made by the community of [GDevelop, the open-source, cross-platform game engine designed for everyone](https://gdevelop.io/).* Learn more about [all GDevelop community-made extensions here](/gdevelop5/extensions).