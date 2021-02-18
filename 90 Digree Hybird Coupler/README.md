# 90 Degree Hybrid Coupler (branchline)

# Fast intro
There are two different types of ideal 4-port 3dB couplers:\
the symmetric solution and the anti-symmetric solution. \
The symmetric solution is called the Quadrature Hybrid. 
The Quadrature Hybrid possesses D4 symmetry—it has two planes of bilateral reflection symmetry. \
This fact leads to circuit analysis procedure that is an extension of odd-even mode analysis. \
Instead of 2 modes (odd-even), the circuit can be expressed as a superposition of 4 modes \

The 90D Hybrid Coupler is a 4-port device, otherwise known as the quadrature coupler or branch-line coupler. \
Its scattering matrix (ideally) has the symmetric solution for a matched, lossless, reciprocal 4-port device: 

<img width="590" alt="image" src="https://user-images.githubusercontent.com/66625688/84611540-310fe080-ae8c-11ea-8b24-a4da81781561.png">

the ports  are matched and the device is lossless.  Note also, that if a signal is incident on one port only, then there will be a port from which no power will exit (i.e., an isolation port). \
Unlike the directional coupler, the power that is flows into the input port will be evenly divided between the two non-isolated ports \
For example, if 10 mW is incident on port 3 (and all other ports are matched), then 5 mW will flow out of both port 1 and port 4, while no power will  exit port 2 (the isolated port \
Note however, that the although the magnitudes of the signals leaving ports 1 and 4 are equal, the relative phase of the two signals are separated by 90 degrees (ejπ2 =j).  \
There are many useful applications where we require both the sine and cosine of a signalm especially in Radar Engineering and communication theory. \

<img width="519" alt="image" src="https://user-images.githubusercontent.com/66625688/84611677-8d730000-ae8c-11ea-9e8c-ff5da8580174.png">


# The project
Design a 90 digree Hybird coupler using Microstrip lines on a RT5880 substrate (20 mil thick ) 
- Center Frequency 10 Ghz
- Show coupling Ratio
- show phase differance between the two coupling ports

# Curcuit and Results

<img width="838" alt="capture2-1" src="https://user-images.githubusercontent.com/66625688/84611934-2144cc00-ae8d-11ea-90b6-4da049f0f73d.png">


<img width="999" alt="capture" src="https://user-images.githubusercontent.com/66625688/84611961-39b4e680-ae8d-11ea-90e4-da9e3a4102a7.png">


<img width="787" alt="capture1-1" src="https://user-images.githubusercontent.com/66625688/84611979-446f7b80-ae8d-11ea-95e7-776c79a545d1.png">


<img width="691" alt="capture3-1" src="https://user-images.githubusercontent.com/66625688/84612031-60731d00-ae8d-11ea-8448-1cd8fe45cca5.png">




