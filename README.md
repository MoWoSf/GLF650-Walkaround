# GLF650 Walkaround

Walk around, into and out of the AKD Studio GLF650 / GLF650ER in X-Plane 12, call ground service from your phone and start your flight in an FBO lounge.

Free. Windows and Linux (64 bit). Needs the AKD Studio GLF650 1.01.

## Install and updates

1. Unpack the ZIP and copy the folder `GLF650_Walkaround` into `X-Plane 12/Aircraft/GLF650_1.01 XP12/plugins/` (next to `SASL`).
2. Load the GLF650 in X-Plane once.
3. Open the SkunkCrafts Updater and check for new addons. **GLF650 Walkaround** now shows up there (filter "Other"), and every later update comes through the updater.

Uninstall: delete the folder.

## Features

- **Walkaround:** walk with W/A/S/D (Shift runs, Ctrl crouches) through the cockpit, cabin and baggage compartment, down the airstair and around the aircraft, with real collision and footstep sounds.
- **Seats:** click a cabin seat or divan to sit down. Push W to stand up again.
- **Ground service phone:** call a Mercedes EQV with your bags and a Maybach GLS with your passengers. They drive along the airport's roads to the baggage door and the airstair. Load the bags yourself, with a click, or automatically. At your destination they come to collect.
- **Door mat** in front of the airstair while the door is open.
- FMS typing stays with the aircraft. Works with X-Camera. All keys can be rebound.

## FBO lounge

When you load the GLF650 on the ground with the engines off, you start in a private terminal. Click the "To Aircraft" door and a car drives you the last stretch to your airstair. Menu: Plugins > GLF650 Walkaround > Start at the FBO.

- **Departure board:** your flight at the top, with the callsign, destination and planned departure from SimBrief, your stand from the airport's data, and BOARDING. While you are connected to VATSIM, other GLF650s filed out of the same airport are listed too, with their stands. Made-up business jets fill the rest of the rows.
- **SimBrief:** your latest flight plan on the briefing room's screen (route, times, fuel, alternate) and on the phone's home screen. Your route is also drawn on the weather map.
- **VATSIM:** while your CID is connected, the airport's VATSIM ATIS is shown. Without VATSIM, the plugin builds a D-ATIS from X-Plane's weather instead (runway in use, QNH, transition level, winds aloft, METAR).
- **Weather map:** 100 NM around the airport: clouds, rain, the winds at FL100, and the nearby airports coloured VFR / MVFR / IFR / LIFR.
- **Live:** the screens refresh every 10 s while you are in the lounge. The phone's FBO app shows the same data and has "Refresh now".
- **Your terminal:** write your own name on the brass sign over the reception (phone: Settings > FBO sign). Add your own logos and music (below).

Set your VATSIM CID and SimBrief Pilot ID once on the phone: Settings > Network.

## Your own logos

PNG or JPEG. A transparent logo lies on the mat or runner. A logo on a plain background colours the whole mat or runner.

| Where | File | Put it into |
|---|---|---|
| Door mat | any name with `doormat`, e.g. `doormat.png` | the livery's folder (`liveries/<your livery>/`) |
| Runner in the FBO | `logo_runner.png` (two panels), `logo_runner_1.png` (one panel), `logo_runner_h.png` (one long panel) | `plugins/GLF650_Walkaround/fbo_custom/` |
| TV behind the reception | any name with `tv`, e.g. `logo_tv.png` | `plugins/GLF650_Walkaround/fbo_custom/` |

You can also drop MP3s into `fbo_custom` for your own lounge music. To change the sign over the reception, use the phone: Settings > FBO sign.

---
Unofficial and free; not affiliated with Gulfstream Aerospace, AKD Studio or Mercedes-Benz. Based on FA8X Walkaround.
