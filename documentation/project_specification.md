# Project specification

## Basic
### 
Degree programme: Bachelor's in Science

Documentation language: English

Project language: Python

## Main Description
###
The goal of this project is to create an AI solver for the game 2048. The program will consist of a base for the game - so it could be played with user inputs - and an AI solver.

## Data Structures and Algorithms
###
The algorithm for be used for this is the expectimax algorithm. It is a variation of the minmax algorithm, where the outcome will depend on random chance and the player's skill. In using this algorithm, the game is treated as a
two-player game: the first player being the "human"/AI who will decide what order to switch the board in, and the second player being the computer who places a tile in a possible location on the board. 

The time complexity for
expectimax is O(b^m), space complexity is O(b*m). 

The data structures in this game will be a two-dimensional array, transposition table, a heap, and more *will be updated.
