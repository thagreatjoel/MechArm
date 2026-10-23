
# Journal: 3D-Printed Robotic Arm

**Project Goal**: Make a light-weight robotic arm that can smoothly move, have Wi-Fi functionality and, potentially, artificial intelligence capability in the future.
**Controler**: ESP32/Arduino uno


---

## Phase 1:

*   The first thought was **28BYJ-48 stepper motor**.
*   **Problem:** It has very poor torque and is weaj slow and unsuitable to lift an arm, especially shoulder and elbow joints.
*   **Solution**: The concept upgraded to the usw of **MG995 servos** for shoulder, elbow, wrist and MG995 360 for the base.

### Final Motor Concept (Hybrid Concept)
*   **Base Rotation**: MG995 360 Continuous Rotation Servo.
*   **Elbow, Wrist**: Standard MG995 servos.
*   **Gripper**: SG90 Micro Servo .

---

## Phase 2:  CAD

### Base Joint 
*   **The Bearing: Chose to use the 625ZZ bearing
*   **The Fit:** The motor is placed below the base plate. The D-shaft goes into the base from the bottom.
*   **The Recess:** There must be a recess measuring 16.1mm in width and 5mm in depth where the 625ZZbearing can be pressfitted.
*   **The Clearance:** Designed a 1mm clearance at the bottom of the rotating plate's outside edge from the fixed base to ensure that there is no friction..
*   **The Friction:** Rubber wave washer was placed on top of the bearing to increase the friction in the joint...

---

### Rotating Platform 
*   **Design:** A 5 wheel with curved cutouts to reduce weight
*   **Spoke Dimensions:** 8mm wide at the center hub, reducing to 4mm near the edge, Thickness is 3mm
*   **Important Note:** Added fillets at all inner joints to avoid breaking the plastic due to strain.
*   **Mounting:** A Dshaped hole in the center hub to mount the motor shaft, with an M3 set screw hole on the side..
* also i will be useinf an aluminium horn for extra grip

---
## Phase 3: 
---

## Journal 1: Initial Concept & Base Design

Date: 10/8/2026
I atually worked on the base of the arm.. the base can move 360.. it has a metal bearing i the middle. it can help the base part stay steady and move with no vibration. there is a stepper motor underneath the base which move it 360.. above the base we have another motor to controll the x axis.. the can go atleas 200 degress both side..

Pictures:

<img width="490" height="430" alt="f31ab88e-d5ef-4af6-b28a-651b7b7ad1a2" src="https://github.com/user-attachments/assets/63cba1e6-cfc7-49af-883d-14b0147afebd" />

> Time spent this session: 9.7Hours
