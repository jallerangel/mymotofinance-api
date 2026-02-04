# 🏍️ MyMotoFinances API

> **The Central Brain of the MyMotoFinances Platform.**

This repository contains the **Backend Core** built with **NestJS** and **Prisma**. It serves as the orchestration layer for a hybrid financial platform designed for motorcycle taxi drivers in LatAm.

## 🏗️ Architecture Overview

This API acts as the bridge between two client applications:
1.  **Main App (Expo/React Native):** For financial dashboarding, goal setting, and manual tracking.
2.  **Companion Service (Android/Kotlin):** For automated income ingestion via notification listeners (Uber/DiDi).

## 🚀 Key Features

-   **Session Management:** Tracks `WorkShifts` to calculate real-time hourly earnings (`$/hr`).
-   **Hybrid Data Ingestion:** Supports both manual entry and automated event-driven inputs.
-   **Smart Allocation:** Automatically distributes income towards debts and savings goals based on user-defined priority logic.
-   **Secure Auth:** JWT-based authentication via Passport strategy.
-   **Data Integrity:** Robust modeling with Prisma ORM and PostgreSQL.

## 🛠️ Tech Stack

-   **Framework:** NestJS (Node.js)
-   **Database:** PostgreSQL
-   **ORM:** Prisma
-   **Auth:** Passport + JWT
-   **Language:** TypeScript

---
*Part of the MyMotoFinances Project Portfolio.*
