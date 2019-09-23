# Awesome-CNC (CAD/CAM/CAE/FEM) 
September 2019

Eine Liste von Software für die Prototypenfertigung via CNC oder 3D-Druck.
Diese Liste umfasst dabei ebenso die Randgebiete, wie z.B. Platinendesign
und Photogrammetrie, die in weiterer Folge bearbeitet und gedruckt/gefräst
werden können. Kommerzielle Produkte - oder Produkte mit erforderlicher 
Registrierung werden der Vollständigkeit halber mit angegeben.

# Softwareeigenschaften
Eigenschaft  | Ausgesprochen                | Bedeutung
------------ | ---------------------------- | -------------
OSS          | Open Source Software	    | Software mit freiem Quelltext
WIN          | Microsoft Windows Nativ      | Software ist eine Windows Anwendung (Keine Emulation)
LIN          | Linux Anwendung              | Software ist eine Linux Anwendung
EMU          | Emuliertes Linux             | Software für Linux, lauffähig in Windows über Docker/Linux-Subsystem/...
BUY          | Kommerzielles Produkt        | Kommerzielles Produkt
REG          | Registrierung erforderlich   | Nur mit Benutzeraccount verfügbar
WEB          | Webanwendung                 | Webanwendung lokal oder im Internet
OLD          | Veraltet                     | Software wird nicht mehr gepflegt und ist veraltet
GUI          | Grafisches Benutzerinterface | 
CMD          | Kommandozeilenanwendung      | 

# Fachbegriffe
Begriff      | Ausgesprochen                  | Bedeutung
------------ | ------------------------------ | -------------
CNC          | Computerized Numerical Control | Computergestützte Materialbearbeitung
CAD          | Computer-aided design	      | Computergestütztes 2D und 3D Design
CAM          | Computer-aided manufacturing   | Computergestütztes Fertigen, CNC, Druck
CAE          | Computer-aided engineering     | Bauteilentwicklung physikalische Eigenschaften
FEM/FEA      | Finite-Elemente-Methode        | Berechnungsmethoden
CFD          | Computational Fluid Dynamics   | Fluss berechnen, z.B. Lüfter
PCB          | Printed Circuit Board          | Platinendesign
																												
### Distributionen
- CAELinux														
															
### Bildbearbeitung	
Anwendung       | Beschreibung                                    | Eigenschaften
--------------- | ----------------------------------------------- | -------------
**ImageMagick**	| Bildbearbeitung Kommandozeile                   | WIN+OSS+CMD
**GIMP**	| Bildbearbeitung                                 | WIN+OSS+GUI
**Inkscape**	| Bildbearbeitung Vektorgrafiken                  | WIN+OSS+GUI

### 2D CAD	
Anwendung          | Beschreibung                                 | Eigenschaften
------------------ | -------------------------------------------- | -------------
**LibreCAD**	   | CAD                                          | WIN+OSS+GUI
QCad	           | CAD (kommerziell)                            | WIN+GUI
Autocad	           | CAD (kommerziell)                            | WIN+GUI

### 3D CAD	
Anwendung          | Beschreibung                                 | Eigenschaften
------------------ | -------------------------------------------- | -------------
**Blender**        | großer Funktionsumfang, Nicht parametrisch   | WIN+OSS
**OpenScad**       | 3D-Design Programmierung, SCAD-Sprache       | WIN+OSS
**SALOME 9.0**     | Shaper Workbench, Parametrisch               | WIN+OSS
FreeCAD            | großer Funktionsumfang, parametrisch         | WIN+OSS
Tinkercad          | ...                                          | WEB+REG
SketchUp           | Registrierung erforderlich                   | WIN+REG
OpenJScad          | 3D-Design Programmierung, Javascript-Sprache | WEB+OSS
BRL-CAD            | 3D-Design Programmierung, BRLCAD-Sprache     | WIN+OSS
Autocad Fusion 360 | Parametrisch                                 | WIN+BUY
Autocad Inventor   | Parametrisch                                 | WIN+BUY
Solid Edge         | Parametrisch                                 | WIN+BUY
123D-Design        | Entwicklung eingestellt                      | OLD
Sculptris          | Entwicklung eingestellt                      | OLD
HeeksCAD           | Entwicklung eingestellt                      | OLD
																	
### 3D-Reperatur				
Anwendung          | Beschreibung                                 | Eigenschaften
------------------ | -------------------------------------------- | -------------
**Meshlab**        | großer Funktionsumfang                       | WIN+FREE
Meshmixer          |                                              | WIN+FREE
Meshrepair         |                                              | WIN+FREE
																	
### Schaltplandesign						
Anwendung          | Beschreibung                                 | Eigenschaften
------------------ | -------------------------------------------- | -------------
**KICAD**          | großer Funktionsumfang, große Community      | WIN+OSS
Fritzing           | kleiner Funktionsumfang, Steckplatinen       | WIN+FREE
EasyEDA            |                                              | WEB+REG
Eagle              |                                              | WIN+BUY
Target 3001!       | Discover Version bis 250 Pins/Pads gratis    | WIN+BUY+FREE
OrCad              |                                              | WIN+BUY
Designspark PCB    |                                              | WIN+REG
															
### Lasergravur	
Anwendung          | Beschreibung                                 | Eigenschaften
------------------ | -------------------------------------------- | -------------
**LaserGRBL**      |                                              | WIN+OSS
Inkscape           | Jtech Laser-Plugin erforderlich              | WIN+OSS
														
