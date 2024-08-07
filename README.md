# Handbook of Marine Craft Hydrodynamics and Motion Control

The "Handbook of Marine Craft Hydrodynamics and Motion Control" comprehensively explores cutting-edge developments in marine craft hydrodynamics and guidance, navigation, and control (GNC) systems. The text establishes how mathematical models and modern control theory can be implemented to simulate and verify control systems. 

<img src="./src/bookcover.jpg" width="170" />  &nbsp;&nbsp;&nbsp;  [Errata.pdf](./src/Errata.pdf)

ISBN: 978-1-119-57505-4

[Thor I. Fossen](https://www.ntnu.edu/employees/tif)

[John Wiley & Sons Ltd., 2nd Edition, April 2021](https://www.wiley.com/en-in/Handbook+of+Marine+Craft+Hydrodynamics+and+Motion+Control%2C+2nd+Edition-p-9781119575030)

## Lecture Material

The textbook is used in the graduate course [TTK4190 Guidance, Navigation and Control of Vehicles](https://www.ntnu.edu/studies/courses/TTK4190) at the Norwegian University of Science and Technology. Complementary slides can be downloaded below. 

| | Chapters | PDF Slides | Last Modified |
| :-: | :--- | :-: | :-: |
| | Part 1: Marine Craft Hydrodynamics |
| 1 | Introduction to Part I | [Ch1.pdf](https://www.dropbox.com/scl/fi/0t35ol7qjkbtq2y2tjtmr/Ch1.pdf?rlkey=733g820vq4vfxdn8pd9zl8xt9&dl=0)| 2024-06-17 |
| 2 | Kinematics   | [Ch2.pdf](https://www.dropbox.com/scl/fi/i7vlggjiipr8vpp6j1evo/Ch2.pdf?rlkey=w6o0au5nphl3h7y449tziior9&dl=0)| 2024-06-17  |
| 3 | Rigid-Body Kinetics | [Ch3.pdf](https://www.dropbox.com/scl/fi/szawrpaykezjodki8t3jq/Ch3.pdf?rlkey=54g895sql59x4gssoa7nextir&dl=0)| 2024-06-17  |
| 4 | Hydrostatics | [Ch4.pdf](https://www.dropbox.com/scl/fi/td0dwv4cgjxmvdg8dhtg9/Ch4.pdf?rlkey=fcbxt5sa0kh826jk783tb7mqt&dl=0)| 2024-06-21  |
| 5 | Seakeeping Models | [Ch5.pdf](https://www.dropbox.com/scl/fi/7yuix37gbad59qma3hi1x/Ch5.pdf?rlkey=zi16uwq78d418v03lh1mdtfb9&dl=0)| 2023-08-10  |
| 6 | Maneuvering Models | [Ch6.pdf](https://www.dropbox.com/scl/fi/f2ipl6gxs9a826b6i06dw/Ch6.pdf?rlkey=utqhkxv7y353rittx1dnte0fo&dl=0)| 2024-07-27  |
| 7 | Autopilot Models for Course and Heading Control | [Ch7.pdf](https://www.dropbox.com/scl/fi/rth0nv12xsrf0ar8bsbwv/Ch7.pdf?rlkey=bjpndrhdfuxzc8281fx3n2hk8&dl=0)| 2023-08-10 |
| 8 | Models for Underwater Vehicles | [Ch8.pdf](https://www.dropbox.com/scl/fi/r3ppxw8sbfy16uy0bts0f/Ch8.pdf?rlkey=uyz1kqiz10b07qg000s0jfp4f&dl=0)| 2023-08-15  |
| 9 | Control Forces and Moments | [Ch9.pdf](https://www.dropbox.com/scl/fi/ftobpq8i6ossgdfuvada0/Ch9.pdf?rlkey=yzuft1ocixxtiol9nuwohxip3&dl=0)| 2023-03-29 |
| 10 | Environmental Forces and Moments | [Ch10.pdf](https://www.dropbox.com/scl/fi/1hdy5puq6p0nzkd4bivtg/Ch10.pdf?rlkey=ro2t6otv1qfn6qg20oi0nxapr&dl=0)| 2022-06-18 |
| | Part 2: Motion Control Systems |
| 11 | Introduction to Part II | [Ch11.pdf](https://www.dropbox.com/scl/fi/sryr1340ilvjv9dpfs62t/Ch11.pdf?rlkey=grlws4qw8edl69s38dqivqfkp&dl=0)| 2021-05-20 |
| 12 | Guidance Systems | [Ch12.pdf](https://www.dropbox.com/scl/fi/mf5ms14t9pp7mfe4qgf6w/Ch12.pdf?rlkey=odw8avz86a02w8tg6wnfmvu79&dl=0)| 2023-10-27 |
| 13 | Model-Based Navigation Systems | [Ch13.pdf](https://www.dropbox.com/scl/fi/2632cq45s97fdbl8h4ihs/Ch13.pdf?rlkey=s2bpax64cwbdcas6cxxgc79gk&dl=0)| 2022-11-04 |
| 14 | Inertial Navigation Systems | [Ch14.pdf](https://www.dropbox.com/scl/fi/68ky3k4is0gahpxi3h010/Ch14.pdf?rlkey=6yq5djch0ycna9h69qz6xh4lz&dl=0)| 2023-08-01  |
| 15 | Motion Control Systems | [Ch15.pdf](https://www.dropbox.com/scl/fi/cprgdxqm7stse4ax4vhvd/Ch15.pdf?rlkey=2yy1j22adyoi7ziq571kb28ii&dl=0)| 2023-09-02 |
| 16 | Advanced Motion Control Systems | [Ch16.pdf](https://www.dropbox.com/scl/fi/3ruzu0wg28cpkxzk0a21t/Ch16.pdf?rlkey=782uj1pkucfqtnqk2logm5uxb&dl=0)| 2021-06-25  |
| | Part III: Appendices |
| A | Nonlinear Stability Theory | |
| B | Numerical Methods | |
| C | Model Transformations | |
| D | Non-dimensional Equations of Motion | |

## MSS (Marine Systems Simulator)

The Marine Systems Simulator (MSS) is a complementary Matlab and Simulink library for simulating marine systems. The m-files are compatible with the free software GNU Octave [www.octave.org](https://www.octave.org). MSS includes models for ships, Autonomous Underwater Vehicles (AUVs), Uncrewed Surface Vehicles (USVs), and floating structures. The library also contains guidance, navigation, and control (GNC) systems for time-domain simulation.  

[github.com/cybergalactic/MSS](https://github.com/cybergalactic/MSS)

<img src="./src/mss.png" width="1000"/>

## Python Vehicle Simulator

The Python Vehicle Simulator supplements the Matlab MSS (Marine Systems Simulator) toolbox. It includes models for Autonomous Underwater Vehicles (AUVs), Uncrewed Surface Vehicles (USVs), and ships. The vehicle models are based on the MSS marine craft models in the /MSS/VESSELS/ catalog. Each vehicle is modeled as an object in Python, and the vehicle class has methods for guidance, navigation, and control. The main program 'main.py' defines vehicle objects for real-time simulation.

[github.com/cybergalactic/PythonVehicleSimulator](https://github.com/cybergalactic/PythonVehicleSimulator)

<img src="./src/pythonVehicleSim.png" width="1000"/>
