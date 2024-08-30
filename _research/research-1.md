---
title: "Multi-Robot Formation Control"
excerpt: "Driving agents to form shapes described by parametric curves.<br/><br><img src='/images/research/research1.png' width='500' height='600'>"
collection: research
---

The automatic monitoring/tracking of environmental boundaries by multi-agent systems is a fundamental problem that has many practical applications. 
In this project, we addressed this problem with formation control techniques based on parametric curves that represent the boundary's feedback shape. 
We first considered the closed evolving boundaries and employed a multi-agent system with directed inter-agent communications to form the boundaries.
For that, we approximate the curve with truncated Fourier series, whose finite coefficients are utilized to characterize the curve's shape and to automatically distribute the agents along it. 
These feedback Fourier coefficients are exploited to design a new type of formation controller that drives the agents to form desired curves. 
A detailed stability analysis is provided for the proposed control methodology, considering both fixed and switching multi-agent topologies.
The reported numerical simulation and experimental studies demonstrate the performance and feasibility of our new method to track closed boundaries of different shapes. 
<br>
<iframe src="https://player.vimeo.com/video/809466573?h=ec7386dd99" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>
<br>
Next, we extended the previous method to more general cases where both open and closed curves were considered.
First, we derive a unified parametric representation for both open and closed curves.
Then, a leader-follower formation controller is designed to drive agents to form the desired parametric curves using the curve coefficients as feedbacks.
We consider directed communications and constant input disturbances rejection in the controller design.
Rigorous Lyapunov-based stability analysis proves the asymptotic stability of the proposed controller.
The convergence of the orientations of agents to some constant values is also guaranteed.
The method has the potential to be extended to deal with various real-world applications, such as object enclosing.
Detailed numerical simulations and experimental studies are conducted to verify the performance of the proposed method.
<br>
<iframe src="https://player.vimeo.com/video/872927697?h=6bdd362b3f" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>
<br>
Related publications:

* **B. Zhang**, H. Zhi, J. G. Romero, L. Labazanova, A. Duan, X. Li, and D. Navarro-Alarcon, "Fourier-Based Multi-Agent Formation Control to Track Evolving Closed Boundaries," in *IEEE Transactions on Circuits and Systems I: Regular Papers (T-CAS-I)*, vol. 70, no. 11, pp. 4549-4559, Nov. 2023, doi: [10.1109/TCSI.2023.3300772](https://doi.org/10.1109/TCSI.2023.3300772). ([PDF](http://zbC137.github.io/files/papers/TCAS1_2023.pdf), [Video](https://vimeo.com/809466573))

* **B. Zhang**, X. Shao, H. Zhi, L. Qiu, J. G. Romero, and D. Navarro-Alarcon, "Leader-Follower Formation Control of Perturbed Nonholonomic Agents along Parametric Curves with Directed Communication," in *IEEE Robotics and Automation Letters (RA-L)*, Aug. 2024 (Early Access). doi:[10.1109/LRA.2024.3445657](https://doi.org/10.1109/LRA.2024.3445657). ([PDF](http://zbC137.github.io/files/papers/RAL_2024.pdf), [Video](https://vimeo.com/872927697))

