# 🏁 Thika Road Rush  
**A Unity-Based Kenyan Racing & Betting Game**

## git link https://github.com/okaraworks/Thika-Road-Rush.git
## blog link https://thikaroadrush.gamer.gd/
---

## 📌 Project Overview
**Thika Road Rush** is a high-speed racing game inspired by Kenya’s iconic **Thika Superhighway**. Players place bets using **M-Pesa**, race cars through realistic Kenyan environments, and win real-money rewards. The game focuses on fast gameplay, intuitive UI/UX, and secure mobile payments.

---

## 🎯 Vision & Goals
- Create a fun, competitive racing experience
- Integrate seamless **M-Pesa betting**
- Celebrate Kenyan road culture & landmarks
- Deliver a mobile-first, low-friction UX
- Ensure secure, fair, and transparent gameplay

---

## 🎮 Core Gameplay Flow
1. Launch Game  
2. Login / Register  
3. Deposit via M-Pesa  
4. Place Bet  
5. Select Car  
6. Race on Thika Road  
7. View Results  
8. Withdraw Winnings  

---

## 🗂️ Project File Structure (Unity)
```plaintext
ThikaRoadRush/
├── Assets/
│   ├── Art/
│   │   ├── Cars/
│   │   ├── Environment/
│   │   │   ├── ThikaRoad/
│   │   │   ├── Flyovers/
│   │   │   └── Buildings/
│   │   └── UI/
│   ├── Audio/
│   │   ├── Engine/
│   │   ├── Effects/
│   │   └── Music/
│   ├── Materials/
│   ├── Prefabs/
│   │   ├── Cars/
│   │   ├── Obstacles/
│   │   └── UI/
│   ├── Scenes/
│   │   ├── Splash.unity
│   │   ├── Login.unity
│   │   ├── Lobby.unity
│   │   ├── Betting.unity
│   │   ├── CarSelect.unity
│   │   ├── Race.unity
│   │   └── Results.unity
│   ├── Scripts/
│   │   ├── Core/
│   │   │   ├── GameManager.cs
│   │   │   ├── PlayerManager.cs
│   │   │   └── RaceManager.cs
│   │   ├── Vehicles/
│   │   │   ├── CarController.cs
│   │   │   └── AIController.cs
│   │   ├── Betting/
│   │   │   ├── BetManager.cs
│   │   │   └── OddsCalculator.cs
│   │   ├── Mpesa/
│   │   │   ├── MpesaAPI.cs
│   │   │   ├── WalletManager.cs
│   │   │   └── TransactionValidator.cs
│   │   ├── UI/
│   │   │   ├── UIManager.cs
│   │   │   └── HUDController.cs
│   └── StreamingAssets/
├── Packages/
├── ProjectSettings/
└── README.md

🏎️ Racing Mechanics

Arcade-style racing with realistic handling

Acceleration, braking, drifting, nitro boost

Traffic vehicles & road obstacles

Police checkpoints (risk vs reward)

Dynamic weather (rain reduces grip)

🚗 Vehicle System

Each car has:

Speed

Acceleration

Handling

Risk rating

Faster cars = higher risk & higher odds

Unlock cars via wins or XP

💰 Betting System

Minimum & maximum bet limits

Odds calculated using:

Car stats

Player win history

Track difficulty

Automatic payout on win

House margin configurable by admin

💳 M-Pesa Integration
Deposit (STK Push)

User enters phone number

STK push sent

User enters M-Pesa PIN

Daraja callback received

Wallet credited

Withdrawals (B2C)

User requests withdrawal

Balance validated server-side

Funds sent to M-Pesa

Transaction status updated in-game

⚠️ API keys and secrets are stored ONLY on backend servers.

🧠 Wallet System

In-game wallet balance

Transaction history

Deposit & withdrawal logs

Daily withdrawal limits

Fraud detection rules

📱 UI / UX Design
Design Principles

Mobile-first

One-thumb interaction

Minimal screens

Clear money visibility

Navigation Flow
Splash → Login → Lobby → Bet → Car Select → Race → Results
UI Highlights

Big “BET & RACE” button

Live wallet balance

Countdown animations

Kenyan color palette (green, red, black)

Thika Road signage inspired UI

UX Enhancements

Haptic feedback

Win/loss sound effects

Confetti animations on wins

Swahili phrases:

“Umeshinda!”

“Jaribu tena”

🏆 Rewards & Progression

Cash payouts

XP points

Car unlocks

Cosmetic skins

Weekly & monthly leaderboards

🛡️ Security & Fair Play

Server-side race result validation

Anti-cheat checks

Encrypted wallet data

KYC required for large withdrawals

Rate limiting on bets

🧑‍💼 Admin & Backend

Manage users & wallets

Adjust odds & house margin

View transaction logs

Flag suspicious accounts

Approve KYC documents

🛠️ Tech Stack

Unity 2022+

C#

Firebase / Node.js / PHP backend

Safaricom Daraja API

REST APIs

Cloud Functions

📦 Installation & Setup

Clone repository

Open project in Unity Hub

Set Android build target

Configure backend endpoints

Build APK / AAB

🚀 Future Roadmap

Real-time multiplayer races

Tournaments & jackpots

Clan betting

Live events

Esports mode

⚖️ Legal & Compliance

18+ only

Complies with Kenyan betting regulations

Responsible gaming limits

Clear terms & conditions
📄 License

This project is proprietary. Unauthorized copying, modification, or commercial use is prohibited.
