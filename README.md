# Malla Curricular 2025‑1 – Ingeniería Industrial (ULima)

```mermaid
graph TD

%% Nivel 4
CO4[Costeo de Operaciones]
FP4[Fundamentos de Programación]
F2[Física II]
EP4[Estadística y Probabilidad]
MEC4[Mecánica]
C3[Cálculo III]

%% Nivel 5
IO1[Investigación de Operaciones I]
LO5[Fundamentos de Operaciones y Logística]
IE5[Ingeniería Económica]
EE5[Electricidad y Electrónica]
ED5[Ecuaciones Diferenciales]
DE5[Diseño de Experimentos]

%% Nivel 6
IO2[Investigación de Operaciones II]
EDT6[Ergonomía y Diseño del Trabajo]
IE6[Innovación en Ingeniería]
PCO6[Planeamiento y Control de Operaciones]
PI6[Procesos Industriales]
ELE6[Electivo (≥80 créditos)]

%% Nivel 7
IF7[Ingeniería Financiera]
DI7[Diseño de Instalaciones]
IN7[Inteligencia de Negocios]
MSL7[Modelos de Sistemas Logísticos]
CAL7[Calidad]
PM7[Procesos de Manufactura]
ELE7[Electivo (≥100 créditos)]

%% Nivel 8
SP8[Simulación de Procesos]
MPD8[Modelamiento Predictivo de Datos]
SIG8[Sistemas Integrados de Gestión]
GP8[Gestión de Proyectos]
APE8[Análisis de Problemas de Ingeniería]
AI8[Automatización Industrial]
ELE8[Electivo (≥120 créditos)]

%% Nivel 9
EGH9[Ética y Gestión Humana]
PIA9[Proyecto de Ingeniería Aplicada I]
CI9[Ingeniería Comercial]
ELE9a[Electivo I]
ELE9b[Electivo II]

%% Nivel 10
PIA10[Proyecto de Ingeniería Aplicada II]
GEE10[Gerencia Estratégica]
ELE10a[Electivo I]
ELE10b[Electivo II]
ELE10c[Electivo III]

%% Conexiones de prerrequisitos
LC1 --> LC2
LC2 --> LC2
MB1 --> AL2 --> C1 --> C2 --> C3 --> ED5
F1 --> F2
C1 --> EP4
IA3 --> FP4
CO4 --> LO5
CO4 --> IE5
IE5 --> IF7
EP4 --> DE5
IO1 --> IO2
LO5 --> PCO6
EE5 --> IE6
