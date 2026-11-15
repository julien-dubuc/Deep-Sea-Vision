# Deep-Sea-Vision

**An interactive browser game about how underwater vehicles see, decide and fail.**

You play the onboard AI of a submarine robot. Your only window on the world is its sensors: cameras, sonar, magnetic detectors. Read what they tell you, make the call, and keep the mission alive.

Scan the QR code below with your phone to play. No install, no account.

<p align="center">
  <img src="QR%20code.png" alt="QR code to play Deep Sea Vision" width="220">
</p>

👉 **Play online:** https://julien-dubuc.github.io/Deep-Sea-Vision/

## 📝 Project Overview

Underwater robots cannot rely on GPS or radio, and light fades within a few dozen metres. Their decisions depend on noisy, ambiguous signals, and a wrong interpretation can cost the whole mission. This game puts the player in that position.

Each mission is a short branching story. At every step the player gets a sensor reading or a situation and has to choose what the vehicle should do next. A correct answer comes with a brief explanation. Some wrong answers can be recovered through a rescue question, others end the mission and send you back to the start.

The game was built as a team project at SeaTech to introduce marine robotics and embedded AI to a general audience, with no prior knowledge required.

## 🎮 The Three Missions

### 🤖 BlueROV2: Deep Sea Descent
*Environmental survey, 10 steps.*
A small tethered ROV goes down to recover a flight recorder from the seabed. Along the way it deals with:
* Water pressure and depth limits
* Cold water, battery drain and how to share limited power
* Communication delay through water
* Computer vision (YOLO) and what happens when a dataset is biased
* Thruster allocation and manipulator control with no sense of touch
* Marine growth on sensors, the colour of light at depth, tether tangles
* Buoyancy and emergency ascent

### 🎯 Military AUV: Search & Track
*Stealth patrol, 10 steps.*
An autonomous submarine with no cable must find and identify an enemy vessel without being heard. Topics include:
* Active versus passive sonar
* Thermoclines bending sound
* Pulling weak signals out of noise
* Biological noise, decoys and false targets
* Acoustic signatures, quieting techniques and blind zones
* Magnetic detection to confirm a hidden target
* Passing the data back

### 🚢 Titan Submersible: Extreme Depth
*A true story about pressure and warnings, 6 steps.*
A dive to the Titanic wreck, inspired by a real accident. The player faces:
* Why materials fail under repeated pressure
* Reading structural warning signs
* Telling wreckage from sea life on sonar
* Which engineering mistakes cannot be undone once past a certain point

## ✨ Key Features

* **Mini-games:** type commands, tune filters, classify sensor signatures, sneak past radar sweeps, split a power budget.
* **Learn as you play:** short explanations after correct answers, and tap-to-define underlined words (hull, claw, thermocline, hydrophone…).
* **Timer, stars and best times:** up to 3 stars per mission, with your best time saved on your device.
* **My Stats:** missions played, questions answered, hardest step, last runs. Everything stays in your browser.
* **Shareable result card:** export an image of your run to challenge friends.
* **Sound and vibration:** ambient sound and sound effects generated in the browser, with optional haptic feedback on phones.
* **Mobile first:** works in portrait and landscape, with full-screen mode.
* **Single file:** the whole game is one `index.html`. No server, no dependencies.

## 🗂️ Repository Structure

* 📄 **`index.html`** : the complete game (HTML, CSS, JavaScript and embedded images).
* 🖼️ **`QR code.png`** : QR code that opens the game on a phone.
* 📄 **`README.md`** : this file.

## 🚀 Run It Locally

Download `index.html` and open it in any modern browser. Nothing else is needed.

## 🛠️ Built With

Plain HTML, CSS and JavaScript. Sounds are synthesised with the Web Audio API. Progress and stats use the browser's local storage.

## 👨‍💻 Authors

A project by **Julien Dubuc**, **Timm Claverie**, **Théo Coulongeat**, **Jules Laurent** and **Thomas Koch-Legrand**.
Engineering students at SeaTech (Université de Toulon).

## 🙏 Acknowledgements

Thanks to our teachers at SeaTech for their guidance, and to everyone who playtested the game.
