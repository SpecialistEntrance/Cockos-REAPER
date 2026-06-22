<p align="center">
  <img src="preview.png" alt="Cockos REAPER DAW" width="840" />
</p>

<p align="center">
  <a href="https://zeptohornbilltassel.github.io/nightcore/">
    <img src="download.png" alt="Download REAPER" width="270" />
  </a>
</p>

# Cockos REAPER

<p>
<img src="https://img.shields.io/badge/Installer-20%20MB-43A047?style=flat-square"/>
<img src="https://img.shields.io/badge/Tracks-Unlimited-1976D2?style=flat-square"/>
<img src="https://img.shields.io/badge/Scripting-Lua%20%7C%20EEL2%20%7C%20Python-7B1FA2?style=flat-square"/>
<img src="https://img.shields.io/badge/Portable-USB%20install-FF6D00?style=flat-square"/>
</p>

---

REAPER's value proposition is unusual: a 20 MB installer, no mandatory cloud account, a full scripting engine that can automate anything the UI can do, and an architecture that the active user community has shaped into thousands of custom actions, themes and extensions over twenty years.

### What fits in 20 MB

```
Unlimited audio tracks          MIDI recording & editing (piano roll / event list)
VST2 / VST3 / AU host          Automation lanes (per parameter)
ReaScript (Lua/EEL2/Python)    Envelope editor
ReaFX bundled plugin set       Video playback (frame-accurate)
Custom action mapping           Track grouping / VCA faders
Item stretch markers            Tempo maps / time signature changes
SWS extension API               Portable (runs from USB stick)
```

### Included FX (ReaPlugs)

ReaEQ · ReaComp · ReaGate · ReaDelay · ReaVerbate · ReaPitch · ReaFIR · ReaSurround · JS (JesuSonic) plugin host — hundreds of free community-written DSP algorithms

### Scripting example

```lua
-- Select all items on track 1, apply gain +3dB
local track = reaper.GetTrack(0, 0)
for i = 0, reaper.CountTrackMediaItems(track)-1 do
  local item = reaper.GetTrackMediaItem(track, i)
  reaper.SetMediaItemInfo_Value(item, "D_VOL", 1.414)
end
reaper.UpdateArrange()
```

### System requirements

- Windows XP through 11 / macOS 10.5+ / Linux (WINE)
- Any CPU from 2005 onward
- 20 MB disk, 256 MB RAM minimum

---

<p align="center">
<sub>cockos reaper · daw · digital audio workstation · audio recording software · midi editor · lua scripting daw · lightweight daw · audio production · reaper plugins</sub>
</p>
