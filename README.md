# Wall Shear Stress (WSS) Analysis Using ParaView & Excel

This mini-project demonstrates a complete workflow for extracting wall shear stress (WSS) and related hemodynamic parameters from a stenosed vessel simulation using ParaView and Excel.

The goal was to:
- extract surface gradients  
- compute WSS = √(GradientX² + GradientY² + GradientZ²)  
- visualise pressure and velocity fields  
- generate the final WSS plot across the vessel wall  

---

## Tools Used
- ParaView - post-processing, gradient extraction, data export  
- Excel - WSS computation and line-plot generation  
- OpenFOAM dataset (3D stenosed artery geometry)

---

## Outputs Included in This Repository

### 1. Velocity Magnitude Field  
File: `velocity.png`  
Shows flow acceleration in the stenosed region.

### 2. Pressure Field  
File: `pressure.png`  
Shows pressure drop across the narrowing.

### 3. Wall Shear Stress Gradient  
File: `WSS_gradient.png`  
Surface distribution of WSS magnitude.

### 4. WSS Line Plot (Excel)  
File: `WSS_Data.csv`  
Contains gradient components + computed WSS values.

### 5. Flow Animation  
File: `stenosis_flow.mp4`  
CFD animation exported from ParaView.

---

## WSS Formula
WSS = sqrt( GradientX^2 + GradientY^2 + GradientZ^2 )


---

## Purpose of This Project
To demonstrate:
- CFD post-processing skills  
- extraction of biomechanical metrics  
- ParaView visualisation  
- custom scientific computation  
- biomedical engineering + imaging workflow

---

## Author
Jeevitha  
Biomedical Engineering  
CFD | Medical Imaging | ParaView | Research Workflows

WSS was computed using:

