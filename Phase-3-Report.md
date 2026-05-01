# MEE 342 Phase 3 Report

**Team:** Jay-Lam

**Team Members:** Michael Spiller, Luca Santoni, Adam Ortiz, Siping Ruan, Yeonwoo Kim, Jafet Torres Maldonado

---

## Prototype Iterations

### Prototype Iteration 1

![Prototype Iteration 1](MEE342-Iteration-1.jpeg)

### Prototype Iteration 2

![Prototype Iteration 2](MEE342-Iteration-2.jpeg)

---

## Design Changes for 3D Printing

The model was modified from the original design so it could be 3D printed.

- Diametral pitch changed from 6 teeth/in to 12 teeth/in
- Face width changed from 1.5 in to 0.5 in
- Shaft diameter changed to a uniform 0.5 in diameter
- No keyway was used in the 3D printed prototype
- Clearance holes were used in the housing instead of bearings
- A handle was added to the input shaft so the model could be manually spun
- The housing was skeletonized so the moving parts could be viewed

---

## 3D Print Parameters

| Parameter | Value |
|---|---|
| Printer | Bambu Lab P1S |
| Filament | Elegoo PLA, black |
| Infill | 25% gyroid |
| Wall loops | 2 for gears, 1 for everything else |
| Total filament used | 258 g |

---

## Assembly and Debugging

- The shaft was inserted into the gears.
- Two endcaps were placed on the outside of each shaft to prevent shaft movement during operation.
- A small wheel was placed onto the output shaft for testing and measurements.
- The model was assembled with superglue on all components.
- No issues with slippage or hole clearances were observed.
- No reprints were used for any parts.

---

## Testing

To validate the gear ratio, a small mark was made on the output wheel to measure rotation.

As expected, the output shaft rotated one time when the input shaft was rotated nine times. During regular operation, the prototype rotated smoothly.

- A small marking on the output wheel was used to measure rotations relative to the input shaft.
- Rotating the input shaft until the output shaft completed one full rotation verified the gear reduction of 9:1.
- All parts rotated smoothly without additional lubrication under normal conditions.
- A small amount of play from gear lash was observed between the input shaft and intermediate shaft, approximately 3 degrees.

---

## Reflection

The modified 3D printed version retained the functionality of the real design while making changes to simplify construction and manufacturing.

### Future Improvements for Phase 2 Prototype

- Attach a motor to the input shaft to simulate more realistic shaft speeds.
- Use higher strength adhesive to ensure parts do not fail under additional loading.
- Use machined aluminum gears to create more precise tooth profiles.
- Add real bearings to handle additional shaft speed.
- Use stepped shafts to increase strength under high speeds.
