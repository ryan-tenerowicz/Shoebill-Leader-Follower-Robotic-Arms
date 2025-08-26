## Shoebill Arms Software Quick Start

This project’s arms are driven using the Vassar Robotics FeeTech Servo SDK. Use the SDK’s example programs to bring up, calibrate, and teleoperate the leader–follower arms.

### Get the SDK and run the examples
- **Visit the SDK repo**: [Vassar Robotics FeeTech Servo SDK](https://github.com/vassar-robotics/feetech-servo-sdk)
- **Clone and install**:
  ```bash
  git clone https://github.com/vassar-robotics/feetech-servo-sdk.git
  cd feetech-servo-sdk
  pip install -r requirements.txt
  ```
- **Run examples** (from the repo root):
  ```bash
  python examples/teleoperation.py
  python examples/set_middle_position.py
  ```

For environment, connection, and port/ID configuration details, follow the SDK’s README: [SDK README](https://github.com/vassar-robotics/feetech-servo-sdk/blob/main/README.md).

### Teleoperation (leader–follower)
- **File**: [`examples/teleoperation.py`](https://github.com/vassar-robotics/feetech-servo-sdk/blob/main/examples/teleoperation.py)
- **What it does**: Streams joint positions from a manually manipulated leader arm and writes those positions to a follower arm so the follower mirrors the leader in real time.
- **How to use**:
  - Connect both arms to your controller per the SDK README.
  - Ensure servo IDs/ports match your setup (see SDK README for configuration).
  - Run the script; move the leader arm to drive the follower.

### Calibration (set middle position)
- **File**: [`examples/set_middle_position.py`](https://github.com/vassar-robotics/feetech-servo-sdk/blob/main/examples/set_middle_position.py)
- **What it does**: Commands each servo to its middle position (typically value 2048) so both arms share a consistent mechanical zero reference.
- **Why it matters**: Establishes a fixed relative alignment between leader and follower joints, improving tracking accuracy during teleoperation.

### Writing custom control code
The SDK README explains how to write your own control programs, including:
- Initializing controllers and connecting to servos
- Reading/writing positions and feedback
- Setting operating modes (position/speed/torque/PWM)

See: [SDK README](https://github.com/vassar-robotics/feetech-servo-sdk/blob/main/README.md)

### Summary
- Use the SDK’s `/examples` to get the arms working quickly: teleoperation and calibration.
- Refer to the SDK README for configuration and for building custom servo control code.

References: [teleoperation.py](https://github.com/vassar-robotics/feetech-servo-sdk/blob/main/examples/teleoperation.py), [set_middle_position.py](https://github.com/vassar-robotics/feetech-servo-sdk/blob/main/examples/set_middle_position.py), [SDK README](https://github.com/vassar-robotics/feetech-servo-sdk/blob/main/README.md)

