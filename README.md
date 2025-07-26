# Alien RPG – Stress System Macros for Foundry VTT

This repository contains a set of macros designed for use with the **Alien RPG** system in **Foundry Virtual Tabletop (VTT)**. These scripts implement the *new panic system* introduced by **Free League Publishing**, streamlining stress and panic mechanics for faster, more immersive gameplay.

## 📦 Contents

This repository includes the following macros and supporting tables:

* **Combat Stress**
  Use this macro in any situation **other than** a skill roll (e.g. during combat encounters, panic events, or environmental triggers).

* **Skill Stress**
  Use this macro specifically when making **skill-based rolls** that result in a *facehugger* (⚠) symbol.

* **Panic V2 Table**
  A required rollable table used by the Combat Stress macro to determine the appropriate panic effect.

* **Skill Panic V2 Table**
  A required rollable table used by the Skill Stress macro to resolve panic outcomes during skill rolls.

## 🛠 Installation

To install and use these macros in Foundry VTT:

1. Open Foundry VTT and load your **Alien RPG** world.
2. Navigate to the **Macros** tab.
3. Create a new macro and paste in the contents of the relevant script from this repository.
4. Name the macro and assign it an icon.
5. Drag the macro to your hotbar for easy access.
6. Import the required rollable tables (`Panic V2` and `Skill Panic V2`) into your world via the **Rollable Tables** directory.

For more guidance, see the [Foundry VTT macro documentation](https://foundryvtt.com/article/macros/).

## Updates
Fixed the tables being off by one - added agenda cards representing the conditions for the players to reference

## 📌 Notes

* These macros are built specifically for the **Alien RPG** system and may not work with other game systems.
* Ensure you have the latest version of the **Alien RPG system module** installed in Foundry VTT.
* You may wish to customise the rollable tables with your own panic effects depending on your house rules or campaign tone.
* Disclaimer: All code was human-generated, but I cannot write good, so this readme was AI-generated.
