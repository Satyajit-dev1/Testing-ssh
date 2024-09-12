# Split Jewels Flow - Pledge Management
**Split Jewels** is a submodule within the ruppek-agent-app, serving a pledge management system designed to facilitate various aspects of loan pledges, schemes including UPI Autopay management. The submodule follows **Model-View-ViewModel (MVVM)** architecture to ensure a clear separation of concerns & maintainability.

## Project Structure

The submodule is organized into the following structure:
```
split_jewels/
├── adapters/                #Recylerview adapters
├── data/
│   ├── models/              # Data models
│   ├── remote/              # Remote API interfaces
│   └── repository/          # Repository classes
├── di/                      # Dependency injection modules
├── screens/                 # UI components (fragments)
├── activity/                # Activities
└── viewmodel/               # ViewModels

```

## Architecture

The submodule follows the **MVVM (Model-View-ViewModel)** architecture .

## Features

- **UPI Autopay Management**: Registers, and track UPI mandates.
- **Multi-Pledge Management**: Manage multiple pledges simultaneously.
- **Scheme Selction**: Select schemes based on the pledges selected.

## Prerequisites

Before you begin, ensure you have the following installed:

- **Java Development Kit (JDK) 17** or later 
- **Android Studio Koala** or latest 
- **Gradle 7.4** or later
- **Git** for version control
- **Internet connection** with **VPN** to download dependencies

## Installation

Follow these steps to setup locally:

**Clone the main repository:**

   ```bash
   git clone git@github.com:Rupeek/rupeek-agent-android.git
   
