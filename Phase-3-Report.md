# MEE 342 Phase 3 Report

**Team:** Jay-Lam

**Team Members:** Michael Spiller, Luca Santoni, Adam Ortiz, Siping Ruan, Yeonwoo Kim, Jafet Torres Maldonado

---

## Prototype Iterations

### Prototype Iteration 1

<img src="MEE342-Iteration-1.jpeg" width="500">

### Prototype Iteration 2

<img src="MEE342-Iteration-2.jpeg" width="500">

---

## 1. Fabrication Details

For Phase 3, the original design was modified so it could be manufactured as a 3D printed prototype. The goal of the prototype was to demonstrate the main gear reduction function of the design at a reduced scale and under safe manual operating conditions.

The final printed prototype was not intended to operate at full speed or full load. Instead, it was used to verify the basic motion of the gear train, confirm the gear ratio, observe backlash, and evaluate whether the printed parts could be assembled and operated smoothly.

### Design Changes for 3D Printing

The model was modified from the original design to improve printability, simplify assembly, and allow the mechanism to be viewed during operation.

- Diametral pitch was changed from 6 teeth/in to 12 teeth/in.
- Gear face width was reduced from 1.5 in to 0.5 in.
- Shaft diameter was changed to a uniform 0.5 in diameter.
- No keyway was used in the 3D printed prototype.
- Clearance holes were used in the housing instead of bearings.
- A handle was added to the input shaft so the model could be manually spun.
- The housing was skeletonized so the moving parts could be viewed during operation.

These changes made the prototype easier to print and assemble, but they also made it less representative of a final loaded mechanical design. The simplified prototype was appropriate for demonstrating motion and gear reduction, but not for testing high-speed or high-torque performance.

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

Because the prototype was designed for manual operation, the design did not include all of the final mechanical features from the original design. Bearings were replaced with clearance holes, and keyways were removed from the printed shaft and gear interfaces. These simplifications reduced manufacturing difficulty while still allowing the prototype to demonstrate the core function of the gear train.

---

## 2. Assembly Procedure and Challenges

After printing, the prototype was assembled manually. The assembly process focused on placing the gears and shafts into the housing, preventing the shafts from sliding out during operation, and adding a visible output marker for testing.

### Assembly Procedure

1. The printed parts were inspected after printing.
2. The shafts were inserted into the gears.
3. The gear and shaft assemblies were placed into the housing.
4. Two endcaps were placed on the outside of each shaft to prevent the shafts from moving during operation.
5. A small wheel was attached to the output shaft for testing and measurement.
6. A handle was attached to the input shaft so the model could be spun manually.
7. The model was assembled using superglue on all components.
8. The mechanism was rotated by hand to check for smooth operation.

### Assembly Results

The assembly process was successful. The shafts, gears, endcaps, handle, and output wheel were assembled without requiring any reprinted parts. No major issues were observed with slippage or hole clearances.

### Assembly Challenges

No major assembly failures occurred. The main assembly limitation was that the prototype used simplified printed features instead of final mechanical components. In particular, the housing used clearance holes instead of bearings, and the gear and shaft connections did not use keyways. These decisions made the prototype easier to assemble but limited its ability to represent the final design under higher loads or speeds.

---

## 3. Test Procedures, Results, and Interpretation

The prototype was tested manually to verify that the gear train functioned as expected. The main tests were gear ratio verification, smooth rotation, lubrication check, and backlash observation.

### Gear Ratio Test

A small mark was made on the output wheel to measure rotation. The input shaft was rotated by hand until the output shaft completed one full rotation.

The output shaft completed one full rotation after the input shaft was rotated nine times. This verified the expected 9:1 gear reduction.

### Smooth Rotation Test

The input shaft was rotated manually during normal operation. The gears and shafts rotated smoothly without binding.

This showed that the printed clearances and assembly alignment were acceptable for low-speed manual operation.

### Lubrication Check

The prototype was operated without additional lubrication. All parts rotated smoothly under normal manual operation.

This showed that lubrication was not required for the low-speed testing performed on the prototype. However, lubrication or bearings would likely be needed for higher-speed or longer-duration testing.

### Backlash Observation

A small amount of play was observed from gear lash between the input shaft and intermediate shaft. The backlash was approximately 3 degrees.

This backlash was likely caused by the printed gear tooth clearances, material flexibility, and simplified shaft support. Although the backlash did not prevent operation, it showed that the 3D printed prototype was less precise than a machined or fully supported final design.

### Summary of Test Results

