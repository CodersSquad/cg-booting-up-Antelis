[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/swKMSSMl)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16850690&assignment_repo_type=AssignmentRepo)
# Computer Graphics Booting Up

## Let's start with ModernGL

This lab stands to prepare the moderngl development environment. Below the steps and requirements for initial coding tasks. Please make sure to edit the python provided files; for dependencies, you can add the files you need.

1. Install moderngl and its dependencies
2. Make sure that the following programs run
    - [`01_hello_world.py`](./01_hello_world.py)
    - [`06_multiple_objects.py`](./06_multiple_objects.py)
    - [`09_models_and_images.py`](./09_models_and_images.py)
        - _Modify this program to change the box's texture to a correctly aligned TEC logo_
3. Document how to execute the 3 programs in the section below.

* For documentation and missing dependencies, follow these links:
    - https://github.com/moderngl/moderngl
    - https://moderngl.readthedocs.io/

## How to run your program

```
#First step
    1. Clone the repository from the github classroom
    2. Installing modernGL
        a. pip install moderngl
```

```
#Hello world
    1. pip install pygame
    2. run python .\01_hello_world.py
    3. If everything is fine we should see the colourful square changing colours :D
```
```
#Multiple objects
    1. pip install pyglm
    2. run python .\06_multiple_objects.py
    3. If everything is fine we should see the colourful triangles changing colours and rotating :D
```
```
#Models and images
    1. pip install objloader
    2. Install a tec image logo from the internet
    3. Install from the github moderngl repository the following files to our folder: 
        - lowpoly_toy_car.obj
        - crate.obj
    4. add the logo to line 109 as ImageTexture(tec.png)
    5. add toy car object to line 112 ModelGeometry('lowpoly_toy_car.obj')
    6. Same with line 115 to crate object. ModelGeometry('crate.obj')
    7. run python .\09_models_and_images.py
    8. To rotate the tec logo to succesfully be the correct side up, change line 82 and make it negative, so its rotated
    8. If everything is working then we should see two cars rotating around a tec logo :D
```
```

## Grading Policy

- 25% - `01_hello_world.py` is running with no errors
- 25% - `06_multiple_objects.py` is running with no errors
- 25% - `09_models_and_images.py` is running with the requested change (TEC logo texture)
- 25% - Documentation on how to run your programs
