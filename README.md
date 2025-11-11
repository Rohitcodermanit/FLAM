\left(t*\cos(0.523)-e^{0.0298\left|t\right|}\cdot\sin(0.3t)\sin(0.523)\ +55.175\ ,\ 42+\ t*\sin(0.523)+e^{0.0298\left|t\right|}\cdot\sin(0.3t)\cos(0.523)\right)
<img width="1663" height="401" alt="Screenshot 2025-11-11 191305" src="https://github.com/user-attachments/assets/9c4ed1a0-f2c1-40d1-a29d-f5a82ec7aefc" />

# Approach
1. The given problem contains three unknown parameters and only two equations,which makes the system underdetermined.Therefore the parameters cannot be uniquely solved using analytical methods alone.
2. To address this the dataset was analyzed by visual inspection. First the data points were plotted to observe the overall curve shape and behavior.
3. The curve generated from the given parametric equations was then plotted separately using initial trial values of the parameters.
4. A trial-and-error (hit-and-try) fitting approach was used to adjust the parameter and attempt to overlap the analytical curve with the dataset curve.
5. Through systematic variation of parameters, the individual roles of each parameter were identified:
   - M primarily controls the amplitude modulation of the curve through the exponential term.
   - X shifts the curve horizontally along the x-axis.
   - θ controls the orientation or rotation of the curve in an anticlockwise direction.
6. By adjusting M, X, and θ accordingly, the curve produced by the equation was aligned closely with the curve formed by the data points, providing an approximate parameter estimation despite the lack of direct analytical solvability.

#Code
------>code is given in code.ipynb
