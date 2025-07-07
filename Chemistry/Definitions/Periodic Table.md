```tikz  
\begin{document}  
\begin{tikzpicture}  
  
% Define element styles with colors  
\tikzstyle{element} = [draw, minimum width=2.5em, minimum height=2.5em, font=\small, color=white]  
\tikzstyle{number} = [font=\tiny, color=white]  
\tikzstyle{undefined} = [element, fill=yellow!15]  
\tikzstyle{alkali} = [element, fill=green!20]  
\tikzstyle{alkaline} = [element, fill=blue!20]  
\tikzstyle{transition} = [element, fill=gray!20]  
\tikzstyle{metalloid} = [element, fill=yellow!20]  
\tikzstyle{halogen} = [element, fill=purple!20]  
\tikzstyle{noble} = [element, fill=red!20]  
\tikzstyle{other} = [element, fill=yellow!40]  
\tikzstyle{lanthanoid} = [element, fill=blue!50]  
\tikzstyle{actinoid} = [element, fill=blue!70]  
  
%SPFD blocks and labels  
\draw[red] (-0.47,0.47) -- (0.47,0.47) -- (0.47,-0.53) -- (1.47,-0.53) -- (1.47,-6.47)-- (-0.47,-6.47) -- (-0.47,0.47);  
\draw[blue] (1.53,-2.53) -- (11.47,-2.53) -- (11.47,-6.47) -- (1.53,-6.47) -- (1.53,-2.53);  
\draw[green] (11.53,-0.53) -- (16.53,-0.53) -- (16.53,0.47) -- (17.47,0.47) -- (17.47,-6.47) -- (11.53,-6.47) -- (11.53,-0.53);  
\draw[yellow] (3.53,-7.03) -- (17.47,-7.03) -- (17.47,-8.97) -- (3.53,-8.97) -- (3.53,-7.03);  
\node at (0.5,-6.75) {s-block};  
\node at (6.5,-6.75) {d-block};  
\node at (14.5,-6.75) {p-block};  
\node at (10.5,-9.25) {f-block};  
  
% Labels  
\node at (0, 2) {1};  
\node at (1, 2) {2};  
\node at (12, 2) {3};  
\node at (13, 2) {4};  
\node at (14, 2) {5};  
\node at (15, 2) {6};  
\node at (16, 2) {7};  
\node at (17, 2) {0};  
  
%links  
\fill[color=gray] (1.5,-5) circle (0.03125);  
\fill[color=gray] (1.5,-5.8) circle (0.03125);  
\fill[color=gray] (1.5,-6.2) circle (0.03125);  
\fill[color=gray] (3.5,-7.5) circle (0.03125);  
\fill[color=gray] (3.5,-8.7) circle (0.03125);  
\fill[color=gray] (3.5,-8.3) circle (0.03125);  
  
% Group labels  
\node at (0, 0.75) {(1)};  
\node at (1, -0.25) {(2)};  
\node at (2, -2.25) {(3)};  
\node at (3, -2.25) {(4)};  
\node at (4, -2.25) {(5)};  
\node at (5, -2.25) {(6)};  
\node at (6, -2.25) {(7)};  
\node at (7, -2.25) {(8)};  
\node at (8, -2.25) {(9)};  
ode at (9, -2.25) {(10)};  
\node at (10, -2.25) {(11)};  
\node at (11, -2.25) {(12)};  
\node at (12, -0.25) {(13)};  
\node at (13, -0.25) {(14)};  
\node at (14, -0.25) {(15)};  
\node at (15, -0.25) {(16)};  
\node at (16, -0.25) {(17)};  
\node at (17, 0.75) {(18)};  
  
% Period 1  
\node[undefined] at (0, 0) {H};  
\node[noble] at (17, 0) {He};  
  
% Period 2  
\node[alkali] at (0, -1) {Li};  
\node[alkaline] at (1, -1) {Be};  
\node[metalloid] at (12, -1) {B};  
\node[other] at (13, -1) {C};  
\node[other] at (14, -1) {N};  
\node[other] at (15, -1) {O};  
\node[halogen] at (16, -1) {F};  
\node[noble] at (17, -1) {Ne};  
  
% Period 3  
\node[alkali] at (0, -2) {Na};  
\node[alkaline] at (1, -2) {Mg};  
\node[transition] at (12, -2) {Al};  
\node[metalloid] at (13, -2) {Si};  
\node[other] at (14, -2) {P};  
\node[other] at (15, -2) {S};  
\node[halogen] at (16, -2) {Cl};  
\node[noble] at (17, -2) {Ar};  
  
% Period 4  
\node[alkali] at (0, -3) {K};  
\node[alkaline] at (1, -3) {Ca};  
\node[transition] at (2, -3) {Sc};  
\node[transition] at (3, -3) {Ti};  
\node[transition] at (4, -3) {V};  
\node[transition] at (5, -3) {Cr};  
\node[transition] at (6, -3) {Mn};  
\node[transition] at (7, -3) {Fe};  
\node[transition] at (8, -3) {Co};  
\node[transition] at (9, -3) {Ni};  
\node[transition] at (10, -3) {Cu};  
\node[transition] at (11, -3) {Zn};  
\node[transition] at (12, -3) {Ga};  
\node[metalloid] at (13, -3) {Ge};  
\node[metalloid] at (14, -3) {As};  
\node[other] at (15, -3) {Se};  
\node[halogen] at (16, -3) {Br};  
\node[noble] at (17, -3) {Kr};  
  
% Period 5  
\node[alkali] at (0, -4) {Rb};  
\node[alkaline] at (1, -4) {Sr};  
\node[transition] at (2, -4) {Y};  
\node[transition] at (3, -4) {Zr};  
\node[transition] at (4, -4) {Nb};  
\node[transition] at (5, -4) {Mo};  
\node[transition] at (6, -4) {Tc};  
\node[transition] at (7, -4) {Ru};  
\node[transition] at (8, -4) {Rh};  
\node[transition] at (9, -4) {Pd};  
\node[transition] at (10, -4) {Ag};  
\node[transition] at (11, -4) {Cd};  
\node[transition] at (12, -4) {In};  
\node[transition] at (13, -4) {Sn};  
\node[metalloid] at (14, -4) {Sb};  
\node[metalloid] at (15, -4) {Te};  
\node[halogen] at (16, -4) {I};  
\node[noble] at (17, -4) {Xe};  
  
% Period 6  
\node[alkali] at (0, -5) {Cs};  
\node[alkaline] at (1, -5) {Ba};  
\node[lanthanoid] at (2, -5) {La};  
\node[transition] at (3, -5) {Hf};  
\node[transition] at (4, -5) {Ta};  
\node[transition] at (5, -5) {W};  
\node[transition] at (6, -5) {Re};  
\node[transition] at (7, -5) {Os};  
\node[transition] at (8, -5) {Ir};  
\node[transition] at (9, -5) {Pt};  
\node[transition] at (10, -5) {Au};  
\node[transition] at (11, -5) {Hg};  
\node[transition] at (12, -5) {Tl};  
\node[transition] at (13, -5) {Pb};  
\node[transition] at (14, -5) {Bi};  
\node[metalloid] at (15, -5) {Po};  
\node[halogen] at (16, -5) {At};  
\node[noble] at (17, -5) {Rn};  
  
% Period 7  
\node[alkali] at (0, -6) {Fr};  
\node[alkaline] at (1, -6) {Ra};  
\node[actinoid] at (2, -6) {Ac};  
\node[transition] at (3, -6) {Rf};  
\node[transition] at (4, -6) {Db};  
\node[transition] at (5, -6) {Sg};  
\node[transition] at (6, -6) {Bh};  
\node[transition] at (7, -6) {Hs};  
\node[transition] at (8, -6) {Mt};  
\node[transition] at (9, -6) {Ds};  
\node[transition] at (10, -6) {Rg};  
\node[transition] at (11, -6) {Cn};  
\node[transition] at (12, -6) {Nh};  
\node[transition] at (13, -6) {Fl};  
\node[transition] at (14, -6) {Mc};  
\node[transition] at (15, -6) {Lv};  
\node[halogen] at (16, -6) {Ts};  
\node[noble] at (17, -6) {Og};  
  
% Lanthanoids  
\node[lanthanoid] at (4,-7.5) {Ce};  
\node[lanthanoid] at (5,-7.5) {Pr};  
\node[lanthanoid] at (6,-7.5) {Nd};  
\node[lanthanoid] at (7,-7.5) {Pm};  
\node[lanthanoid] at (8,-7.5) {Sm};  
\node[lanthanoid] at (9,-7.5) {Eu};  
\node[lanthanoid] at (10,-7.5) {Gd};  
\node[lanthanoid] at (11,-7.5) {Tb};  
\node[lanthanoid] at (12,-7.5) {Dy};  
\node[lanthanoid] at (13,-7.5) {Ho};  
\node[lanthanoid] at (14,-7.5) {Er};  
\node[lanthanoid] at (15,-7.5) {Tm};  
\node[lanthanoid] at (16,-7.5) {Yb};  
\node[lanthanoid] at (17,-7.5) {Lu};  
  
%Actanoids  
\node[actinoid] at (4,-8.5) {Th};  
\node[actinoid] at (5,-8.5) {Pa};  
\node[actinoid] at (6,-8.5) {U};  
\node[actinoid] at (7,-8.5) {Np};  
\node[actinoid] at (8,-8.5) {Pu};  
\node[actinoid] at (9,-8.5) {Am};  
\node[actinoid] at (10,-8.5) {Cm};  
\node[actinoid] at (11,-8.5) {Bk};  
\node[actinoid] at (12,-8.5) {Cf};  
\node[actinoid] at (13,-8.5) {Es};  
\node[actinoid] at (14,-8.5) {Fm};  
\node[actinoid] at (15,-8.5) {Md};  
\node[actinoid] at (16,-8.5) {No};  
\node[actinoid] at (17,-8.5) {Lr};  
  
%RAM  
\node[number] at (0,0.25) {1.0};  
\node[number] at (17,0.25) {4.0};  
\node[number] at (0,-0.75) {6.9};  
\node[number] at (0,-1.75) {23.0};  
\node[number] at (0,-2.75) {39.1};  
\node[number] at (0,-3.75) {85.5};  
\node[number] at (0,-4.75) {132.9};  
\node[number] at (0,-5.75) {[223]};  
\node[number] at (1,-0.75) {9.0};  
\node[number] at (1,-1.75) {24.3};  
\node[number] at (1,-2.75) {40.1};  
\node[number] at (1,-3.75) {87.6};  
\node[number] at (1,-4.75) {137.5};  
\node[number] at (1,-5.75) {[226]};  
\node[number] at (2,-2.75) {45.0};  
\node[number] at (2,-3.75) {88.9};  
\node[number] at (2,-4.75) {138.9};  
\node[number] at (2,-5.75) {[227]};  
\node[number] at (3,-2.75) {47.9};  
\node[number] at (3,-3.75) {91.2};  
\node[number] at (3,-4.75) {178.5};  
\node[number] at (3,-5.75) {[267]};  
\node[number] at (4,-2.75) {50.9};  
\node[number] at (4,-3.75) {96.0};  
\node[number] at (4,-4.75) {180.9};  
\node[number] at (4,-5.75) {[270]};  
\node[number] at (4,-7.25) {140.1};  
\node[number] at (4,-8.25) {232.0};  
\node[number] at (5,-2.75) {53.0};  
\node[number] at (5,-3.75) {96.0};  
\node[number] at (5,-4.75) {183.8};  
\node[number] at (5,-5.75) {[269]};  
\node[number] at (5,-7.25) {140.9};  
\node[number] at (5,-8.25) {231};  
\node[number] at (6,-2.75) {54.9};  
\node[number] at (6,-3.75) {[97]};  
\node[number] at (6,-4.75) {186.2};  
\node[number] at (6,-5.75) {[270]};  
\node[number] at (6,-7.25) {144.2};  
\node[number] at (6,-8.25) {238};  
\node[number] at (7,-2.75) {55.8};  
\node[number] at (7,-3.75) {101.1};  
\node[number] at (7,-4.75) {190.2};  
\node[number] at (7,-5.75) {[270]};  
\node[number] at (7,-7.25) {[145]};  
\node[number] at (7,-8.25) {[237]};  
\node[number] at (8,-2.75) {58.9};  
\node[number] at (8,-3.75) {102.9};  
\node[number] at (8,-4.75) {192.2};  
\node[number] at (8,-5.75) {[278]};  
\node[number] at (8,-7.25) {150.4};  
\node[number] at (8,-8.25) {[244]};  
\node[number] at (9,-2.75) {58.7};  
\node[number] at (9,-3.75) {106.4};  
\node[number] at (9,-4.75) {195.1};  
\node[number] at (9,-5.75) {[281]};  
\node[number] at (9,-7.25) {152.0};  
\node[number] at (9,-8.25) {[243]};  
\node[number] at (10,-2.75) {63.5};  
\node[number] at (10,-3.75) {107.9};  
\node[number] at (10,-4.75) {197.0};  
\node[number] at (10,-5.75) {[281]};  
\node[number] at (10,-7.25) {157.3};  
\node[number] at (10,-8.25) {[247]};  
\node[number] at (11,-2.75) {65.4};  
\node[number] at (11,-3.75) {112.4};  
\node[number] at (11,-4.75) {200.6};  
\node[number] at (11,-5.75) {[285]};  
\node[number] at (11,-7.25) {158.9};  
\node[number] at (11,-8.25) {[247]};  
\node[number] at (12,-0.75) {10.8};  
\node[number] at (12,-1.75) {27.0};  
\node[number] at (12,-2.75) {69.7};  
\node[number] at (12,-3.75) {114.8};  
\node[number] at (12,-4.75) {204.4};  
\node[number] at (12,-5.75) {[286]};  
\node[number] at (12,-7.25) {162.5};  
\node[number] at (12,-8.25) {[251]};  
\node[number] at (13,-0.75) {12.0};  
\node[number] at (13,-1.75) {28.1};  
\node[number] at (13,-2.75) {72.6};  
\node[number] at (13,-3.75) {118.7};  
\node[number] at (13,-4.75) {207.2};  
\node[number] at (13,-5.75) {[289]};  
\node[number] at (13,-7.25) {164.9};  
\node[number] at (13,-8.25) {[252]};  
\node[number] at (14,-0.75) {14.0};  
\node[number] at (14,-1.75) {28.1};  
\node[number] at (14,-2.75) {74.9};  
\node[number] at (14,-3.75) {121.8};  
\node[number] at (14,-4.75) {209.0};  
\node[number] at (14,-5.75) {[289]};  
\node[number] at (14,-7.25) {167.3};  
\node[number] at (14,-8.25) {[257]};  
\node[number] at (15,-0.75) {16.0};  
\node[number] at (15,-1.75) {32.1};  
\node[number] at (15,-2.75) {79.0};  
\node[number] at (15,-3.75) {127.6};  
\node[number] at (15,-4.75) {[209]};  
\node[number] at (15,-5.75) {[293]};  
\node[number] at (15,-7.25) {168.9};  
\node[number] at (15,-8.25) {[258]};  
\node[number] at (16,-0.75) {19.0};  
\node[number] at (16,-1.75) {35.5};  
\node[number] at (16,-2.75) {79.9};  
\node[number] at (16,-3.75) {126.9};  
\node[number] at (16,-4.75) {[210]};  
\node[number] at (16,-5.75) {[294]};  
\node[number] at (16,-7.25) {173.0};  
\node[number] at (16,-8.25) {[259]};  
\node[number] at (17,-0.75) {20.1};  
\node[number] at (17,-1.75) {39.9};  
\node[number] at (17,-2.75) {83.8};  
\node[number] at (17,-3.75) {131.3};  
\node[number] at (17,-4.75) {[222]};  
\node[number] at (17,-5.75) {[294]};  
\node[number] at (17,-7.25) {175.0};  
\node[number] at (17,-8.25) {[262]};  
  
%Proton number  
\node[number] at (0,-0.25) {1};  
\node[number] at (17,-0.25) {2};  
\node[number] at (00,-1.25) {3};  
\node[number] at (01,-1.25) {4};  
\node[number] at (12,-1.25) {5};  
\node[number] at (13,-1.25) {6};  
\node[number] at (14,-1.25) {7};  
\node[number] at (15,-1.25) {8};  
\node[number] at (16,-1.25) {9};  
\node[number] at (17,-1.25) {10};  
\node[number] at (00,-2.25) {11};  
\node[number] at (01,-2.25) {12};  
\node[number] at (12,-2.25) {13};  
\node[number] at (13,-2.25) {14};  
\node[number] at (14,-2.25) {15};  
\node[number] at (15,-2.25) {16};  
\node[number] at (16,-2.25) {17};  
\node[number] at (17,-2.25) {18};  
\node[number] at (00,-3.25) {19};  
\node[number] at (01,-3.25) {20};  
\node[number] at (02,-3.25) {21};  
\node[number] at (03,-3.25) {22};  
\node[number] at (04,-3.25) {23};  
\node[number] at (05,-3.25) {24};  
\node[number] at (06,-3.25) {25};  
\node[number] at (07,-3.25) {26};  
\node[number] at (08,-3.25) {27};  
\node[number] at (09,-3.25) {28};  
\node[number] at (10,-3.25) {29};  
\node[number] at (11,-3.25) {30};  
\node[number] at (12,-3.25) {31};  
\node[number] at (13,-3.25) {32};  
\node[number] at (14,-3.25) {33};  
\node[number] at (15,-3.25) {34};  
\node[number] at (16,-3.25) {35};  
\node[number] at (17,-3.25) {36};  
\node[number] at (00,-4.25) {37};  
\node[number] at (01,-4.25) {38};  
\node[number] at (02,-4.25) {39};  
\node[number] at (03,-4.25) {40};  
\node[number] at (04,-4.25) {41};  
\node[number] at (05,-4.25) {42};  
\node[number] at (06,-4.25) {43};  
\node[number] at (07,-4.25) {44};  
\node[number] at (08,-4.25) {45};  
\node[number] at (09,-4.25) {46};  
\node[number] at (10,-4.25) {47};  
\node[number] at (11,-4.25) {48};  
\node[number] at (12,-4.25) {49};  
\node[number] at (13,-4.25) {50};  
\node[number] at (14,-4.25) {51};  
\node[number] at (15,-4.25) {52};  
\node[number] at (16,-4.25) {53};  
\node[number] at (17,-4.25) {54};  
\node[number] at (00,-5.25) {55};  
\node[number] at (01,-5.25) {56};  
\node[number] at (02,-5.25) {57};  
\node[number] at (04,-7.75) {58};  
\node[number] at (05,-7.75) {59};  
\node[number] at (06,-7.75) {60};  
\node[number] at (07,-7.75) {61};  
\node[number] at (08,-7.75) {62};  
\node[number] at (09,-7.75) {63};  
\node[number] at (10,-7.75) {64};  
\node[number] at (11,-7.75) {65};  
\node[number] at (12,-7.75) {66};  
\node[number] at (13,-7.75) {67};  
\node[number] at (14,-7.75) {68};  
\node[number] at (15,-7.75) {69};  
\node[number] at (16,-7.75) {70};  
\node[number] at (17,-7.75) {71};  
\node[number] at (03,-5.25) {72};  
\node[number] at (04,-5.25) {73};  
\node[number] at (05,-5.25) {74};  
\node[number] at (06,-5.25) {75};  
\node[number] at (07,-5.25) {76};  
\node[number] at (08,-5.25) {77};  
\node[number] at (09,-5.25) {78};  
\node[number] at (10,-5.25) {79};  
\node[number] at (11,-5.25) {80};  
\node[number] at (12,-5.25) {81};  
\node[number] at (13,-5.25) {82};  
\node[number] at (14,-5.25) {83};  
\node[number] at (15,-5.25) {84};  
\node[number] at (16,-5.25) {85};  
\node[number] at (17,-5.25) {86};  
\node[number] at (00,-6.25) {87};  
\node[number] at (01,-6.25) {88};  
\node[number] at (02,-6.25) {89};  
\node[number] at (04,-8.75) {98};  
\node[number] at (05,-8.75) {99};  
\node[number] at (06,-8.75) {90};  
\node[number] at (07,-8.75) {91};  
\node[number] at (08,-8.75) {92};  
\node[number] at (09,-8.75) {93};  
\node[number] at (10,-8.75) {94};  
\node[number] at (11,-8.75) {95};  
\node[number] at (12,-8.75) {96};  
\node[number] at (13,-8.75) {97};  
\node[number] at (14,-8.75) {100};  
\node[number] at (15,-8.75) {101};  
\node[number] at (16,-8.75) {102};  
\node[number] at (17,-8.75) {103};  
\node[number] at (03,-6.25) {104};  
\node[number] at (04,-6.25) {105};  
\node[number] at (05,-6.25) {106};  
\node[number] at (06,-6.25) {107};  
\node[number] at (07,-6.25) {108};  
\node[number] at (08,-6.25) {109};  
\node[number] at (09,-6.25) {110};  
\node[number] at (10,-6.25) {111};  
\node[number] at (11,-6.25) {112};  
\node[number] at (12,-6.25) {113};  
\node[number] at (13,-6.25) {114};  
\node[number] at (14,-6.25) {115};  
\node[number] at (15,-6.25) {116};  
\node[number] at (16,-6.25) {117};  
\node[number] at (17,-6.25) {118};  
  
%Period Numbers  
\foreach \y in {1,...,7} {  
	\node at (-0.75,1-\y) {\y};  
}  
  
\end{tikzpicture}  
\end{document}  
```  
