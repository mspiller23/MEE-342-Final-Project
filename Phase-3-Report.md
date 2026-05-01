# MEE 342 Phase 3 Report

**Team:** Jay-Lam

**Team Members:** Michael Spiller, Luca Santoni, Adam Ortiz, Siping Ruan, Yeonwoo Kim, Jafet Torres Maldonado

---

## Prototype Iterations

### Prototype Iteration 1: Manual Gear Train Demonstration

<img src="MEE342-Iteration-1.jpeg" width="500">

The first prototype iteration was a simplified gear train demonstration. It used the printed gears and shafts with a hand-crank input. A single wheel was attached to the output shaft so the output rotation could be observed and counted.

This version was used to verify the basic gear train motion and confirm the expected 9:1 gear ratio. When the input shaft was rotated nine times by hand, the output wheel completed one full rotation.

### Prototype Iteration 2: Motorized Working Prototype

<img src="MEE342-Iteration-2.jpeg" width="500">

The second prototype iteration used the same gear dimensions as the first version, but it was upgraded into a working motorized model. Instead of only using a hand crank, the input shaft was driven by a motor. A speed-control dial was used to adjust the motor speed during operation.

The output shaft was connected to two wheels wrapped with thin rubber tape. The tape increased traction so the wheels could grip better while turning. This version showed that the gear train not only had the correct 9:1 ratio, but also moved continuously under powered input.

### Presentation Poster

<img src="MEE342-Poster.jpeg" width="500">

---

## 1. Fabrication Details

For Phase 3, the original design was modified so it could be manufactured as a 3D printed prototype. The goal of the prototype was to demonstrate the main gear reduction function of the design at a reduced scale and under safe operating conditions.

The first prototype iteration was a manual gear train demonstration. It included the printed gear train, a hand-crank input, and a single output wheel. This version was used to verify the expected 9:1 gear ratio by counting the number of input rotations required to produce one full output rotation.

The second prototype iteration used the same gear dimensions, but it was improved into a working motorized model. A motor was added to drive the input shaft, and a speed-control dial was added so the motor speed could be adjusted during operation. The output shaft was connected to two wheels wrapped with thin rubber tape to improve traction while the wheels turned.

### Design Changes for 3D Printing

The model was modified from the original design to improve printability, simplify assembly, and allow the mechanism to be viewed during operation.

- Diametral pitch was changed from 6 teeth/in to 12 teeth/in.
- Gear face width was reduced from 1.5 in to 0.5 in.
- Shaft diameter was changed to a uniform 0.5 in diameter.
- No keyway was used in the 3D printed prototype.
- Clearance holes were used in the housing instead of bearings.
- A hand crank was added to the input shaft for the first prototype iteration.
- A single output wheel was added to the first prototype iteration to show output rotation.
- A motor was added to the second prototype iteration to drive the input shaft.
- A speed-control dial was added to adjust the motor speed during operation.
- The output shaft was connected to two wheels.
- Thin rubber tape was added around the wheels to improve traction while turning.
- The housing was skeletonized so the moving parts could be viewed during operation.

These changes made the prototype easier to print and assemble while still allowing the gear train motion and speed reduction to be demonstrated. The first iteration verified the 9:1 gear ratio manually, while the second iteration showed continuous powered operation using the same gear dimensions.

### 3D Print Parameters

| Parameter | Value |
|---|---|
| Printer | Bambu Lab P1S |
| Filament | Elegoo PLA, black |
| Infill | 25% gyroid |
| Wall loops | 2 for gears, 1 for everything else |
| Total filament used | 258 g |
| Number of reprints | 0 |

### Print Preparation

The parts were prepared for 3D printing by simplifying the geometry and adjusting dimensions to better fit the limitations of the printing process. The gear teeth, shafts, and housing were modified so the parts could be printed and assembled more easily.

Because the prototype was designed for demonstration, the design did not include all final mechanical features from the original design. Bearings were replaced with clearance holes, and keyways were removed from the printed shaft and gear interfaces. These simplifications reduced manufacturing difficulty while still allowing the prototype to demonstrate the core function of the gear train.

The addition of the motor, speed-control dial, and traction wheels in the second iteration improved the final prototype by allowing the gear train to be operated continuously and by making the output wheel motion easier to observe.

---

## 2. Assembly Procedure and Challenges

After printing, the prototype was assembled manually. The assembly process focused on placing the gears and shafts into the housing, preventing the shafts from sliding out during operation, and adding visible output wheels for testing. The second iteration also included a motor connected to the input side, a speed-control dial, and two wheels connected to the output shaft.

