---
tags:
  - Undone
  - Chemistry
  - Quantative_Chemistry
date: 2025-02-10
---
---  
# Enthalpy (H)  
Enthalpy (H) -> A measure of heat energy in a chemical system, measured in kilojoules (kJ)  
- System = the atoms/ions/molecules involved, which have energy stored in their chemical bonds  
  
Enthalphy change ($\Delta$H) -> A change in enthalpy between reactants and products that can be measured and calculated, measured in kJ/mol.  
$$ \Delta H = \text{H(products)} - \text{H(reactants)}$$  
Conservation of energy -> energy cannot be created or destroyed, only transferred.  
  
# Energy profile diagrams  
Exothermic -> energy is transferred from the system to the surroundings, causing the temperature to increase  
```tikz  
\usepackage{tikz}  
\usetikzlibrary{arrows.meta}  
  
\begin{document}  
  
\begin{tikzpicture}[scale=1.2]  
    % Draw the axes  
    \draw[->] (0,0) -- (0,4) node[above] {Energy};  
    \draw[->] (0,0) -- (6,0) node[right] {Reaction Progress};  
  
    % Draw the energy profile  
    \draw[thick] (0,3) -- (2,3) node[midway, above] {Reactants}   
				  -- (2,1)  
                  -- (4,1) node[midway, below] {Products}   
                  -- (6,1);  
  
  
\end{tikzpicture}  
  
\end{document}  
```  
Endothermic -> Energy is transferred from the surroundings to the system, causing the temperature to decrease  
```tikz  
\usepackage{tikz}  
\usetikzlibrary{arrows.meta}  
  
\begin{document}  
  
\begin{tikzpicture}[scale=1.2]  
    % Draw the axes  
    \draw[->] (0,0) -- (0,4) node[above] {Energy};  
    \draw[->] (0,0) -- (6,0) node[right] {Reaction Progress};  
  
	\draw[thick] (0,1) -- (2,1) node[midway,above] {Reactants}  
		-- (2,3)   
		-- (6,3) node[midway,above] {Products};  
  
\end{tikzpicture}  
  
\end{document}  
```  
  
# Activation energy  
Energy is needed to break the bonds in reactants, allowing them to rearrange into products and form new bonds.  
  
Activation energy $(E_A)$ -> The minimum energy needed for a reaction to take place  
  
```tikz  
\usepackage{tikz}  
\usetikzlibrary{arrows.meta}  
  
\begin{document}  
  
\begin{tikzpicture}[scale=1.2]  
    % Draw the axes  
    \draw[->] (0,0) -- (0,4) node[above] {Energy};  
    \draw[->] (0,0) -- (6,0) node[right] {Reaction Progress};  
  
	\draw[thick] (0,1) -- (2,1) node[midway,above] {Reactants}  
		-- (4,3)   
		-- (6,3) node[midway,above] {Products};  
  
\end{tikzpicture}  
  
\end{document}  
```  
  
# Standard enthalphy changes  
Enthalpy changes are measured under a series of standard conditions to make them comparably -> they are given the symbol $\Delta H ^{\ominus}$  
  
## Standard conditions:  
- Pressure: 100 kPa  
- Temperature: 298 K / 25$^\textdegree$C  
- Concentration:  
  
# Enthalpy change of combustion $(\Delta _c H ^ \ominus)$   
The enthalpy change when one mole of a substance reacts completely with oxygen under standard conditions with substances in their standard rate.  
  
# Enthalpy change of neutralisation $(\Delta_\text{neut} H ^ \ominus)$  
$H^+ (aq) + OH^- (aq) \rightarrow H_2O (l) \qquad \Delta_\text{neut}H^\ominus = -57kJ \thinspace mol^{_1}$  
  
# Questions  
1. $C_2H_6O+2O_2\rightarrow 2CO_2 + 3H_2O$  
2. $C_3H_8+5O_2\rightarrow 3CO_2+4H_2O$  
3. $C+2H_2\rightarrow CH_4$  
4. $C+2H_2+\frac{1}{2}O \rightarrow CH_4O$  
5. $\frac{1}{2}H_2SO_4+NaOH \rightarrow \frac{1}{2}Na_2SO_4 +H_2O$  
  
