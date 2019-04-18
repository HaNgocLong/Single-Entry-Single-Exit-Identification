# Single-Entry Single-Exit-Identification (Demo version)
 > The demo is a part of the gProAnalyzer (Graph Based Process Analyzer) toolset.
 > The gProAnalyzer was developed by BPM Lab - Inje University
 
<kbd>
 <img src= "https://github.com/InjeBPM/Single-Entry-Single-Exit-Identification/blob/master/Demo_Overview.png">
</kbd>

A screenshot of the demo - The highlighted SESE regions

<kbd>
 <img src= "https://github.com/InjeBPM/Single-Entry-Single-Exit-Identification/blob/master/Demo_Overview_RPSTwNode.png">
</kbd>

A screenshot of the demo - The RPST defined by Nodes


On Developing
-----------  
  - This demo is written in C# under .Net 4.5 framework
  - The prototype is released as a part of the gProAnalyzer toolset and fully tested with 604 SAP EPC reference models
  - The bug/glitch fixing and updates will be released
  - The final tool is subjected to change without notice
  - The gProAnalyzer toolset includes various of process analysis techniques for process model's verification [[1](https://doi.org/10.1016/j.datak.2014.11.003)]

System Requirements:
------------
 - Windows OS
 - DotNet Framework 4.5 or higher

How to use:
------------
 - Download "SESE_Demo_v1.0" setup file and follow the setup instruction for installation
 - After installation, click "Load Model" to load a process model
 - Click "Run" to get the highlighted SESE region of a given process model
 - The resulted RPST is represent with nodes which each rounded regtangle box depicts the SESE region for each type (e.g. "B" for Bond, "R" for Rigid, and "S" for Series)

Contributors:
------------
 - Yongsun Choi (Prof. Dr.) (*Laboratory Director*)
 - N.Long Ha (PhD Student) (*Lab member*)
 - Choel Min Joo (Prof. Dr.)
 - Pauline Kongsunwan (Prof. Dr.) (*Lab member*)
