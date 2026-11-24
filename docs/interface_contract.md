# Interface Contract

Agree on this in week 1, before writing detection code.

## Database table: events

| Column | Type | Notes |
|---|---|---|
| Session_ID | text | e.g. S01 |
| Timestamp | text | Full ISO datetime |
| Behavior | text | Normal, Drowsy, Distracted, Using Phone, Eating, Drinking |
| EAR | real | |
| Head_Pose | text | Forward, Down/Side, ... |
| Confidence | real | 0 to 1 |
| Alert | text | ON / OFF |

## Detector outputs (to be agreed)

- Face analysis (A):
- Object detection (B):
- State machine (B):

## API endpoints (to be agreed)

- Start session:
- Stop session:
- Current state:
