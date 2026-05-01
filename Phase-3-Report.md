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

The second prototype iteration used the same gear dimensions as the first version, but it was upgraded into a working motorized model. Instead of only using a hand crank, the input shaft was driven by a motor. The output side included a turning dial so the reduced output speed could be seen clearly during operation.

This version showed that the gear train not only had the correct 9:1 ratio, but also moved continuously under powered input.

### Presentation Poster

<img src="MEE342-Poster.jpeg" width="500">

---

## 1. Fabrication Details

For Phase 3, the original design was modified so it could be manufactured as a 3D printed prototype. The goal of the prototype was to demonstrate the main gear reduction function of the design at a reduced scale and under safe operating conditions.

The first prototype iteration was a manual gear train demonstration. It included the printed gear train, a hand-crank input, and a single output wheel. This version was used to verify the expected 9:1 gear ratio by counting the number of input rotations required to produce one full output rotation.

The second prototype iteration used the same gear dimensions, but it was improved into a working motorized model. A motor was added to drive the input shaft, and a turning dial was added to the output side so the reduced output speed could be observed continuously.

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
- A turning dial was added to the output side of the second prototype iteration so the output motion and reduced speed could be observed clearly.
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

The addition of the motor and output dial in the second iteration improved the final prototype by allowing the gear train to be operated continuously and by making the output rotation easier to observe.

---

## 2. Assembly Procedure and Challenges

After printing, the prototype was assembled manually. The assembly process focused on placing the gears and shafts into the housing, preventing the shafts from sliding out during operation, and adding a visible output marker for testing. The second iteration also included a motor connected to the input side and a turning dial connected to the output side.

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
10. A turning dial was added to the output side to show the reduced output speed.
11. The model was assembled using superglue on printed components.
12. The motorized version was operated to demonstrate continuous gear train motion and output speed reduction.

### Assembly Results

The assembly process was successful, and the prototype worked immediately after assembly. The first iteration demonstrated the gear train manually using a hand crank and a single output wheel. This confirmed that the printed gear train produced the expected 9:1 ratio.

The second iteration kept the same gear dimensions but added a motor-driven input and output dial. This created a working powered prototype that moved continuously and made the reduced output speed easier to see during operation.

No major issues were observed with slippage or hole clearances, and no parts required reprinting.

### Assembly Challenges

No major assembly failures occurred. The main assembly limitation was that the prototype used simplified printed features instead of final mechanical components. In particular, the housing used clearance holes instead of bearings, and the gear and shaft connections did not use keyways.

The motorized version improved the demonstration, but it also made the limitations of the printed prototype more important. Under motorized operation, alignment, shaft support, adhesive strength, and gear lash matter more than they do during slow manual testing.

---

## 3. Test Procedures, Results, and Interpretation

The prototype was tested in two stages. The first iteration was tested manually using a hand-crank input and a single output wheel to confirm the gear ratio. The second iteration was tested as a motorized working model using the same gear dimensions, with the motor driving the input shaft and the output dial showing the reduced output speed.

### Gear Ratio Test

The gear ratio was tested using the first prototype iteration. A single wheel was attached to the output shaft, and the input shaft was rotated by hand using the hand crank.

The output wheel completed one full rotation after the input shaft was rotated nine times. This verified the expected 9:1 gear reduction.

### Smooth Rotation Test

The input shaft was rotated manually during normal operation. The gears and shafts rotated smoothly without binding.

This showed that the printed clearances and assembly alignment were acceptable for low-speed manual operation.

### Motorized Operation Test

The second prototype iteration used the same gear dimensions as the first version, but the input shaft was driven by a motor. The output side included a turning dial so the reduced output speed could be observed clearly.

This test showed that the gear train did not only work as a manual demonstration. It also moved continuously under powered input, which made the relationship between input speed and output speed easier to observe.

### Lubrication Check

The prototype was operated without additional lubrication. All parts rotated smoothly under normal operation.

This showed that lubrication was not required for the low-speed testing performed on the prototype. However, lubrication or bearings would improve durability for higher-speed or longer-duration motorized testing.

### Backlash Observation

A small amount of play was observed from gear lash between the input shaft and intermediate shaft. The backlash was approximately 3 degrees.

This backlash was likely caused by the printed gear tooth clearances, material flexibility, and simplified shaft support. Although the backlash did not prevent operation, it showed that the 3D printed prototype was less precise than a machined or fully supported final design.

### Summary of Test Results

