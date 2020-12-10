---
layout: page
title: CMCI - Composable Models for Compliant Interaction Control
---

With the advent of highly redundant robots with model-based computed
torque control, the specification of compliant behavior is
increasingly important to create interactions with humans like
cooperate pushing, carrying, walking, and with objects e.g. in
grasping, polishing, or deburring. The idea of the CMCI project is to
tackle the composition challenges that occur through the inevitable
interplay of control, sensing, and the mechanism that creates the
targeted compliant behavior, which is necessary to realize advanced
robotics systems. To this end, the project aims at providing
composable domain-specific (meta-)models to enable the specification
of compliant behavior and model-transformations to synthesize the
required motion control components, realizing the desired compliant
interaction tasks. Both, the modeling and synthesis aspects will be
realized in our workbench for modeling robot control architectures
"CoSiMA".

## Final Video
<video style="width:100%" controls="controls" preload="metadata">
  <source src="video/cmci_final.m4v#t=0.5">
  Your browser does not support the video tag.
</video>

## Replicate our Results
The language workbenches, DSLs and the embedded simulation environment are available at our [github orgranization](https://github.com/rosym-project/). To learn more about our control architecture for compliant interaction please refer to [1].

The backend is based on the OpenSoT [2] library by the Humanoids & Human Centered Mechatronics Lab at the Italian Institute of Technology (IIT). You can download Debian packages (`-dev` variant with header files) of the OpenSoT [here](#). To learn more about the specific compliant behaviour in the video you can refere to [3].

## Consortium:
- [Research institute for cognition and robotics, Universität Bielefeld](https://www.cor-lab.de/research-institute-cognition-and-robotics)
- [Institut für Robotik und Prozessinformatik, Technische Universität Braunschweig](https://www.rob.cs.tu-bs.de/)

[<img src="http://robmosys.eu/wp-content/uploads/2019/10/Siegel_TU_Braunschweig_transparent.svg_-300x111.png" height="64" />](https://www.rob.cs.tu-bs.de/)
[<img src="http://robmosys.eu/wp-content/uploads/2019/10/CoR-Lab_RGB_mit-300x119.jpg" height="64" />](https://www.cor-lab.de/research-institute-cognition-and-robotics)

## Acknowledgements

This work was supported by the European Union’s Horizon 2020 project [RobMoSys – Composable Models and Software](https://robmosys.eu/) (grant agreement No 732410).

## References
[1] D. L. Wigand, N. Dehio, and S. Wrede. *Model-Based Specification of Control Architecturesfor Compliant Interaction with the Environment*. In2020 IEEE/RSJ International Conferfence on Intelligent Robots and Systems (IROS), 2020.

[2] A. Rocchi, E. M. Hoffman, D. G. Caldwell, and N. G. Tsagarakis. *Opensot: A Whole-Body Control Library for the Compliant Humanoid Robot Coman*. In2015 IEEE InternationalConference on Robotics and Automation (ICRA), pages 6248–6253, 2015.

[3] E. M. Hoffman, A. Laurenzi, L. Muratore, N. G. Tsagarakis, and D. G. Caldwell. *Multi-Priority Cartesian Impedance Control Based on Quadratic Programming Optimization*. In2018IEEE International Conference on Robotics and Automation (ICRA), pages 309–315, 2018.
