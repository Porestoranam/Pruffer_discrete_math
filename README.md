# Pruffer_discrete_math


The program can create tree graph and visualize it by Prufer code. Also the program builds Prufer code by adjacency list. The project was implemented using jupiter notebook. The construction of the Puгfer code for a given tree and the restoration of a tree by its code is performed with asymptotic complexity O(n) with using O(n) additional memory.

To start you should to download the jupyter. Then you can clone this repository and follow instructions there.

The program Build_Prufer_tree takes as input a sequence of positive integers of length n, whose each element less or equal than n + 2. If the input is incorrect, user will get a message of error. If Prufer code is correct, user will see a visualization of tree with marked vertices.

The program Prufer_encode takes as input number of vertices and adjencency list of your tree. If adjencency list typed correct, the output will be Prufer code of user's tree. Else there is an message which informed user about invalid entered information about edges.

This program was prepared in frame of the course 'Discrete analysis' in Moscow Institute of Physics and Technology. Website of the course: https://mipt.ru/education/chairs/dm/education/courses/common_courses/year2/diskretnyy-analiz-2017-18.php. The program illustrates relation between trees and numerical sequences by using Prufer code.

Other existing related programs: https://github.com/skswanke/pruferdecode - a similar implementation in javascript using web technologies.

https://gist.github.com/forthright48/f403befb8c12ad18c38f21825ce98af6 - a console program for constructing an adjacency matrix by the code of the proliferator, implementation in C ++.

https://github.com/GalaxyDragon/Prufer_code_decoder - a program of buildig and visualizating tree corresponding to the Prufer code by Alexey Berdovsky (MIPT 2019).

Authors: Mazheyka Mikhail and Akopyan Albert Date: 20.10.19 (MIPT)