# More questions  
1. The enthalpy change of formation of a compound is when mole of a compound is formed from its elements under standard conditions with substances in their standard states  
  
  
| Reactants                              | Temperature before mixing / $\textdegree$C | Temperature after mixing / $\textdegree$C | Temperature change / $\textdegree$C | Exothermic or endothermic? |  
| -------------------------------------- | ------------------------------------------ | ----------------------------------------- | ----------------------------------- | -------------------------- |  
| Hydrochloric acid and sodium hydroxide | 21                                         | 29                                        | +8                                  | Exothermic                 |  
| Copper sulphate and magnesium powder   | 20                                         | 64                                        | +44                                 | Exothermic                 |  
| Ammonium nitrate and water             | 20                                         | 2                                         | -18                                 | Endothermic                |  
| Hydrochloric acid and magnesium ribbon | 20                                         | 30                                        | +10                                 | Exothermic                 |  
  
  
| Time (s) | Temperature ([[To do/Degrees | degrees]] C) |  
| -------- | ---------------------------- | ------------ |  
| 0        | 21.5                         |              |  
| 30       | 22                           |              |  
| 60       | 22                           |              |  
| 90       | 22                           |              |  
| 120      | 22                           |              |  
| 150      | 22                           |              |  
| 180      | *Add in Zinc*                |              |  
| 210      | 35                           |              |  
| 240      | 55                           |              |  
| 270      | 58                           |              |  
| 300      | 58                           |              |  
| 330      | 56                           |              |  
| 360      | 54.5                         |              |  
| 390      | 53.5                         |              |  
| 420      | 52                           |              |  
| 450      | 51                           |              |  
| 480      | 50                           |              |  
| 510      | 49                           |              |  
| 540      | 48                           |              |  
| 570      | 47                           |              |  
| 600      | 46                           |              |  
Mass of empty weighing boat = 0.96 g  
[[../../To do/Mass|Mass]] of weighing boat with zinc = 3.93 g  
Mass of zinc = 2.97 g  
Mass of weighing boat after experiment = 1.01 g  
Mass of zinc left over = 0.05 g  
Mass of zinc used = 2.92 g  
  
```chartsview  
#-----------------#  
#- chart type    -#  
#-----------------#  
type: Line  
  
#-----------------#  
#- chart data    -#  
#-----------------#  
data:  
  - label: "0"  
    value: 21.5  
  - label: "30"  
    value: 22  
  - label: "60"  
    value: 22  
  - label: "90"  
    value: 22  
  - label: "120"  
    value: 22  
  - label: "150"  
    value: 22  
  - label: "180"  
    value: 22  
  - label: "210"  
    value: 35  
  - label: "240"  
    value: 55  
  - label: "270"  
    value: 58  
  - label: "300"  
    value: 58  
  - label: "330"  
    value: 56  
  - label: "360"  
    value: 54.5  
  - label: "390"  
    value: 53.5  
  - label: "420"  
    value: 52  
  - label: "450"  
    value: 52  
  - label: "480"  
    value: 50  
  - label: "510"  
    value: 49  
  - label: "540"  
    value: 48  
  - label: "570"  
    value: 47  
  - label: "600"  
    value: 46  
  
#-----------------#  
#- chart options -#  
#-----------------#  
options:  
  xField: label  
  yField: value  
```  
  
# Prep  
### Enthalpy Questions 1  
  
1. **Calculate the amount of heat energy needed to increase the temperature of 150g of water from 20℃ to 35℃.**  
  
   **Answer:**  
   - **Formula**: $q = mc\Delta T$  
   - $m = 150 \, \text{g}$  
   - $c = 4.18 \, \text{J/g℃}$  
   - $\Delta T = 35℃ - 20℃ = 15℃$  
   - $q = 150 \, \text{g} \times 4.18 \, \text{J/g℃} \times 15℃ = 9405 \, \text{J}$  
   - $q \approx 9.41 \, \text{kJ}$  
  
