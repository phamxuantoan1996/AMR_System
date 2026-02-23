# AMR_System
┌────────────────────────────┐
│       External Layer       │
└─────────────▲──────────────┘
              │
────────────────────────────────
        Application Layer
────────────────────────────────
 Executor
 MissionStateMachine
 MissionJob
 AMRStateMachine
────────────────────────────────
        Domain Layer
────────────────────────────────
 IAMRController
 AMRState
 MissionState
 AMRCommand
────────────────────────────────
     Infrastructure Layer
────────────────────────────────
 VendorController
 TCP / SDK
