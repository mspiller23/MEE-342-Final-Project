# MEE 342 Phase 3 Report

**Team:** Jay-Lam

**Team Members:** Michael Spiller, Luca Santoni, Adam Ortiz, Siping Ruan, Yeonwoo Kim, Jafet Torres Maldonado

---

## Prototype Iterations

### Prototype Iteration 1

<img src="MEE342-Iteration-1.jpeg" width="500">

### Prototype Iteration 2

<img src="MEE342-Iteration-2.jpeg" width="500">

### Final Poster

<img src="MEE342-Poster.jpeg" width="500">

---

## 1. Fabrication Details

For Phase 3, the original design was modified so it could be manufactured as a 3D printed prototype. The goal of the prototype was to demonstrate the main gear reduction function of the design at a reduced scale and under safe operating conditions.

The first version of the printed prototype was designed for manual testing. The later version was improved into a working motorized model with a motor-driven input and an output turning dial. This allowed the gear train to operate continuously and made the reduced output speed easier to observe.

### Design Changes for 3D Printing

The model was modified from the original design to improve printability, simplify assembly, and allow the mechanism to be viewed during operation.

- Diametral pitch was changed from 6 teeth/in to 12 teeth/in.
- Gear face width was reduced from 1.5 in to 0.5 in.
- Shaft diameter was changed to a uniform 0.5 in diameter.
- No keyway was used in the 3D printed prototype.
- Clearance holes were used in the housing instead of bearings.
- A handle was added to the input shaft for early manual testing.
- A motor was added to the final prototype to drive the input shaft.
- A turning dial was added to the output side so the output motion and reduced speed could be observed clearly.
- The housing was skeletonized so the moving parts could be viewed during operation.

These changes made the prototype easier to print and assemble while still allowing the gear train motion and speed reduction to be demonstrated. The motorized version improved the final demonstration because the system could operate continuously instead of only being turned by hand.

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

The addition of the motor and output dial improved the final prototype by allowing the gear train to be operated continuously and by making the output rotation easier to observe.

---

## 2. Assembly Procedure and Challenges

After printing, the prototype was assembled manually. The assembly process focused on placing the gears and shafts into the housing, preventing the shafts from sliding out during operation, and adding a visible output marker for testing. The final version also included a motor connected to the input side and a turning dial connected to the output side.

### Assembly Procedure

1. The printed parts were inspected after printing.
2. The shafts were inserted into the gears.
3. The gear and shaft assemblies were placed into the housing.
4. Two endcaps were placed on the outside of each shaft to prevent the shafts from moving during operation.
5. A small wheel or turning dial was attached to the output shaft for testing and measurement.
6. A handle was attached to the input shaft for early manual testing.
7. A motor was added to the input shaft for the final working prototype.
8. The model was assembled using superglue on printed components.
9. The mechanism was first rotated by hand to check for smooth operation.
10. The motorized version was operated to demonstrate continuous gear train motion and output speed reduction.

### Assembly Results

The assembly process was successful. The shafts, gears, endcaps, handle, motor, and output dial were assembled into a working prototype. No major issues were observed with slippage or hole clearances, and no parts required reprinting.

The motorized prototype was a major improvement because it demonstrated that the gear train could operate continuously instead of only being turned by hand. The output dial also made the reduced output speed easier to see during operation.

### Assembly Challenges

No major assembly failures occurred. The main assembly limitation was that the prototype used simplified printed features instead of final mechanical components. In particular, the housing used clearance holes instead of bearings, and the gear and shaft connections did not use keyways.

The motorized version improved the demonstration, but it also made the limitations of the printed prototype more important. Under motorized operation, alignment, shaft support, adhesive strength, and gear lash matter more than they do during slow manual testing.

---

## 3. Test Procedures, Results, and Interpretation

The prototype was tested to verify that the gear train functioned as expected. Testing included manual gear ratio verification, smooth rotation, motorized operation, lubrication observation, and backlash observation.

### Gear Ratio Test

A small mark was made on the output wheel or dial to measure rotation. The input shaft was rotated until the output shaft completed one full rotation.

The output shaft completed one full rotation after the input shaft was rotated nine times. This verified the expected 9:1 gear reduction.

### Smooth Rotation Test

The input shaft was rotated manually during normal operation. The gears and shafts rotated smoothly without binding.

This showed that the printed clearances and assembly alignment were acceptable for low-speed manual operation.

### Motorized Operation Test

The final prototype was tested using a motor attached to the input shaft. The motor drove the gear train continuously, and the output dial turned at the reduced output speed.

This test showed that the prototype was able to demonstrate the gear reduction more realistically than the hand-cranked version. The motorized input made the relationship between input speed and output speed easier to observe.

### Lubrication Check

The prototype was operated without additional lubrication. All parts rotated smoothly under normal operation.

This showed that lubrication was not required for the low-speed testing performed on the prototype. However, lubrication or bearings would improve durability for higher-speed or longer-duration motorized testing.

### Backlash Observation

A small amount of play was observed from gear lash between the input shaft and intermediate shaft. The backlash was approximately 3 degrees.

This backlash was likely caused by the printed gear tooth clearances, material flexibility, and simplified shaft support. Although the backlash did not prevent operation, it showed that the 3D printed prototype was less precise than a machined or fully supported final design.

### Summary of Test Results