### Assembly Procedure

1. The printed parts were inspected after printing.
2. The shafts were inserted into the gears.
3. The gear and shaft assemblies were placed into the housing.
4. Two endcaps were placed on the outside of each shaft to prevent the shafts from moving during operation.
5. For the first iteration, a hand crank was attached to the input shaft.
6. For the first iteration, a single wheel was attached to the output shaft so the output rotation could be observed.
7. The first iteration was manually rotated to verify the 9:1 gear ratio.
8. For the second iteration, the same gear dimensions were used.
9. A motor was added to the input shaft for the final working prototype.
10. A speed-control dial was connected so the motor speed could be adjusted during operation.
11. Two wheels were connected to the output shaft.
12. Thin rubber tape was wrapped around the wheels to improve traction.
13. The model was assembled using superglue on printed components.
14. The motorized version was operated to demonstrate continuous gear train motion and wheel rotation.

### Assembly Results

The assembly process was successful, and the prototype worked immediately after assembly. The first iteration demonstrated the gear train manually using a hand crank and a single output wheel. This confirmed that the printed gear train produced the expected 9:1 ratio.

The second iteration kept the same gear dimensions but added a motor-driven input, speed-control dial, and two output wheels wrapped with thin rubber tape. This created a working powered prototype that moved continuously and allowed the output wheel motion to be observed during operation.

No major issues were observed with slippage or hole clearances, and no parts required reprinting.

### Assembly Challenges

No major assembly failures occurred. The main assembly limitation was that the prototype used simplified printed features instead of final mechanical components. In particular, the housing used clearance holes instead of bearings, and the gear and shaft connections did not use keyways.

The motorized version improved the demonstration, but it also made the limitations of the printed prototype more important. Under motorized operation, alignment, shaft support, adhesive strength, gear lash, and wheel traction matter more than they do during slow manual testing.

---

## 3. Test Procedures, Results, and Interpretation

The prototype was tested in two stages. The first iteration was tested manually using a hand-crank input and a single output wheel to confirm the gear ratio. The second iteration was tested as a motorized working model using the same gear dimensions, with the motor driving the input shaft and the output shaft driving two traction wheels.

Testing included manual gear ratio verification, smooth rotation, motorized operation, and backlash observation.

### Gear Ratio Test

The gear ratio was tested using the first prototype iteration. A single wheel was attached to the output shaft, and the input shaft was rotated by hand using the hand crank.

The output wheel completed one full rotation after the input shaft was rotated nine times. This verified the expected 9:1 gear reduction.

### Smooth Rotation Test

The input shaft was rotated manually during normal operation. The gears and shafts rotated smoothly without binding.

This showed that the printed clearances and assembly alignment were acceptable for low-speed manual operation.

### Motorized Operation Test

The second prototype iteration used the same gear dimensions as the first version, but the input shaft was driven by a motor. A speed-control dial was used to adjust the motor speed during operation.

The output shaft was connected to two wheels wrapped with thin rubber tape to improve traction. This test showed that the gear train did not only work as a manual demonstration. It also moved continuously under powered input and transferred motion to the output wheels.

### Backlash Observation

A small amount of play was observed from gear lash between the input shaft and intermediate shaft. The backlash was approximately 3 degrees.

This backlash was likely caused by the printed gear tooth clearances, material flexibility, and simplified shaft support. Although the backlash did not prevent operation, it showed that the 3D printed prototype was less precise than a machined or fully supported final design.

### Summary of Test Results

| Test | Prototype Iteration | Procedure | Result | Interpretation |
|---|---|---|---|---|
| Gear ratio test | Iteration 1 | Rotate hand-crank input until output wheel completes one full rotation | Output wheel rotated once after 9 input rotations | The expected 9:1 gear reduction was verified |
| Smooth rotation test | Iteration 1 and 2 | Rotate the input and observe gear movement | Prototype rotated smoothly without binding | Printed clearances and alignment were acceptable |
| Motorized operation test | Iteration 2 | Use motor to drive the input shaft, adjust speed with the dial, and observe the output wheels | Output wheels rotated continuously with added traction from rubber tape | The prototype successfully demonstrated powered gear reduction and output wheel motion |
| Backlash observation | Iteration 1 and 2 | Observe play between input shaft and intermediate shaft | Approximately 3 degrees of gear lash | Backlash was present due to printed clearances and simplified supports |

---

## 4. Comparison With Phase 2 Predictions

The Phase 3 prototype matched the most important expected behavior from the earlier design. The first iteration achieved the intended 9:1 gear reduction using a hand-crank input and a single output wheel. The second iteration used the same gear dimensions and showed that the gear train could also move continuously under motorized input.