2. **The combustion of 0.15g of ethanol, CH₃CH₂OH, in a spirit burner increased the temperature of 75ml of water by 12.5℃. Calculate the enthalpy of combustion of ethanol in kJ mol⁻¹.**  
  
   **Answer:**  
   - **Formula**: $q = mc\Delta T$  
   - $m = 75 \, \text{g}$  
   - $c = 4.18 \, \text{J/g℃}$  
   - $\Delta T = 12.5℃$  
   - $q = 75 \, \text{g} \times 4.18 \, \text{J/g℃} \times 12.5℃ = 3918.75 \, \text{J}$  
   - Molar mass of ethanol = 46 g/mol  
   - Moles of ethanol = $\frac{0.15 \, \text{g}}{46.07 \, \text{g/mol}} \approx 0.00326 \, \text{mol}$  
   - Enthalpy of combustion = $\frac{3918.75 \, \text{J}}{0.00326 \, \text{mol}} \approx -1202 \, \text{kJ/mol}$  
  
3. **A student completed a practical to determine the enthalpy of combustion of methanol, CH₃OH. The results were as follows:**  
   - **Initial mass of spirit burner and methanol**: 52.76g  
   - **Final mass of spirit burner and methanol**: 52.45g  
   - **Volume of water in beaker**: 100ml  
   - **Initial temperature of water**: 21.0℃   
   - **Final temperature of water**: 36.5℃  
  
   **a) Calculate the energy released by the methanol.**  
  
   **Answer:**  
   - **Formula**: $q = mc\Delta T$  
   - $m = 100 \, \text{g}$  
   - $c = 4.18 \, \text{J/g℃}$  
   - $\Delta T = 36.5℃ - 21.0℃ = 15.5℃$  
   - $q = 100 \, \text{g} \times 4.18 \, \text{J/g℃} \times 15.5℃ = 6479 \, \text{J}$  
   - $q \approx 6.48 \, \text{kJ}$  
  
   **b) Calculate the enthalpy of combustion of methanol in kJ mol⁻¹.**  
  
   **Answer:**  
   - Mass of methanol burnt = 52.76g - 52.45g = 0.31g  
   - Molar mass of methanol = 32.04 g/mol  
   - Moles of methanol = $\frac{0.31 \, \text{g}}{32.04 \, \text{g/mol}} \approx 0.00968 \, \text{mol}$  
   - Enthalpy of combustion = $\frac{6.48 \, \text{kJ}}{0.00968 \, \text{mol}} \approx -669 \, \text{kJ/mol}$  
  
4. **A student was asked to determine the enthalpy change of neutralisation:**  
   **HCl (aq) + NaOH (aq) → NaCl (aq) + H₂O (l)**  
   - The student placed 50ml of 1 mol dm⁻³ hydrochloric acid in a polystyrene cup and recorded the temperature. 50ml of sodium hydroxide at the same temperature was then added and the mixture stirred. The maximum temperature rise was 6.75℃. The sodium hydroxide used was in excess to ensure all the hydrochloric acid had reacted.  
  
   **Calculate the enthalpy of neutralisation.**  
  
   **Answer:**  
   - **Formula**: $q = mc\Delta T$  
   - Total volume = 50ml + 50ml = 100ml  
   - $m = 100 \, \text{g}$  
   - $c = 4.18 \, \text{J/g℃}$  
   - $\Delta T = 6.75℃$  
   - $q = 100 \, \text{g} \times 4.18 \, \text{J/g℃} \times 6.75℃ = 2821.5 \, \text{J}$  
   - Moles of HCl = 0.05 mol (since 50ml of 1 mol dm⁻³ HCl)  
   - Enthalpy of neutralisation = $\frac{2821.5 \, \text{J}}{0.05 \, \text{mol}} = 56430 \, \text{J/mol}$  
   - $\Delta H_{\text{neut}} \approx -56.43 \, \text{kJ/mol}$  
  
