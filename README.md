# EVALUATION-OF-RADAR-RANGE-USING-SCILAB
## Aim
To calculate the maximum range of a radar system using the Radar Range Equation and verify the results through Scilab programming.

## Apparatus Required
1. **Software:** Scilab environment
2. **Hardware:** Personal Computer

---

## Theory
The Radar Range Equation is a fundamental formula used in radar system design to determine the maximum range at which a radar can detect a target. 

### Mathematical Representation
The maximum radar range $R_{\max}$ is given by:

$$R_{\max} = \left( \frac{P_t G_t G_r \lambda^2 \sigma}{(4\pi)^3 P_{\min}} \right)^{\frac{1}{4}}$$

Where:
* $R_{\max}$ : Maximum detectable range of the radar (m)
* $P_t$ : Transmitted power (W)
* $G_t$ : Gain of the transmitting antenna
* $G_r$ : Gain of the receiving antenna
* $\lambda$ : Wavelength of the radar signal (m), calculated as $\lambda = \frac{c}{f}$ (where $c = 3 \times 10^8 \text{ m/s}$)
* $\sigma$ : Radar cross-section of the target ($\text{m}^2$)
* $P_{\min}$ : Minimum detectable signal power of the receiver (W)

---

## Procedure / Algorithm
1. **Set Up the Scilab Environment:** Launch the Scilab workspace/console.
2. **Define Parameters:** Set values for transmitted power ($P_t$), antenna gains ($G_t, G_r$), frequency ($f$), radar cross section ($\sigma$), and minimum power ($P_{\min}$).
3. **Calculate Wavelength:** Convert signal frequency to wavelength using $\lambda = \frac{c}{f}$, where $c = 3 \times 10^8 \text{ m/s}$.
4. **Define Radar Range Equation:** Compute the numerator and denominator using Scilab's built-in math functions and `%pi`.
5. **Calculate Maximum Range:** Evaluate $R_{\max}$ by raising the ratio to the power of $0.25$ (1/4th power).
6. **Execute and Display Results:** Run the Scilab script (`.sce`) to display the maximum radar range in meters and kilometers.

---

## Tabulation

<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/c3d393bd-5371-416b-803d-fa1004b6d9eb" />


## Output
<img width="1917" height="1020" alt="image" src="https://github.com/user-attachments/assets/c1f64fac-7f13-4060-9ff8-e265a78a814b" />


## Result
Thus, the maximum range of radar system using radar range equation is verified.