The final motorized prototype improved the comparison with the Phase 2 design because it allowed the mechanism to operate with a powered input instead of only being turned by hand. The speed-control dial allowed the motor speed to be adjusted, and the two rubber-wrapped output wheels made the output motion visible.

The prototype still differed from the more realistic Phase 2 design because several features were simplified for 3D printing. The printed version used PLA, clearance holes instead of bearings, no keyways, and superglue assembly. These decisions made the prototype easier to manufacture and test, while still allowing the core function to be demonstrated.

| Phase 2 Expectation | Phase 3 Prototype Result | Explanation |
|---|---|---|
| Gear train should provide a 9:1 gear reduction | The measured reduction was 9:1 | The first iteration successfully demonstrated the main gear reduction function |
| Mechanism should rotate smoothly | Prototype rotated smoothly by hand and with motor input | Printed clearances were acceptable for demonstration testing |
| Prototype should demonstrate powered input | Second iteration included a motor on the input shaft with a speed-control dial | The motor and dial made the demonstration more realistic and allowed the speed to be adjusted |
| Output motion should be visible | Output shaft drove two wheels wrapped with thin rubber tape | The wheels made the output motion visible, and the rubber tape improved traction |
| Shaft supports should allow rotation while maintaining alignment | Clearance holes supported the shafts during testing | Clearance holes worked for the prototype, but bearings would be better for realistic speeds |
| Shaft-gear connections should transfer torque | Superglue and simplified fits were sufficient for prototype operation | This worked for the demonstration, but stronger connections would be needed for higher loads |
| Gear mesh should have limited backlash | Approximately 3 degrees of backlash was observed | Backlash likely came from printed tooth clearances and material flexibility |
| Prototype should demonstrate the core mechanical function | Prototype showed visible gear motion and output wheel rotation | Skeletonized housing helped make the function easier to observe |

---

## 5. Failures, Mistakes, and Surprises

The prototype worked successfully on the first assembly and test. No parts required reprinting, and no major failures occurred during assembly, manual testing, or motorized operation. The mechanism rotated smoothly, demonstrated the expected 9:1 gear reduction, and operated with the motorized input.

One positive surprise was that the prototype functioned immediately after assembly. The printed clearances, gear alignment, shaft placement, and overall assembly were accurate enough for the gear train to run without major adjustments. The final motorized version also improved the demonstration by using a speed-control dial and rubber-wrapped output wheels to show controlled powered motion.

Although the prototype worked well, several design limitations were still identified:

- Approximately 3 degrees of gear lash was observed between the input shaft and intermediate shaft.
- Clearance holes were used instead of bearings, which limited the realism of the shaft support.
- No keyways were used, so the shaft-gear connections were not representative of a final high-load design.
- Superglue was used to assemble the components, which may not be reliable under higher torque or long-term motorized operation.
- PLA was acceptable for a functional demonstration, but it is not ideal for a final gear train operating under higher load.
- The reduced gear face width made the gears easier to print but reduced strength compared with the original design.
- The output wheels required added traction, which was improved using thin rubber tape.
- Longer motorized testing would require stronger shaft supports and more durable interfaces.

Overall, the immediate success of the prototype showed that the 3D print modifications, clearances, and assembly approach were effective for demonstrating the core gear reduction function.

---

## 6. Version 2 Design Changes

The addition of the motor, speed-control dial, and output wheels already addressed several major improvements from the manual prototype. If another prototype iteration were made, the following changes would improve realism, durability, and test quality.

| Proposed Change | Reason |
|---|---|
| Improve motor mounting | A more rigid motor mount would improve alignment and reduce vibration |
| Improve speed-control integration | A more permanent dial and wiring setup would make motor speed adjustment more reliable |
| Use higher strength adhesive or mechanical fasteners | This would reduce the chance of parts separating under motorized operation |
| Use machined aluminum gears | Aluminum gears would provide more precise tooth profiles, better strength, and improved wear resistance |
| Add real bearings | Bearings would reduce friction, improve shaft alignment, and support higher shaft speeds |
| Use stepped shafts | Stepped shafts would improve strength and help locate gears more accurately |
| Add keyways or set screws | These would improve torque transfer between the shafts and gears |
| Improve traction wheel design | Molded or fitted rubber wheels would provide better traction than taped wheels |
| Perform a load or traction test | This would measure how well the output wheels transfer motion before slipping |
| Add speed measurement data | Measuring input and output RPM would give a more quantitative comparison to the expected 9:1 ratio |
