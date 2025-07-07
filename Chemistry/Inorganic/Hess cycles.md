---
tags:
  - Undone
  - Chemistry
date: 2025-03-03
---
---  
##  <u>Hess' law</u>  
→ The [[./Enthalpy|enthalpy]] change in a chemical reaction is independent of the route it takes  
- used when we cannot measure the [[./Enthalpy|enthalpy]] change directly using calorimetry, and instead use values from other known reactions  
- [[./Enthalpy|Enthalpy]] cycle — shows alternative routes between reactants and products  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\node at (0,0) {X};  
\node at (6,0) {Y};  
\node at (3,-2) {Z};  
\draw[line width = 1pt, -latex] (0.25,0) -- (5.75,0);  
\draw[line width = 1pt, -latex] (0.25,-0.25) -- (2.75,-2);  
\draw[line width = 1pt, latex-] (3.25,-2) -- (5.75,-0.25);  
  
\end{tikzpicture}  
\end{document}  
```  
## Combustion  
Example:$$C_{(s)}+2H_{2(g)} \rightarrow CH_{4(g)}$$  
Methane cannot be made from its elements under standard conditions, however, we can combust all the substances to produce $CO_2$ and $H_2O$  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\node at (0,0) {$C_{(s)}+2H_{2(g)}$};  
\node at (6,0) {$CH_{4(g)}$};  
\node at (3,-2) {$CO_{2(g)},H_2O_{(l)}$};  
\draw[line width = 1pt, -latex] (1.1,0) -- (5.3,0) node[midway,above] {?};  
\draw[line width = 1pt, -latex] (0.25,-0.25) -- (2.25,-1.75) node[left,midway] {-966};  
\draw[line width = 1pt, latex-] (3.75,-1.75) -- (5.75,-0.25) node[right,midway] {-890};  
  
\end{tikzpicture}  
\end{document}  
```  
$$\Delta _r H^{\degree} = \sum \Delta _c reactants - \sum \Delta _c products$$  
Example 2:  
Calculate the [[./Enthalpy|enthalpy]] of combustion of propane, C$_3$H$_8$(g), given the following [[./Enthalpy|enthalpy]] changes $\Delta _c H$ : C(s) –393; H₂(g) –286 kJ mol$^{-1}$, $\Delta _f H$ : C$_3$H$_8$(l) –103 kJ mol$^{-1}$  
$4 \times -286 + 3 \times -393 = -2323$  
$-103$  
$-2323 - ? = -103$  
$?=2220 \thinspace kJ \thinspace mol^{-1}$  
  
Calculate the [[./Enthalpy|enthalpy]] change for this reaction given the following data: $C(s) + 2 H2(g) \rightarrow CH_{4(g)}$   
$\Delta _cH : C_{(s)} = –393, \space H_{2(g)} = –286, \space CH_{4(g)} = –890\thinspace kJ \thinspace mol{–1}$  
$-393+-286 \times 2 - -890 = -75\thinspace kJ \thinspace mol{–1}$  
  
Calculate the [[./Enthalpy|enthalpy]] change for the following reaction using the enthalpies of combustion given. $C(graphite) \rightarrow C(diamond)$  
$\Delta _cH : C(graphite) –393, \space C(diamond) –395 \thinspace kJ \thinspace mol{-1}$  
$-393--395= +2 \thinspace kJ \thinspace mol{–1}$  
  
Calculate the [[./Enthalpy|enthalpy]] change during the fermentation of glucose using the enthalpies of combustion given. $C_6H_{12}O_{6(s)} \rightarrow 2 C_2H_5OH_{(l)} + 2 CO_{2(g)}$  
$\Delta _cH : C_6H_{12}O_{6(s)} –2820, \space C_2H_5OH_{(l)} –1368 \thinspace kJ \thinspace mol{-1}$  
$-2820--2736=-84\thinspace kJ \thinspace mol{-1}$  
  
