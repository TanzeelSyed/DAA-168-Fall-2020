#DAA 168 Fall 2020: Course Repository#
###PROJECT MEMBERS###
StdID | Name
------------ | -------------
**60790** | **Syed Muhammad Tanzeel** <!--this is the group leader in bold-->
61864 | Ehrar Hussain
61917 | Muhammad Siraj
<!-- Replace name and student ids with acutally group member names and ids-->

## Description ##
This repository contains assignments and project submitted to DAA course offered in Fall 2020 at PafKiet.

By Ehrar Hussain

## Phase_1 N-Queen Solution by Recursive Backtracking Solutions ##
   # Recursive Backtracking Solutions Algorithm Analysis ##
   
   Backtracking alogrithm is a technique which is used in order to recursively solve problems by
   attempting to construct a solution progressively, one part at a time, and clearing solution
   that doesn't succeed to satisfy the limits of the problem at any point of time.
   
   Using Backtracking algorithm to arrange N queens on NxN chessboard is one most common instances.
   In this problem the N queens are to be placed on a chessboard in a way that no queen is
   attacking other queen. Before going further we must learn how queen attack. The queen in
   chess attack in vertical, horizontal and diagonal way. In the begining we place first queen
   randomly and then we place the next queen in any of the available safe places (place that
   are not in attack with first queen). We repeatdly perform this process until all unplaced
   queens comes to 0 or if there is no place left which is safe. In case if there is no place 
   left for remaining queen we change the position of last queen that was placed. We have to 
   carry on with this process and in the conclusion we get the desired solution.
   
   The advantage of Backtracking algorithm is it is relatively easier to code and use less
   lines of code. It works step by step representing the solution to the required problem
   which is very simple interpret.

## Time Complexity ##

n | time
------------ | -------------
4 | 45.000000682193786
8 |  5.000001692678779
16 | 4.999994416721165
32 | 5.000001692678779
64 | 9.999996109399945
