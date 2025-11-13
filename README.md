# 🔊 Dub Auth — Protecting the Legacy of Reggae & Dancehall Dubplate Culture  

![GitHub last commit](https://img.shields.io/github/last-commit/jnrmello247-png/dub-auth)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Build](https://img.shields.io/badge/build-passing-brightgreen)

---

## 🌍 About  
**Dub Auth** (formerly **Authenticated-Verified.com**) continues the mission to **protect the history, legacy, and culture of the Reggae Dubplate and Sound Clash fraternity**.

It is the **first audio-watermarking and verification platform** built specifically for:

- Reggae & Dancehall Sound Systems  
- Artists & Producers  
- Collectors & Fans of Dub Culture  

---

## 🎯 Mission  
To **preserve and protect** the authentic voices of Reggae and Dancehall artists — ensuring every dubplate is **real**, **credited**, and **respected**.

---

## 🧠 Vision  
Dub Auth aims to build a trusted global ecosystem that:

- **Verifies authenticity** of dubplates (no AI impersonation)  
- **Protects artists’ rights & voices**  
- **Creates new revenue pathways** for artists and sound systems  
- **Documents and celebrates** Reggae & Dancehall culture worldwide  

---

## 🚀 MVP Features  

### 🎤 Artist Verification  
- Verified artist profiles  
- Cryptographic signing keys  
- Optional manual/community verification  

### 🎧 Dub Upload & Provenance  
- Upload or record dubs via mobile or web  
- Generate **SHA-256 hash + audio fingerprint**  
- Record metadata: artist → sound system → timestamp → signature  

### ✅ Authenticity Check  
- Digital signature validation  
- Audio fingerprint matching  
- AI voice-clone detection (ML model)  
- Human moderation fallback  

### 🏆 Marketplace  
- Artists accept commissions  
- Sound systems order verified dubs  
- Escrow payments + automatic commission split  

### 🔒 Transparency & Rights  
- Complete audit trail  
- Clear ownership & licensing  
- Optional blockchain/timestamp anchoring  

---

## 🧩 MVP System Architecture  

```mermaid
graph TD
    A[Frontend - Next.js / React] --> B[Backend API - Node.js / FastAPI]
    A --> C[Mobile App - React Native / Expo]

    C --> D[Local Audio Recording + Hash Signing]

    B --> E[Audio Upload - S3/Cloud Storage]
    B --> F[Signature Verification Service]
    B --> G[ML Service - Audio Fingerprint + AI Detection]
    B --> H[Payments - Stripe / Crypto Split]

    G --> I[AI Voice Clone Detection]
    G --> J[Audio Fingerprint Database]