| Test | Prototype Iteration | Procedure | Result | Interpretation |
|---|---|---|---|---|
| Gear ratio test | Iteration 1 | Rotate hand-crank input until output wheel completes one full rotation | Output wheel rotated once after 9 input rotations | The expected 9:1 gear reduction was verified |
| Smooth rotation test | Iteration 1 and 2 | Rotate the input and observe gear movement | Prototype rotated smoothly | Printed clearances and alignment were acceptable |
| Motorized operation test | Iteration 2 | Use motor to drive the input shaft and observe output dial | Output dial rotated continuously at reduced speed | The prototype successfully demonstrated powered gear reduction |
| Lubrication check | Iteration 1 and 2 | Operate the prototype without additional lubrication | Parts rotated smoothly without lubrication | Lubrication was not needed for demonstration testing |
| Backlash observation | Iteration 1 and 2 | Observe play between input shaft and intermediate shaft | Approximately 3 degrees of gear lash | Backlash was present due to printed clearances and simplified supports |

---

## 4. Comparison With Phase 2 Predictions

The Phase 3 prototype matched the most important expected behavior from the earlier design. The first iteration achieved the intended 9:1 gear reduction using a hand-crank input and a single output wheel. The second iteration used the same gear dimensions and showed that the gear train could also move continuously under motorized input.

The final motorized prototype improved the comparison with the Phase 2 design because it allowed the mechanism to operate with a powered input instead of only being turned by hand. The output dial showed the reduced output speed clearly, which made the speed reduction easier to verify visually.

The prototype still differed from the more realistic Phase 2 design because several features were simplified for 3D printing. The printed version used PLA, clearance holes instead of bearings, no keyways, and superglue assembly. These decisions made the prototype easier to manufacture and test, while still allowing the core function to be demonstrated.

| Phase 2 Expectation | Phase 3 Prototype Result | Explanation |
|---|---|---|
| Gear train should provide a 9:1 gear reduction | The measured reduction was 9:1 | The first iteration successfully demonstrated the main gear reduction function |
| Mechanism should rotate smoothly | Prototype rotated smoothly by hand and with motor input | Printed clearances were acceptable for demonstration testing |
| Prototype should demonstrate powered input | Second iteration included a motor on the input shaft | The motor made the demonstration more realistic than manual operation alone |
| Output speed should be visibly reduced | Output wheel and output dial showed reduced output speed | The output wheel verified the ratio, and the dial made continuous powered output easy to observe |
| Shaft supports should allow rotation while maintaining alignment | Clearance holes supported the shafts during testing | Clearance holes worked for the prototype, but bearings would be better for realistic speeds |
| Shaft-gear connections should transfer torque | Superglue and simplified fits were sufficient for prototype operation | This worked for the demonstration, but stronger connections would be needed for higher loads |
| Gear mesh should have limited backlash | Approximately 3 degrees of backlash was observed | Backlash likely came from printed tooth clearances and material flexibility |
| Prototype should demonstrate the core mechanical function | Prototype showed visible gear motion and output reduction | Skeletonized housing helped make the function easier to observe |

---

## 5. Failures, Mistakes, and Surprises

The prototype worked successfully on the first assembly and test. No parts required reprinting, and no major failures occurred during assembly, manual testing, or motorized operation. The mechanism rotated smoothly, demonstrated the expected 9:1 gear reduction, and operated with the motorized input.

One positive surprise was that the prototype functioned immediately after assembly. The printed clearances, gear alignment, shaft placement, and overall assembly were accurate enough for the gear train to run without major adjustments. The final motorized version also improved the demonstration by making the output speed reduction easier to observe through the turning dial.

Although the prototype worked well, several design limitations were still identified:

- Approximately 3 degrees of gear lash was observed between the input shaft and intermediate shaft.
- Clearance holes were used instead of bearings, which limited the realism of the shaft support.
- No keyways were used, so the shaft-gear connections were not representative of a final high-load design.
- Superglue was used to assemble the components, which may not be reliable under higher torque or long-term motorized operation.
- PLA was acceptable for a functional demonstration, but it is not ideal for a final gear train operating under higher load.
- The reduced gear face width made the gears easier to print but reduced strength compared with the original design.
- Longer motorized testing would require stronger shaft supports and more durable interfaces.

Overall, the immediate success of the prototype showed that the 3D print modifications, clearances, and assembly approach were effective for demonstrating the core gear reduction function.

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

The Phase 3 prototype successfully demonstrated the main function of the gear train through two prototype iterations. The first iteration used a hand-crank input and a single output wheel to verify the expected 9:1 gear ratio. The second iteration used the same gear dimensions but added a motor-driven input and output turning dial, allowing the gear train to move continuously and show the reduced output speed more clearly.

The prototype worked immediately after assembly, required no reprinted parts, and operated smoothly during both manual and motorized testing. The skeletonized housing made it easier to observe the internal gear motion, while the output wheel and output dial made the speed reduction easier to verify and demonstrate.

The main limitations were caused by simplifications made for 3D printing, including PLA material, clearance holes instead of bearings, no keyways, and superglue assembly. These choices were appropriate for a functional demonstration prototype, but a more realistic second version would need stronger materials, better shaft support, improved gear connections, and additional speed or load testing.
