# Machine Condition Monitoring

## Problem Statement
Small production units depend on critical machines. Unexpected machine failures cause production delays and financial loss.

## Objective
Monitor machine temperature and vibration, detect abnormal conditions, and help schedule maintenance before machine failure.

## Tools Used
- Flutter
- Dart
- CSV Dataset
- Visual Studio Code
- Chrome (Flutter Web)

## Features
- Select Machine
- Enter Temperature
- Enter Vibration
- Validate Input
- Save Reading Message

## Dataset Fields

| Field | Description |
|--------|-------------|
| reading_id | Unique reading ID |
| machine_id | Machine ID |
| vibration | Vibration value (mm/s) |
| temperature | Temperature (°C) |
| alert_flag | 0 = Normal, 1 = Alert |
| recorded_at | Date and Time |

## How to Run

1. Open project in VS Code.
2. Run `flutter pub get`
3. Run `flutter run`
4. Enter machine readings.
5. Click SAVE READING.

## Alert Logic

Alert is generated when machine vibration or temperature exceeds the normal operating range.

## Current Status

✅ Dataset Completed

✅ Capture Screen Completed

✅ Input Validation Completed

⏳ Future Work:
- Save readings into SQLite
- ESP32/Wokwi integration
- Cloud synchronization