5. **In an experiment to find the enthalpy of neutralisation of a weak acid, HX, 30ml of a 1 mol dm⁻³ solution of HX was mixed with 40ml of 1 mol dm⁻³ potassium hydroxide in a polystyrene cup. The temperature rise in the reaction was 5.0℃.**  
  
   **Calculate the enthalpy of neutralisation for the weak acid.**  
  
   **Answer:**  
   - **Formula**: $q = mc\Delta T$  
   - Total volume = 30ml + 40ml = 70ml  
   - $m = 70 \, \text{g}$  
   - $c = 4.18 \, \text{J/g℃}$  
   - $\Delta T = 5.0℃$  
   - $q = 70 \, \text{g} \times 4.18 \, \text{J/g℃} \times 5.0℃ = 1463 \, \text{J}$  
   - Moles of HX = 0.03 mol (since 30ml of 1 mol dm⁻³ HX)  
   - Enthalpy of neutralisation = $\frac{1463 \, \text{J}}{0.03 \, \text{mol}} = 48766.67 \, \text{J/mol}$  
   - $\Delta H_{\text{neut}} \approx -48.77 \, \text{kJ/mol}$  
  
6. **A student added 3.41g of sodium carbonate to 40ml of dilute hydrochloric acid (in excess). The temperature of the acid rose by 7.3℃. Calculate the enthalpy change in kJ mol⁻¹ for the reaction.**  
  
   **Answer:**  
   - **Formula**: $q = mc\Delta T$)  
   - $m = 40 \, \text{g}$  
   - $c = 4.18 \, \text{J/g℃}$  
   - $\Delta T = 7.3℃$  
   - $q = 40 \, \text{g} \times 4.18 \, \text{J/g℃} \times 7.3℃ = 1220.72 \, \text{J}$  
   - Molar mass of sodium carbonate $(\text{Na}_2\text{CO}_3$) = 106 g/mol  
   - Moles of $\text{Na}_2\text{CO}_3$ = $\frac{3.41 \, \text{g}}{106 \, \text{g/mol}} \approx 0.03217 \, \text{mol}$  
   - Enthalpy change = $\frac{1220.72 \, \text{J}}{0.03217 \, \text{mol}} \approx 37939.03 \, \text{J/mol}$  
   - $\Delta H_{\text{reaction}} \approx -37.94 \, \text{kJ/mol}$  
  
### Enthalpy Calculations 2  
  
1. **When 0.4g of calcium reacts with 100ml (excess) dilute hydrochloric acid, a temperature rise of 12ºC occurs. The equation for the reaction is:**  
   **Ca (s) + 2HCl (aq) → CaCl₂ (aq) + H₂ (g)**  
   - **(a) Is the reaction exothermic or endothermic?**  
     - **Answer**: The reaction is exothermic.  
   - **(b) How many moles of calcium were used?**  
     - **Answer**: Molar mass of Ca = 40.08 g/mol  
     - Moles of Ca = $\frac{0.4 \, \text{g}}{40.08 \, \text{g/mol}} \approx 0.00998 \, \text{mol}$  
   - **(c) How much energy is released during the reaction?**  
     - **Answer**: $q = mc\Delta T$  
     - $m = 100 \, \text{g}$  
     - $c = 4.18 \, \text{J/g℃}$  
     - $\Delta T = 12℃$  
     - $q = 100 \, \text{g} \times 4.18 \, \text{J/g℃} \times 12℃ = 5016 \, \text{J}$  
     - $q \approx 5.02 \, \text{kJ}$  
   - **(d) Calculate the enthalpy change for the reaction.**  
     - **Answer**: $\Delta H = \frac{q}{\text{moles of Ca}} = \frac{5016 \, \text{J}}{0.00998 \, \text{mol}} \approx -503 \, \text{kJ/mol}$  
  
