# 3D-Printed Robotic Arm

A lightweight, 3Dprinted robotic arm designed for smooth movement amd wireless control

## Project Overview

The project initially used a 28BYJ48 stepper motor, but testing showed that it did not provide enough torque and speed to move the arm effectively then the design has updated to use a servo motors.

The current motor configuration is:

- **Base:** MG995 360 continuous rotation servo
- **Shoulder, elbow, and wrist:** Three MG995 180 standard servos
- **Gripper:** SG90 micro servo

The ESP32 will act as the main controller. It will handle servo control and allow the arm to be operated wirelessly from a laptop or through a Bluetooth gamepad. AI-based vision and object recognition may be added in a future phase.

## Bill of Materials (BOM)
---

## Mechanical Design

### Base Rotation Mechanism

The base is designed to rotate while supporting the rest of the arm. Several features have been included to reduce friction, improve alignment, and keep the structure lightweight.

**Bearing fit**

The base plate includes a circular recess measuring 16.1mm in diameter and 5mm in depth for the 625ZZ bearing. The fit will be tested after the bearing arrives to ensure that it sits securely without excessive looseness.

**Motor mounting**

The servo will be mounted beneath the base plate. The rotating assembly will be aligned with the bearing to reduce wobble and provide stable movement. The shaft and coupling arrangement will need to be checked against the actual motor dimensions before final assembly.

**Five-spoke rotating platform**

The rotating platform uses a five-spoke design to reduce material usage and overall weight. Each spoke tapers from 8mm near the center to 4mm near the outer edge. Fillets are included at internal joints to reduce stress concentrations and help prevent cracking during operation.

**Clearance and friction control**

A 1mm gap is planned between the platform's outer rim and the stationary base to prevent rubbing during rotation.

A rubber wave washer will be positioned above the bearing to provide controlled friction and reduce unwanted movement. The final arrangement will be tested to ensure that tightening the assembly does not create excessive friction or interfere with rotation.

---


i had wrote detailed development notes, session dates, test results, and progress photographs are maintained in `journal.md`.

The journal will be used to document design changes record issues that comes during testing, and track the projects progress from the initial prototype to the rovotic arm
