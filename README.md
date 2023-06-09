![image](https://github.com/ADerycke/Series-Plotter/assets/130437433/b424b0f9-6329-48d9-bb85-59c1af6edd63)

## General introduction

This file is simply made for accelerate significantly the Excel chart production, and add other kind of chart not natively handle by Excel (e.g., ternary diagram, stacked "temporal" chart...). The file allows to add grid for binary and ternary diagram, with a list of already implemented geochemical grids (cf. grid files).

It's a "work in progress project" so maybe you gonna encounter some trubble and error, so don't hesitated to reported me any problem.
There is no restriction to use and distribute the "Series Plotter" files, as long as you refer this GitHub. 

*Excel version :*
  - should work on any version greeter than Excel 2016
  - never tested on version older than Excel 2016
  - some very specifiques utility may not work on the restrained version of Excel (as students version or application)

*Systems :*
  - Windows 10 (32bit) : not tested but should work
  - Windows 10 (64bi) : tested and work
  - Windows 11 (64bit) : not tested but should work
  - MacOS (Monterey) : tested and don't work
  
  For the MacOS user, Microsoft removed several developpement facilities from Mac Excel, so i'm not working on a proper version by now, sorry...

**Conceptor : Alexis Derycke** 
  - [Reseach Gate](https://www.researchgate.net/profile/Alexis-Derycke)


## How to use the file 
You just have to download the file, openning it and allow the macro execution.

You can find several videos (~2min) in the helping folder that gonna introduce you to the file and show you quickly how to use it. You can find associate data example in the folder to easly test the files and reproduce what its show in videos.

**Step by Step simple use :**
  - open the file
  - add some data (you can click on the "template" to see how to input data)
  - click on the "Get column" button
  - select the wanted element to plot in the "Graphic list" sheet
  - select the wanted kind of graph
  - click on "Plot Graphic" button
  
*for more option, let your mouse on any button and a screentips gonna appear*

https://github.com/ADerycke/Series-Plotter/assets/130437433/d620555c-989c-427b-a564-139f6c200737

# Graphic type :

## graphic XY :

![graph XY](https://user-images.githubusercontent.com/130437433/233654680-7dec2505-8e34-4ba6-90ac-d4c969450cd1.png)

**note :** for binary diagram, multiple automatic grid are already ready to add to graph
![image](https://user-images.githubusercontent.com/130437433/233656030-1236a5e2-c85f-40e5-a94c-f834610e12a8.png)

## graphic XYZ (Z as color) :

![Zcolor - 1](https://github.com/ADerycke/Series-Plotter/assets/130437433/e610d7d9-df17-44d7-8f63-23b37830a7f5)

**note :** the min and max value are determine automatically from the dataset. You can select a third color and indicate it's value. You can also select an automatic round of the min an max value.
![Zcolor](https://github.com/ADerycke/Series-Plotter/assets/130437433/f04832a0-ecdb-4d51-8944-dd2c03fe736f)

## graphic XYZ (ternary diagram) :

![graph XYZ](https://user-images.githubusercontent.com/130437433/233654854-ad3199e7-f194-4f03-9329-8e0e1341f9b2.png)
![graph XYZ (bis)](https://user-images.githubusercontent.com/130437433/233799016-01b8f8f8-f5e9-4137-879a-6b409bcc31da.png)

**note :** for ternary diagram, multiple automatic grid are already ready to add to graph

![image](https://user-images.githubusercontent.com/130437433/233655226-8d13ca9e-ea7e-4495-881e-ff361bf8c55b.png)

## graphic XY - stacked :

![graph XY - stacked ](https://user-images.githubusercontent.com/130437433/233655423-5dc175fc-9fe8-4177-9faa-4711021abeee.png)

## graphic Y (spectra/spider diagram) :

![graph Y](https://user-images.githubusercontent.com/130437433/233655533-995ee4f8-3b7d-4268-9f38-8be0b044d1d1.png)

**note :** for spider diagram, an automatic normalisation is possible (msg pop-up at the selection).
This normalisation gonna be applied/remove to your data in fonction of what you want.
The available normalisation can be found and selected on the "Normalisation" sheet that apprear after it selection.
![image](https://github.com/ADerycke/Series-Plotter/assets/130437433/f1bc2a27-678e-45de-a50b-678474d599d0)

## Normal law and KDE (basic distribution) :

![graph Normal law](https://github.com/ADerycke/Series-Plotter/assets/130437433/97ad0c89-154d-4c71-9103-68ade5a1e215)

## X - Histogram (automatic generation) :

![X - Histogram](https://github.com/ADerycke/Series-Plotter/assets/130437433/e660c782-9aeb-4ce7-b2be-4eb6e6be83f6)

**note :** when you select this, you enter the wanted range (here 6 to 18) and the wanted intervalle (here 1) and excel gonna automatically calculate the distribution in your dataset

