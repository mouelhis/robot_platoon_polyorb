# Distributed control of wheeled robots platoons using the middlware PolyORB

This github repository is an Ada implementation of the design approach of distributed platooning speed control presented in the paper "Distributed Object-Oriented Design of Autonomous Control Systems for Connected Vehicle Platoons" (doi : 10.1109/ICECCS.2017.32).

See the animations videos below
https://www.youtube.com/watch?v=2WHyy5Z7nv4
https://www.youtube.com/watch?v=vIlWZUfYKIY
https://www.youtube.com/watch?v=Cl-vGISxBe4

Robots are directly controlled by the Romeo All-in-One V1.3 boards enslaved by Raspberry Pi 3 cards on which a distributed software application of platooning control is deployed and executed under real-time (Preempt_RT) Linux kernels 4.4.21. The control software is based on object-oriented component-based method of design. It is implemented in the Ada language (annexes D and E of real-time and distributed systems of Ada Reference Manual). Distribution in the software is managed by the middleware PolyORB maintained by AdaCore.