2. **When 1.3g of zinc reacts with 100ml of 2.0mol dm⁻³ nitric acid, a temperature rise of 6℃ occurs. The equation for the reaction is:**  
   **Zn (s) + 2HNO₃ (aq) → Zn(NO₃)₂ (aq) + H₂ (g)**  
   - **(a) Is the reaction exothermic or endothermic?**  
     - **Answer**: The reaction is exothermic.  
   - **(b) How many moles of zinc are used?**  
     - **Answer**: Molar mass of Zn = 65.38 g/mol  
     - Moles of Zn = $\frac{1.3 \, \text{g}}{65.38 \, \text{g/mol}} \approx 0.01988 \, \text{mol}$  
   - **(c) How many moles of nitric acid are used?**  
     - **Answer**: Molarity = 2.0 mol/L  
     - Volume = 100 ml = 0.1 L  
     - Moles of HNO₃ = Molarity × Volume = 2.0 mol/L × 0.1 L = 0.2 mol  
   - **(d) Which reagent is not in excess?**  
     - **Answer**: Zinc is not in excess.  
   - **(e) How much energy is released during the reaction?**  
     - **Answer**: $q = mc\Delta T$  
     - $m = 100 \, \text{g}$  
     - $c = 4.18 \, \text{J/g℃}$  
     - $\Delta T = 6℃$  
     - $q = 100 \, \text{g} \times 4.18 \, \text{J/g℃} \times 6℃ = 2508 \, \text{J}$  
     - $q \approx 2.51 \, \text{kJ}$  
   - **(f) Calculate the enthalpy change for the reaction.**  
     - **Answer**: $\Delta H = \frac{q}{\text{moles of Zn}} = \frac{2508 \, \text{J}}{0.01988 \, \text{mol}} \approx -126.17 \, \text{kJ/mol}$  
  
3. **When 0.046g of sodium reacts with 50ml of water, the temperature of the water rises by 1.5ºC. How much energy is released when one mole of sodium reacts with water?**  
   - **Answer**: $q = mc\Delta T$  
   - $m = 50 \, \text{g}$  
   - $c = 4.18 \, \text{J/g℃}$  
   - $\Delta T = 1.5℃$  
   - $q = 50 \, \text{g} \times 4.18 \, \text{J/g℃} \times 1.5℃ = 313.5 \, \text{J}$  
   - Molar mass of Na = 22.99 g/mol  
   - Moles of Na = $\frac{0.046 \, \text{g}}{22.99 \, \text{g/mol}} \approx 0.002 \, \text{mol}$  
   - Energy released per mole of Na = $\frac{313.5 \, \text{J}}{0.002 \, \text{mol}} = 156750 \, \text{J/mol}$  
   - $\approx -158 \, \text{kJ/mol}$  
  
4. **When 4g of ammonium nitrate, NH₄NO₃, dissolves in 100ml of water, the temperature falls by 4ºC.**  
   - **(a) How many moles of ammonium nitrate are dissolved?**  
     - **Answer**: Molar mass of NH₄NO₃ = 80.04 g/mol  
     - Moles of NH₄NO₃ = $\frac{4 \, \text{g}}{80.04 \, \text{g/mol}} \approx 0.05 \, \text{mol}$  
   - **(b) How much energy is absorbed from the water when the ammonium nitrate dissolves?**  
     - **Answer**: $q = mc\Delta T$  
     - $m = 100 \, \text{g}$  
     - $c = 4.18 \, \text{J/g℃}$  
     - $\Delta T = 4℃$  
     - $q = 100 \, \text{g} \times 4.18 \, \text{J/g℃} \times 4℃ = 1672 \, \text{J}$  
     - $q \approx 7 \, \text{kJ}$  
   - **(c) Calculate the enthalpy change of reaction.**  
     - **Answer**: $\Delta H = \frac{q}{\text{moles of NH₄NO₃}} = \frac{1672 \, \text{J}}{0.05 \, \text{mol}} \approx 33.44 \, \text{kJ/mol}$  
  