| Test | Procedure | Result | Interpretation |
|---|---|---|---|
| Gear ratio test | Rotate input shaft until output shaft completes one full rotation | Output shaft rotated once after 9 input rotations | The expected 9:1 gear reduction was verified |
| Smooth rotation test | Rotate the input shaft by hand through normal operation | Prototype rotated smoothly | Printed clearances and alignment were acceptable |
| Motorized operation test | Use motor to drive the input shaft and observe output dial | Output dial rotated continuously at reduced speed | The prototype successfully demonstrated powered gear reduction |
| Lubrication check | Operate the prototype without additional lubrication | Parts rotated smoothly without lubrication | Lubrication was not needed for low-speed testing |
| Backlash observation | Observe play between input shaft and intermediate shaft | Approximately 3 degrees of gear lash | Backlash was present due to printed clearances and simplified supports |

---

## 4. Comparison With Phase 2 Predictions

The Phase 3 prototype matched the most important expected behavior from the earlier design. The gear train achieved the intended 9:1 gear reduction, and the prototype rotated smoothly during manual and motorized testing.

The final motorized prototype improved the comparison with the Phase 2 design because it allowed the mechanism to operate with a powered input instead of only being turned by hand. The output dial showed the reduced output speed clearly, which made the speed reduction easier to verify visually.

The prototype still differed from the more realistic Phase 2 design because several features were simplified for 3D printing. The printed version used PLA, clearance holes instead of bearings, no keyways, and superglue assembly. These decisions made the prototype easier to manufacture and test, while still allowing the core function to be demonstrated.

| Phase 2 Expectation | Phase 3 Prototype Result | Explanation |
|---|---|---|
| Gear train should provide a 9:1 gear reduction | The measured reduction was 9:1 | The prototype successfully demonstrated the main gear reduction function |
| Mechanism should rotate smoothly | Prototype rotated smoothly by hand and with motor input | Printed clearances were acceptable for demonstration testing |
| Prototype should demonstrate powered input | Final prototype included a motor on the input shaft | The motor made the demonstration more realistic than manual operation alone |
| Output speed should be visibly reduced | Output dial rotated at the reduced output speed | The dial made the reduction easy to observe |
| Shaft supports should allow rotation while maintaining alignment | Clearance holes supported the shafts during testing | Clearance holes worked for the prototype, but bearings would be better for realistic speeds |
| Shaft-gear connections should transfer torque | Superglue and simplified fits were sufficient for prototype operation | This worked for the demonstration, but stronger connections would be needed for higher loads |
| Gear mesh should have limited backlash | Approximately 3 degrees of backlash was observed | Backlash likely came from printed tooth clearances and material flexibility |
| Prototype should demonstrate the core mechanical function | Prototype showed visible gear motion and output reduction | Skeletonized housing helped make the function easier to observe |

---

## 5. Failures, Mistakes, and Surprises

No parts required reprinting, and no major failures occurred during assembly or testing. The prototype was able to rotate smoothly, demonstrate the expected 9:1 gear reduction, and operate with a motorized input.

A major positive surprise was the final working motorized model. The motor and output dial made the prototype more complete than the earlier manual version and improved the quality of the final demonstration.

The main issues and limitations were related to the simplified 3D printed design:

- Approximately 3 degrees of gear lash was observed between the input shaft and intermediate shaft.
- Clearance holes were used instead of bearings, which limited the realism of the shaft support.
- No keyways were used, so the shaft-gear connections were not representative of a final high-load design.
- Superglue was used to assemble the components, which may not be reliable under higher torque or long-term motorized operation.
- PLA was acceptable for a functional demonstration, but it is not ideal for a final gear train operating under higher load.
- The reduced gear face width made the gears easier to print but reduced strength compared with the original design.
- The motorized prototype improved the demonstration, but longer motorized testing would require stronger shaft supports and more durable interfaces.

One positive result was that no reprints were needed. This suggests that the print modifications and clearances were effective enough for assembly and testing.

---

## 6. Version 2 Design Changes

The addition of the motor and output dial already addressed one of the major planned improvements from the manual prototype. If another prototype iteration were made, the following changes would improve realism, durability, and test quality.

| Proposed Change | Reason |
|---|---|
| Improve motor mounting | A more rigid motor mount would improve alignment and reduce vibration |
| Use higher strength adhesive or mechanical fasteners | This would reduce the chance of parts separating under motorized operation |
| Use machined aluminum gears | Aluminum gears would provide more precise tooth profiles, better strength, and improved wear resistance |
| Add real bearings | Bearings would reduce friction, improve shaft alignment, and support higher shaft speeds |
| Use stepped shafts | Stepped shafts would improve strength and help locate gears more accurately |
| Add keyways or set screws | These would improve torque transfer between the shafts and gears |
| Perform a load or torque test | This would measure how much torque the prototype can transmit before slipping or failing |
| Improve gear tooth precision | This would reduce backlash and make the motion smoother |
| Add speed measurement data | Measuring input and output RPM would give a more quantitative comparison to the expected 9:1 ratio |

---


## 7. Conclusion

The Phase 3 prototype successfully demonstrated the main function of the gear train. The 3D printed assembly achieved the expected 9:1 gear reduction, rotated smoothly, and required no reprinted parts. The skeletonized housing made it easier to observe the internal gear motion.

The final motorized version improved the project by allowing the input shaft to be powered by a motor and by using an output dial to show the reduced output speed. This made the prototype a stronger demonstration of the intended mechanical function than the earlier hand-cranked version.

The main limitations were caused by simplifications made for 3D printing, including PLA material, clearance holes instead of bearings, no keyways, and superglue assembly. These choices were appropriate for a functional demonstration prototype, but a more realistic second version would need stronger materials, better shaft support, improved gear connections, and additional speed or load testing.
