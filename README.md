# Final Robot Design & assembling Algorithm

This repository contains the mechanical CAD files for a fully 3D-printable robot dog. This robot was designed during an AI & Robotics engineering internship at **Smart Methods**.

The design was focusing on real-world hardware integration, durability, and easy 3D printing and assembly.

## Technical Specifications
* **Dimensions:** 600 mm (Length) x 350 mm (Height).
* **Actuators:** Designed to house 12x MG996R standard metal gear servos for the main joints.
* **Sensors:** V-shaped angled front face with custom recessed sockets for two HC-SR04 ultrasonic sensors.
* **Joints:** Uses a mechanical linkage system with a 0.5 mm tolerance to ensure smooth movement after 3D printing.

## 3D CAD Model
You can view the interactive 3D design directly in your browser here:
[https://cad.onshape.com/documents/0b0644969d0130974522928c/w/bfb1d92e6729126245d96304/e/67d5918c0bec445543112798?renderMode=0&uiState=6a67ef1e2ed50b8a8000f734]


---

## Assembly Algorithm

Step-by-step instructions to build the physical robot after printing the parts:

### Phase 1: Prepare the Parts
1. **Print all plastic parts:** 3D print the main body, the 4 upper legs (thighs), and the 4 lower legs (shins).
2. **Gather hardware:** Collect all servo motors, metal bearings, metal pins (shafts), and screws.

### Phase 2: Build the Legs (Do this 4 times)
1. **Insert the bearings:** Push the small circular metal bearings into the round holes on the upper leg and lower leg joints.
2. **Attach the lower leg:** Put the lower leg (shin) inside the upper leg (thigh) joint.
3. **Insert the pin:** Push the metal pin (shaft) through the bearings to lock the upper and lower leg together. Make sure the joint can swing freely.
4. **Install the knee motor:** Push the servo motor into the rectangular hole in the upper leg. Use screws to fix it in place. Connect the motor gear to the leg linkage.

### Phase 3: Connect Legs to the Main Body
1. **Install the hip motors:** Push the 4 servo motors into the rectangular holes on the sides of the main body (chassis). Use screws to secure them.
2. **Attach the legs:** Slide the top hole of the assembled leg onto the hip motor gear on the main body.
3. **Lock the legs:** Put a screw through the leg into the motor gear so the leg does not fall off.
