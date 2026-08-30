# W' Balance (IQwprimebal)

A Garmin Connect IQ data field that tracks and displays your anaerobic work capacity (**W' balance**) in real-time.

## 🚴 What is W' Balance?

In cycling physiology, **W'** (W-prime) represents the finite amount of energy available to an athlete when exercising above their **Critical Power (CP)**. 

- **Above CP**: You consume your W' reserve.
- **Below CP**: Your W' reserve regenerates.

This data field allows you to monitor your "battery" level on your Garmin device, helping you decide when to launch an attack, respond to a sprint, or pace yourself during a climb.

## ✨ Features

- **Two Calculation Models**:
    - **Integral**: Based on Dr. Philip Skiba's theory.
    - **Differential**: Based on Froncioni and Clarke's model (default in GoldenCheetah).
- **Customizable Display**: Choose between displaying the balance as a **percentage (%)** or in **kiloJoules (kJ)**.
- **TTE (Time To Exhaustion)**: Optional display of the estimated time remaining before W' reaches zero, based on current averaged power.
- **Data Recording**: The W' balance is recorded directly into the `.FIT` file (`wprime_bal`), allowing for post-ride analysis in software like GoldenCheetah.

## ⚙️ Configuration

To use this field, you must configure your personal physiological parameters via Garmin Connect Mobile or Garmin Express:

1. **CP (Critical Power)**: Your power threshold in Watts.
2. **W'**: Your anaerobic capacity in Joules.
3. **Method**: Select between *Integral* or *Differential*.
4. **Value**: Select display unit (*%* or *kJ*).
5. **TTE**: Enable or disable the Time To Exhaustion display.

*Tip: You can estimate your CP and W' using the "Estimate CP and W'" tool in **GoldenCheetah**.*

## 📖 Detailed Guides

For a comprehensive explanation of the theory and usage, please refer to the following articles:
- 🇫🇷 [Guide en Français](https://www.nakan.ch/wp/2016/03/03/afficher-la-balance-de-w-sur-son-guidon/)
- 🇬🇧 [Guide in English](https://www.trinakan.com/wp/2016/04/02/everything-about-my-w-bal-w-prime-balance-connect-iq-app/)

## 📦 Installation

You can download the app directly from the Garmin Connect IQ Store:
[W' Balance on Connect IQ Store](https://apps.garmin.com/en-US/apps/6dcfffe5-cd3d-41f3-8ba3-13fa0647b003)

## 📜 Credits & License

- Adapted from **GoldenCheetah** (`wprime.cpp`).
- Special thanks to Mark Liversedge for his implementation details.
- This software is licensed under the **GNU General Public License v3**.
