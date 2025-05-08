# 19AI513 - GAME-PROGRAMMING
# EX-01
# Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine
# AIM:
 To inplement various effects in a material such as emissive, roughness and metallic properties in Unreal Engine.
# PROCEDURE:
1.Right-click in the content browser and choose material. Rename the material and double-click to open it.

2.Right-click in the working space and search for constants. In constant choose constant vector

3.After this double click on the constant vector 4 and edit the colour using the colour picker.

4.After adjusting the colour click okay and save it.

5.They join the output of the constant vector 4 to the base colour.

6.Create a single constant using step 3 and adjust its value of it using detail panel by adjusting the value.

7.And you can apply this constant value to metallic, roughness, emissive colour etc..

8.For emissive you need to multiply the constant vector 4 and constant and apply it to emissive colour.

9.For creating walls and gate you need to create a material and import a png image.

10.And use the png image as texture sample and connect the (rgb) of texture sample to the emissive colour & connect the alpha value of texture sample to the opacity.

11.The save it, go to the third person example map and create a plane or cube apply the material which you have created for the wall or gate.
# OUTPUT:
 # METALLIC:
 ## MATERIAL GRAPH:
![Screenshot 2025-05-08 105259](https://github.com/user-attachments/assets/38ff7ec8-66b4-48cf-811e-7d46a2a0d9eb)
 ## OUTPUT:
![image](https://github.com/user-attachments/assets/5d2e6cbb-c9dc-4a08-8b93-59048b677fe2)

 # ROUGHNESS:
  ## MATERIAL GRAPH:
  ![Screenshot 2025-05-08 105756](https://github.com/user-attachments/assets/88c68043-09cb-470a-a409-652eebf05313)
  ## OUTPUT:
  ![image](https://github.com/user-attachments/assets/c3a8ff2b-7881-4676-81e3-3c338d331625)
 
 # EMISSIVE:
  ## MATERIAL GRAPH:
   ![image](https://github.com/user-attachments/assets/083c866c-1565-48e1-a305-c1649409d4be)
   ## OUTPUT:
   ![image](https://github.com/user-attachments/assets/a8cfe230-7456-49fe-81a4-f6a489be9f14)
# RESULT:
Thus, various effects in material properties is successfully implemented in Unreal Engine.
