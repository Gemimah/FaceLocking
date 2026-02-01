## Face Locking – Intelligent Robotics Assignment

**Overview**

Enhances a CPU-only ArcFace face recognition system with Face Locking: tracks a specific person across frames, even with other faces or brief occlusions, and logs simple face actions.

**Features**

Manual target selection (currently "Gabriel")

Face Locking: locks on the target identity, ignores others

Stable tracking: IOU + embedding similarity + timeout

Action detection: left/right movement, blink, smile, laugh

Action logging: saved as <name>_history_<timestamp>.txt

**Usage**

Run the system.

Select target identity.

System locks onto the face and detects actions in real time.