### PCB			
Anwendung          | Beschreibung                                  | Eigenschaften
------------------ | --------------------------------------------- | -------------
**FlatCAM**        | Konvertiert Gerber/Drill zu Gcode             | WIN+OSS
GRBLPlotter        |                                               | WIN+OSS
FreeMill           | Plugin als Anbindung an kommerzielles Produkt | WIN+FREE
HeeksCNC           | nur Abstürze auf Windows 10                   | OLD
PyCam              | Windows Version wird nicht mehr gepflegt      | WIN+OSS
CamBam             |                                               | WIN+OSS
															
### Gcode Sender (CAM)															
Anwendung          | Beschreibung                                 | Eigenschaften
------------------ | -------------------------------------------- | -------------
**BCNC**           | großer Funktionsumfang, unaufgeräumt, träge  | WIN+OSS
...                | Drag Knife support                           |
CNCJS              |                                              | WIN+OSS
GRBLControler      | (Candle) - Easy, stabil, kleiner Funktionsumfang.    | WIN+OSS
UGS Platform       | Version 2.0 in Entwicklung, Vielversprechend, Beta.  | WIN+OSS
UGS Classic        | Universal G-Code Sender. Wird ersetzt durch Platform | WIN+OSS
GRBLGru            | DragKnife-Support                            | WIN+OSS
Deskproto          |                                              | WIN+BUY
SheetCAM           |                                              | WIN+BUY
G-Simple           |                                              | WIN+OSS	
DXF2GCode          | DragKnife-Support                            | WIN+OSS
InkCut             | DragKnife-Support + Incscape Plugin          | WIN+OSS
															
### Slicer
Anwendung          | Beschreibung                                 | Eigenschaften
------------------ | -------------------------------------------- | -------------
**Slic3r**         | gute Ergebnisse, Anbindung an Octoprint      | WIN+OSS
PrusaSlic3r        | gute Ergebnisse                              | WIN+OSS
Pronterface        | Justierung                                   | WIN+OSS
Cura               | gute Ergebnisse                              | WIN+OSS
Simplify3D         | sehr gute Ergebnisse, viele Möglichkeiten    | WIN+OSS
Mattercontrol      |                                              | WIN+OSS
IdeaMaker          |                                              | WIN+OSS
															
### CNC-Simulation				
Anwendung          | Beschreibung                                 | Eigenschaften
------------------ | -------------------------------------------- | -------------
**Camotics**       |                                              | WIN+OSS
Openbuilds Control |                                              | WIN+OSS
UGS Platform       | Version 2.0 in Entwicklung, Beta             | WIN+OSS
UGS Classic        | Universal G-Code Sender                      | WIN+OSS
															
### 3D-Rekonstruktion (photogrammetry, Bilder zu 3D-Modell)
Anwendung          | Beschreibung                                 | Eigenschaften
------------------ | -------------------------------------------- | -------------
**MeshRoom**       | Beste Ergebnisse                             | WIN+OSS
MeshRecon          |                                              | WIN+OSS
ColMap             |                                              | WIN+OSS
VisualSFM          |                                              | WIN+OSS
OpenMVS            |                                              | WIN+OSS
OpenMVG            |                                              | WIN+OSS
Bundler            |                                              | WIN+OSS
MVE                |                                              | WIN+OSS
SVMS               |                                              | WIN+OSS
TexRecon           |                                              | WIN+OSS
															
### 3D-Engineering (CAE)				
Anwendung          | Beschreibung                                 | Eigenschaften
------------------ | -------------------------------------------- | -------------
Elmer              |                                              | WIN+OSS
OpenFOAM           | OpenCFD - OpenFOAM                           | WIN+EMU+OSS
**Salome Meca 8.0**| Salome Meca = Salome + Code_Aster + Paraview | WIN+OSS
OneLab             | GMSH + GetDP                                 | WIN+OSS
HelyxOS            |                                              | WIN+OSS
CFSuite            |                                              | WIN+OSS
CastNet            |                                              | WIN+OSS
VisualCFD          |                                              | WIN+OSS
OpenCascade        | 3D-Library                                   | WIN+OSS
ParaView           | Berechnungen visualisieren                   | WIN+OSS
Code_Aster         | Finite Element Solver                        | WIN+OSS
Mfront             |                                              | WIN+OSS
Calculix           |                                              | WIN+OSS
NetGen/NGSolve     | Mesh Generator                               | WIN+OSS
MMG3D              |                                              | WIN+OSS
FEMAP              |                                              | WIN+OSS
MBDyn              |                                              | WIN+OSS
CFMesh             |                                              | WIN+OSS
TetGen             | Mesh Generator                               | WIN+OSS
GMSH               | Mesh/Grid Generator + Post Processor         | WIN+OSS
GetDP              | Finite Element Solver                        | WIN+OSS
FreeFem++          | Finite Element Solver                        | WIN+OSS
OpenSees           | Finite Element Solver                        | WIN+OSS
Dune               | Finite Element Solver                        | WIN+OSS
Z88                | Finite Element Solver                        | WIN+OSS

Ansys Workbench    |                                              | WIN+BUY
Solid Edge         |                                              | WIN+BUY
		
# Server
Anwendung          | Beschreibung                                 | Eigenschaften
------------------ | -------------------------------------------- | -------------
Octoprint          | Raspberry 3D-Druck Server + CNC Plugin       | LIN+OSS
SER2NET            | Serial Port over LAN                         | LIN+OSS
