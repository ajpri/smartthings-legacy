# smartthings-legacy

Legacy SmartThings Groovy code, consolidated into one attic.

SmartThings retired its Groovy device-handler/SmartApp platform, so this code no longer runs there. It ports to Hubitat with minimal changes — Hubitat's app/driver model is Groovy-based.

## Contents

- `STApps` — collection of SmartThings SmartApps (from ajpri/STApps)
- `ST-EcolinkWirelessLightSwitch` — device handler for the Ecolink Z-Wave wireless light switch, models TLS-ZWAVE5 and DLS-ZWAVE5 (from ajpri/ST-EcolinkWirelessLightSwitch)
- `STMutableDTH` — generic configurable device handler (from ajpri/STMutableDTH)
- `silentLevelLights` — control a light's brightness without turning it on (from ajpri/silentLevelLights)
- `ST-AprilFun` — an April Fools' SmartApp (from ajpri/ST-AprilFun)
- `UselessSmartApp` — the Useless SmartApp (from ajpri/UselessSmartApp)
- `Ill-be-back-SA` — "I'll Be Back" presence SmartApp (from ajpri/Ill-be-back-SA)
- `ST-GoContWirelessSwitch` — GoControl wireless switch device handler (from ajpri/ST-GoContWirelessSwitch)
- `VPresPlus` — virtual presence device handler (from ajpri/VPresPlus)

Each folder was imported from its standalone repository at its latest commit; folder-level provenance is in the git history.
