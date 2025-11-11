\left(t*\cos(0.523)-e^{0.03\left|t\right|}\cdot\sin(0.3t)\sin(0.523)\ +55.185\ ,\ 42+\ t*\sin(0.523)+e^{0.03\left|t\right|}\cdot\sin(0.3t)\cos(0.523)\right)
<img width="1653" height="475" alt="Screenshot 2025-11-11 220925" src="https://github.com/user-attachments/assets/7ee67894-0d0c-42b1-9f85-e54a83af4351" />

# Approach
1. The given problem contains three unknown parameters and only two equations,which makes the system underdetermined.Therefore the parameters cannot be uniquely solved using analytical methods alone.
2. To address this i analyzed the dataset by visual inspection then First plotted the data points to observe the overall curve shape and behavior.
3. The curve generated from the given parametric equations was then plotted separately using initial trial values of the parameters.
4. I used trial-and-error (hit-and-try) fitting approach to adjust the parameter and attempt to overlap the analytical curve with the dataset curve.
5. Through systematic variation of parameters, the individual roles of each parameter were identified:
   - M primarily controls the amplitude modulation of the curve through the exponential term.
   - X shifts the curve horizontally along the x-axis.
   - θ controls the orientation or rotation of the curve in an anticlockwise direction.
6. By adjusting M, X, and θ accordingly, the curve produced by the equation was aligned closely with the curve formed by the data points, providing an approximate parameter estimation despite the lack of direct analytical solvability.

#Code
------>code is given in code.ipynb
