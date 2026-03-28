# Kerbalized Launch Audio Packs for NASA CountDown

This project provides a collection of **kerbalized launch audio packs** for *Kerbal Space Program*, designed for use with the **[NASA CountDown (NCD)](https://github.com/linuxgurugamer/LaunchCountdownEx)** mod.

All audio sequences are derived from **real launch recordings**, reworked to fit the Kerbal universe while preserving the structure, pacing, and atmosphere of actual mission countdowns.

## Features

* Multiple launch providers and programs:

  * Mercury, Gemini, Apollo
  * Soyuz and Proton
  * Ariane 5 and Ariane 6
  * Delta II, Delta IV, Atlas V
  * Space Shuttle
  * Artemis
  * JAXA missions
  * SpaceX: Falcon 9 and Starship (includes ambient crowd reactions, e.g. Starbase celebrations)

* Each pack includes a complete set of audio events:

  * `LiftOff`
  * `Hold`
  * `Aborted`
  * `TowerCleared` *(currently unused by NCD, included for completeness)*

* Standardized timing:

  * All countdowns begin at **T-60 seconds**
  * Enables easier **manual synchronization** with autopilot tools such as *MechJeb*

* Consistent structure across all packs for easy swapping and customization

## Installation

1. Navigate to:

   ```
   GameData/NASA_CountDown/Sounds
   ```

2. Delete any existing folders that share the same name as the ones you want to install.

3. Copy the desired audio pack folders into the directory above.

4. Launch the game.

### Restore Default Sounds

To revert to the original audio:

* Perform a **clean reinstall** of the NASA CountDown mod.

## Compatibility & Dependancy Notes

* Fully compatible with:

  * **[NASA CountDown (NCD)](https://github.com/linuxgurugamer/LaunchCountdownEx)**, which is therefore a dependancy

* Partial / experimental compatibility:

  * Athlonic's **[Launch CountDown (LCD)](https://spacedock.info/mod/791/LCD%20-%20Launch%20CountDown)**

    * This mod appears to use **hard-coded sequence selections**
    * Some folder names differ from NCD
    * Manual adjustments or renaming may be required

A dedicated compatibility version for LCD may be released in the future.

## Design Notes

These packs aim to balance:

* **Authenticity** (real launch cadence and phrasing)
* **Consistency** (uniform timing and structure)
* **Immersion** within the Kerbal universe

The result is a set of audio sequences that feel grounded in real aerospace operations while remaining fully compatible with gameplay constraints.

## Known Limitations

* `TowerCleared` is included but seems not currently triggered by NCD
* Synchronization with launches is **manual** (no direct integration with flight state or autopilot timing)
* Audio playback follows in-game time; under low performance (physics slowdown), it may become choppy or discontinuous
  * Clips are edited to center key phrases where possible, but this cannot always be guaranteed
  * This is a limitation of NCD/LCD design and overall game performance, not of the audio packs themselves

## Feedback

If you notice timing inconsistencies, missing cues, or have suggestions for additional launch systems, feel free to share feedback.