5. **When 10.7g of ammonium chloride, NH₄Cl, dissolves in 200g of water, the temperature falls by 4℃.**  
   - **(a) How many moles of ammonium chloride are dissolved?**  
     - **Answer**: Molar mass of NH₄Cl = 53.49 g/mol  
     - Moles of NH₄Cl = $\frac{10.7 \, \text{g}}{53.49 \, \text{g/mol}} \approx 0.2 \, \text{mol}$  
   - **(b) How much energy is absorbed from the water when the ammonium chloride dissolves?**  
     - **Answer**: $q = mc\Delta T$  
     - $m = 200 \, \text{g}$  
     - $c = 4.18 \, \text{J/g℃}$  
     - $\Delta T = 4℃$  
     - $q = 200 \, \text{g} \times 4.18 \, \text{J/g℃} \times 4℃ = 3344 \, \text{J}$  
     - $q \approx 3.34 \, \text{kJ}$  
   - **(c) Calculate the enthalpy change for the reaction.**  
     - **Answer**: $\Delta H = \frac{q}{\text{moles of NH₄Cl}} = \frac{3344 \, \text{J}}{0.2 \, \text{mol}} \approx 16.72 \, \text{kJ/mol}$  
  
## More questions  
  
![](https://web-api.textin.com/ocr_image/external/ebc7438d0fe73621.jpg)  
  
## 1) What is enthalpy?   
  
What is enthalpy? It is a measure of the heat content of a substance  
  
Enthalpy change (∆H) = Change in heat content at constant pressure   
  
Standard conditions $(\Delta H^{\circ })=100kPa$ and a stated temperature (usually 298K)  
  
## 2) Reaction profiles   
  
Exothermic reactions Endothermic reactions   
  
  
![](https://web-api.textin.com/ocr_image/external/ab01e81e5e591a98.jpg)  
  
  
![](https://web-api.textin.com/ocr_image/external/0576b28417409fae.jpg)  
  
# 3) Standard enthalpy change of reaction (∆rH°) (“enthalpy of reaction”)   
  
This is the enthalpy change for a reaction with the quantities shown in the chemical equation. This means that the value should always be quoted along with the equation  
  
In this example, the second equation contains half the molar quantities e entistiof the first and so the ∆rH° value is half as much. The value of –114.2 kJ mol-1 in the first equation means that 114.2kJ of heat energy is released when 1 mole of H2SO4 reacts with 2 moles of NaOH. The value of –57.1 kJ mol-1 in the second equation means that 57.1 kJ of heat energy is released when ½mole of H2SO4 reacts with 1 mole of NaOH. em NH   
  
e.g.  $H_{2}SO_{4}(aq)+2NaOH(aq)\rightarrow Na_{2}SO_{4}(aq)+2H_{2}O(l)$ $\Delta _{f}H^{\circ }=-114.2kJmol^{-1}$  
  
$\%H_{2}SO_{4}(aq)+NaOH(aq)\rightarrow \%Na_{2}SO_{4}(aq)+H_{2}O(l)$ $\Delta _{f}H^{\circ }=-57.1kJmol^{-1}$  
  
# 4) Standard enthalpy change of formation (∆fH°) (“enthalpy of formation”)   
  
Enthalpy change when 1 mole of a substance is formed from its constituent elements with all reactants and products in standard states under standard conditions.   
  
e.g. $CH_4(g)$ - $C(s)+2H_2(g) \rightarrow CH_4(g)$  
  
$H_{2}O(l)$ - $H_2(g)+\frac{1}{2}O_2 \rightarrow H_2O(l)$  
  
$NH_3(g)$ - $\frac{1}{2}N_2(g)+\frac{3}{2}H_2(g) \rightarrow NH_3(g)$  
  
$C_{2}H_{5}OH(l)$ - $2C(s)+3H_2(g)+\frac{1}{2}O_2(g) \rightarrow C_2H_5OH(l)$  
  
$CH_3Br(l)$ - $C(s)+\frac{3}{2}H_2(g)+\frac{1}{2}Br_2(l) \rightarrow CH_3Br(l)$  
  
$Na_{2}O(s)$ - $2Na(s)+\frac{1}{2}O_2(g) \rightarrow Na_2O(s)$  
  
Note: re ∆fH° of an element in its standard state=0 by definition  
  
## 5) Standard enthalpy change of combustion (∆cH°) (“enthalpy of combustion”)  
  
Enthalpy change when 1 mole of a substance is completely burned in oxygen with all reactants and products in standard states under standard conditions.   
  
e.g.  $CH_4(g)$  
  
$H_2(g)$  
  
$C_{2}H_{6}(g)$  
  
$C_2H_5OH(l)$  
  
$Na(s)$  
  
$C_{6}H_{14}(l)$  
  
## 6) Standard enthalpy change of neutralisation ($∆_{neut}H°$) (“enthalpy of neutralisation”)   
  
Enthalpy change when 1 mole of water is formed in a reaction between an acid and alkali under standard conditions.  
  
e.g.  $HCl(aq)+NaOH(aq)$  
  
$H_{2}SO_{4}(aq)+NaOH(aq)$  
  
$HNO_{3}(aq)+KOH(aq)$  
  
$HNO_{3}(aq)+Ba(OH)_{2}(aq)$  
  
$H_{2}SO_{4}(aq)+Ba(OH)_{2}(aq)$  
  
<!-- ©  -->  
![](https://web-api.textin.com/ocr_image/external/d8dd1e9f37ccfde1.jpg)  
  
  
  
# Bond enthalpies  
## Friday, February 28th 2025  
  
### <u>Average bond enthalpy</u>  
- The enerfy needed to break one mole of a specified bond in a gaseous molecule  
- Bond breaking requires energy (endo), so values are always positive  
- Values are given as an average as the actual bond enthalpy will vary depending on the chemical environment  
  
### <u>Making and breaking bonds</u>  
In a chemical reaction, bonds between atoms need to be broken (reactants) so the atom can rearrange and form new bonds  
- Breaking bonds <u>requires</u> energy (endo, + values)  
- Making bonds <u>releases</u> energy (exo, -values)  
Bond enthalpy values are the same but opposite for making/breaking bonds (same number, different sign)  
  
### <u>Overall enthalpy change</u>  
The difference between the bond breaking and bond making values determines os a reaction is overall endothermic or exothermic  
$$ \Delta _r H = \sum (\text{bond enthalpies in reactants}) - \sum (\text{bond enthalpies in products})$$  
Breaking in reactants > making in products  
- <span style="color: #ADD8E6;">More energy is absorbed than released (endo, +ΔH)</span>  
- <span style="color: #FFCCCB;">More energy is released than absorbed (exo, -ΔH)</span>  
  
1. $2H_2 + O_2 \rightarrow 2H_2O$  
$2(H-H) + O=O \rightarrow 2(H-O-H)$  
$2 \times 436 + 1 \times 497 \rightarrow 4 \times 463$  
$(1369-1852) \div 2=-241.5 KJ\thinspace mol^{-1} \therefore \text{exothermic}$  
2. $C_2H_4+H_2O \rightarrow C_2H_5OH$  
$4(C-H)+(C=C)+2(O-H) \rightarrow 5(C-H)+(C-C)+(C-O)+(O-H)$  
$4 \times 413 + 612 + 2 \times 463 \rightarrow 5 \times 413 + 347 + 463$  
$3190-2875=315\thinspace KJ \thinspace mol ^{-1} \therefore \text{endothermic}$  
3. $2C+3H_2 \rightarrow C_2H_6$  
$3 \times 436 \rightarrow 6 \times 413 + 347$  
$1308-2825=-1517 KJ\thinspace mol^{-1} \therefore \text{exothermic}$  
4. $N_2+3H_2 \rightarrow 2NH_3$  
$(N\equiv N)+3(H-H)\rightarrow 6(N-H)$  
$945 + 3 \times 436 \rightarrow 6 \times 391$  
$(2253-2346) \div 2 = -46.5 \thinspace KJ \thinspace mol ^{-1} \therefore \text{exothermic}$  
  
  
### <u>Questions</u>  
1. $108\thinspace KJ \thinspace mol ^{-1}$  
2. $-549\thinspace KJ \thinspace mol ^{-1}$  
3. $0 \thinspace KJ \thinspace mol ^{-1}$  
4. $-489 \thinspace KJ \thinspace mol ^{-1}$  
5. $-808 \thinspace KJ \thinspace mol ^{-1}$  
  
6. Definition of enthalpy  
7. -42  
8. B  
9. 198  
10. -740  
11. 298  
12. 612  
13. 1370  
14. A  
15. 431.5  
16. 