## Formation  
```tikz  
\begin{document}  
\begin{tikzpicture}  
  
\node at (0,0) {X};  
\node at (6,0) {Y};  
\node at (3,-2) {Z};  
\draw[line width = 1pt, -latex] (0.25,0) -- (5.75,0) node[above,midway] {A};  
\draw[line width = 1pt, latex-] (0.25,-0.25) -- (2.75,-2) node[midway,left] {B};  
\draw[line width = 1pt, -latex] (3.25,-2) -- (5.75,-0.25) node[midway,right] {C};  
  
\end{tikzpicture}  
\end{document}  
```  
$A=-B+C$  
  
Example  
$CaO_{_{(s)}}+H_2O_{_{(l)}} \rightarrow Ca(OH)_{2_{(s)}}$  
  
| Substance                                             | $CaO_{_{(s)}}$ | $H_2O_{_{(l)}}$ | $Ca(OH)_{2_{(s)}}$ |  
| ----------------------------------------------------- | -------------- | --------------- | ------------------ |  
| $\Delta _f H{\degree} \space (kJ\thinspace mol^{-1})$ | -635           | -286            | -986               |  
|                                                       |                |                 |                    |  
$-(-635+-286)+(-986)=-65 \thinspace kJ\thinspace mol^{-1}$  
  
Calculate the $\Delta H$ for the following reactions given the values of $\Delta _fH$ in the following table.  
  
|                             | $ZnCO_3(s)$ | $ZnO(s)$ | $CO_2(g)$ | $CO(g)$ | $H_2O(l)$ | $Fe_2O_3(s)$ | $Al_2O_3(s)$ | $C_2H_4(g)$ |     |     |  
| --------------------------- | ----------- | -------- | --------- | ------- | --------- | ------------ | ------------ | ----------- | --- | --- |  
| $\Delta _fH \space(kJ/mol)$ | –812        | –348     | –393      | –111    | –286      | –822         | –1669        | +52         |     |     |  
  
$ZnCO_3(s) \rightarrow ZnO(s) + CO_2(g)$  
$-(-812)+(-348+-393)=+71 \thinspace kJ\thinspace mol^{-1}$  
  
$2 CO(g) + O_2(g) \rightarrow 2 CO_2(g)$  
$-(-111+0)+(2 \times -393)=-675\thinspace kJ\thinspace mol^{-1}$  
  
$2 Al(s) + Fe_2O_3(s) \rightarrow 2 Fe(s) + Al_2O_3(s)$  
$-(0+-822)+(0+-1669)=-847 \thinspace kJ\thinspace mol^{-1}$  
  
$C_2H_4(g) + 3 O_2(g) \rightarrow 2 CO_2(g) + 2 H_2O(l)$  
$-(52+0)+(-393)=-445 \thinspace kJ\thinspace mol^{-1}$  
  
$C_2H_4(g) + 2 O_2(g) \rightarrow 2 CO(g) + 2 H_2O(l)$  
$-(-393)+(2 \times -111 + 2 \times -286) = -1187\thinspace kJ\thinspace mol^{-1}$  
  
The table below shows standard [[./Enthalpy|enthalpy]] changes of formation, $Δ_fH$.  
  
| Compound              | $NH_4NO_3(s)$ | $H_2O(g)$ | $CO_2(g)$ |  
| --------------------- | ------------- | --------- | --------- |  
| $Δ_fH ( kJ mol^{−1})$ | −366          | −242      | −394      |  
  
What is the [[./Enthalpy|enthalpy]] change for the following reaction?  
  
$2NH_4NO_3(s) + C(s) → 2N_2 (g) + 4H_2O(g) + CO_2(g)$  
  
- $–630 \thinspace kJ\thinspace mol^{-1}$ ←<span style="background-color: rgba(241,247,134,0.5)">This one</span>  
- $–540 \thinspace kJ\thinspace mol^{-1}$  
- $+540 \thinspace kJ\thinspace mol^{-1}$   
- $+630 \thinspace kJ\thinspace mol^{-1}$  