| Test | Procedure | Result | Interpretation |
|---|---|---|---|
| Gear ratio test | Rotate input shaft until output shaft completes one full rotation | Output shaft rotated once after 9 input rotations | The expected 9:1 gear reduction was verified |
| Smooth rotation test | Rotate the input shaft by hand through normal operation | Prototype rotated smoothly | Printed clearances and alignment were acceptable |
| Lubrication check | Operate the prototype without additional lubrication | Parts rotated smoothly without lubrication | Lubrication was not needed for low-speed manual testing |
| Backlash observation | Observe play between input shaft and intermediate shaft | Approximately 3 degrees of gear lash | Backlash was present due to printed clearances and simplified supports |

---

## 4. Comparison With Phase 2 Predictions

The Phase 3 prototype matched the most important expected behavior from the earlier design. The gear train achieved the intended 9:1 gear reduction, and the prototype rotated smoothly by hand.

However, the prototype differed from the more realistic Phase 2 design because several features were simplified for 3D printing. The printed version used PLA, clearance holes instead of bearings, no keyways, and superglue assembly. These decisions made the prototype easier to manufacture and test, but they reduced its ability to represent the real design under higher speed or load.

| Phase 2 Expectation | Phase 3 Prototype Result | Explanation |
|---|---|---|
| Gear train should provide a 9:1 gear reduction | The measured reduction was 9:1 | The prototype successfully demonstrated the main gear reduction function |
| Mechanism should rotate smoothly | Prototype rotated smoothly by hand | Printed clearances were acceptable for manual operation |
| Shaft supports should allow rotation while maintaining alignment | Clearance holes supported the shafts during manual testing | Clearance holes worked for the prototype, but bearings would be better for realistic speeds |
| Shaft-gear connections should transfer torque | Superglue and simplified fits were sufficient for manual operation | This was acceptable for low-load testing, but not ideal for high torque |
| Gear mesh should have limited backlash | Approximately 3 degrees of backlash was observed | Backlash likely came from printed tooth clearances and material flexibility |
| Prototype should demonstrate the core mechanical function | Prototype showed visible gear motion and output reduction | Skeletonized housing helped make the function easier to observe |

---

## 5. Failures, Mistakes, and Surprises

No parts required reprinting, and no major failures occurred during assembly or manual testing. The prototype was able to rotate smoothly and demonstrate the expected 9:1 gear reduction.

The main issues and limitations were related to the simplified 3D printed design:

- Approximately 3 degrees of gear lash was observed between the input shaft and intermediate shaft.
- Clearance holes were used instead of bearings, which limited the realism of the shaft support.
- No keyways were used, so the shaft-gear connections were not representative of a final high-load design.
- Superglue was used to assemble the components, which may not be reliable under higher torque or long-term operation.
- PLA was acceptable for a functional demonstration, but it is not ideal for a final gear train operating under higher load.
- The reduced gear face width made the gears easier to print but reduced strength compared with the original design.
- The prototype was tested manually, so it did not fully represent motor-driven operation.

One positive result was that no reprints were needed. This suggests that the print modifications and clearances were effective enough for assembly and manual testing.

---

## 6. Version 2 Design Changes

If a second prototype iteration were made, the following changes would improve realism, durability, and test quality.

| Proposed Change | Reason |
|---|---|
| Attach a motor to the input shaft | This would simulate more realistic shaft speeds and provide more consistent testing |
| Use higher strength adhesive or mechanical fasteners | This would reduce the chance of parts separating under load |
| Use machined aluminum gears | Aluminum gears would provide more precise tooth profiles, better strength, and improved wear resistance |
| Add real bearings | Bearings would reduce friction, improve shaft alignment, and support higher shaft speeds |
| Use stepped shafts | Stepped shafts would improve strength and help locate gears more accurately |
| Add keyways or set screws | These would improve torque transfer between the shafts and gears |
| Perform a load or torque test | This would measure how much torque the prototype can transmit before slipping or failing |
| Improve gear tooth precision | This would reduce backlash and make the motion smoother |

---

## 7. Conclusion

The Phase 3 prototype successfully demonstrated the main function of the gear train. The 3D printed assembly achieved the expected 9:1 gear reduction, rotated smoothly by hand, and required no reprinted parts. The skeletonized housing also made it easier to observe the motion of the internal components.

The main limitations were caused by simplifications made for 3D printing, including PLA material, clearance holes instead of bearings, no keyways, superglue assembly, and manual testing instead of motor-driven testing. These choices were appropriate for a low-speed demonstration prototype, but a more realistic second version would need stronger materials, better shaft support, improved gear connections, and additional load testing.

---

## 8. Remaining Project Deliverables

In addition to this Phase 3 report, the project also requires the Phase 3 prototype demo and reflection video, final poster, and organized GitHub repository files.

The SolidWorks assembly file and `.glb` file will be added separately when the group member with the CAD files is available.

