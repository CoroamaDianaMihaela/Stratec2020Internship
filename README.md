# STRATECInternshipProblem2020

This repository contains mine and Coroama Larisa's attempt at solving "The 2020 Internship Software Challenge" from STRATEC Biomedical company. 

This software had the task of connecting dots in a matrix, there could be either two or more dots to conected between each other. One of the key restraints was that the connecting roads must not intersect with each other and there would always be at least one block separating them.

This program was made in collaboration with Coroama Larisa-Gabriela and it has an interactive GUI where each button represents a step in the problem. 

Step one outputs:
<p align="center">
<img src="https://github.com/CoroamaLarisa/STRATECInternshipProblem2020/blob/main/images_internship/step_one.png" width="300" height="300">
</p>


Step two outputs:

<p align="center">
<img src="https://github.com/CoroamaLarisa/STRATECInternshipProblem2020/blob/main/images_internship/step_two.png" width="300" height="300">
</p>


For the third step we had to specify the blocks that were the intersection between the roads:

<p align="center">
<img src="https://github.com/CoroamaLarisa/STRATECInternshipProblem2020/blob/main/images_internship/step_three.png" width="300" height="300">
</p>


The last step was the most challenging one. We opted to let the user input their desired lines and columns and then fill in the matrix with the dots, as the example shows. 
The software will find and show the best roads. If the user inputted something impossible( two roads can't happen at the same time without overlapping) the software will go on a continuous loop and then crash.

One example of user inputting matrix(where the matrix is 20x20) is:
<p align="center">
<img src="https://github.com/CoroamaLarisa/STRATECInternshipProblem2020/blob/main/images_internship/step_four.png" width="300" height="300">
  <img src="https://github.com/CoroamaLarisa/STRATECInternshipProblem2020/blob/main/images_internship/step_four_resulted.png" width="300" height="300">
</p>
