# Reinforcement Learning for Locomotion Control

This section covers the application of reinforcement learning to locomotion control in robotics. Reinforcement learning is a branch of machine learning where an agent learns optimal behaviors through interactions with its environment and feedback in the form of rewards or penalties. In robotics, this approach is used to refine movement strategies, much like the trial-and-error processes observed in biological motor learning.

## Overview

Below is a preliminary list academic papers that discuss reinforcement learning in the context of locomotion control. This list will be expanded and refined as additional resources become available.

**2024**

1. **Agile But Safe: Learning Collision-Free High-Speed Legged Locomotion**
    *  **Authors:** Tairan Helt, Chong Zhang, Wenli Xiao, Guanqi He, Changliu Liu, Guanya Shi
    *  **Published:** May, 2024
    *  **Institutions:** Carnegie Mellon University, ETH Zürich
    *  **Link:** [https://agile-but-safe.github.io](https://agile-but-safe.github.io)
    *  **Code:** [https://github.com/LeCAR-Lab/ABS](https://github.com/LeCAR-Lab/ABS)
    *  **PDF:** [papers/agile_but_safe.pdf](papers/agile_but_safe.pdf)

2. **Dual-Layer Reinforcement Learning for Quadruped Robot Locomotion and Speed Control in Complex Environments**
    *  **Authors:** Yilin Zhang, Jiayu Zeng, Huimin Sun, Honglin Sun, Kenji Hashimoto
    *  **Published:** Sep, 2024
    *  **PDF:** [papers/dual_layer_rl.pdf](papers/dual_layer_rl.pdf)

3. **RL2AC: Reinforcement Learning-Based Rapid Online Adaptive Control for Legged Robot Robust Locomotion**
    *  **Authors:** Shangke Lyu, Xin Lang, Han Zhao, Hongyin Zhang, Pengxiang Ding, Donglin Wang
    *  **Institutions:** Machine Intelligence Lab (MiLAB), School of Engineering, Westlake University
    *  **Published:** 2024
    *  **PDF:** [papers/rl_2_ac.pdf](papers/rl_2_ac.pdf)

4. **Full-Order Sampling-Based MPC for Torque-Level Locomotion Control via Diffusion-Style Annealing**
    *  **Authors:** Haoru Xue, Chaoyi Pan, Zeji Yi, Guannan Qu, Guanya Shi
    *  **Published:** Sep, 2024
    *  **Code:** [https://github.com/LeCAR-Lab/dial-mpc](https://github.com/LeCAR-Lab/dial-mpc)
    *  **PDF:** [papers/dial_mpc_paper.pdf](papers/dial_mpc_paper.pdf)

5. **Reinforcement Learning For Quadrupedal Locomotion: Current Advancements And Future Perspectives**
    *  **Authors:** Maurya Gurram, Prakash Kumar Uttam, Dr. Shantipal S. Ohol
    *  **Published:** Oct, 2024
    *  **PDF:** [papers/rl_ql_caf.pdf](papers/rl_ql_caf.pdf)

6. **An Advanced Reinforcement Learning Control Method for Quadruped Robots in Typical Urban Terrains**
    *  **Authors:** Chi Yan, Ning Wang, Hongbo Gao, Xinmiao Wang, Chao Tang, Lin Zhou, Yuehua Li, Yue Wang 
    *  **Published:** Dec, 2024
    *  **Link:** [https://link.springer.com/article/10.1007/s13042-024-02478-9](https://link.springer.com/article/10.1007/s13042-024-02478-9)

**2023**

7. **Robot Parkour Learning**
    *  **Authors:** Ziwen Zhuang, Zipeng Fu, Jianren Wang, Christopher Atkeson, Sören Schwertfeger, Chelsea Finn, Hang Zhao
    *  **Published:** 2023
    *  **Institutions:** Shanghai Qi Zhi Institute, Stanford University
    *  **Link:** [https://robot-parkour.github.io/](https://robot-parkour.github.io/)
    *  **PDF:** [papers/parkour.pdf](papers/parkour.pdf)

8. **Extreme Parkour with Legged Robots**
    *  **Authors:** Xuxin Cheng, Kexin Shi, Ananye Agarwal1, Deepak Pathak1
    *  **Published:** 2023
    *  **Institutions:** Carnegie Mellon University, University of Zurich
    *  **Link:** [https://extreme-parkour.github.io/](https://extreme-parkour.github.io/)
    *  **PDF:** [papers/extreme_parkour.pdf](papers/extreme_parkour.pdf)

9. **RL + Model-based Control: Using On-demand Optimal Control to Learn Versatile Legged Locomotion**
    *  **Authors:** Dongho Kang, Jin Cheng, Miguel Zamora, Fatemeh Zargarbashi, Stelian Coros
    *  **Published:** May, 2023
    *  **Institutions:** CRL, ETH Zürich
    *  **Link:** [https://donghok.me/rl-plus-model-based-control/](https://donghok.me/rl-plus-model-based-control/)
    *  **PDF:** [papers/rl_plus_mpc.pdf](papers/rl_plus_mpc.pdf)

10. **SayTap: Language to Quadrupedal Locomotion**
    *  **Authors:** Yujin Tang, Heiga Zen, Wenhao Yu, Aleksandra Faust, Jie Tan, Tatsuya Harada
    *  **Published:** Sep, 2023
    *  **Institutions:** Google DeepMind, The University of Tokyo
    *  **Link:** [https://saytap.github.io/](https://saytap.github.io/)
    *  **PDF:** [papers/say_tap.pdf](papers/say_tap.pdf)

11. **One Policy to Run Them All: an End-to-end Learning Approach to Multi-Embodiment Locomotion**
    *  **Authors:** Nico Bohlinger, Grzegorz Czechmanowski, Maciej Krupka, Piotr Kicki, Krzysztof Walas, Jan Peters, Davide Tateo
    *  **Published:** 2023
    *  **Link:** [https://nico-bohlinger.github.io/one_policy_to_run_them_all_website/](https://nico-bohlinger.github.io/one_policy_to_run_them_all_website/)
    *  **PDF:** [papers/one_policy_to_run_them_all.pdf](papers/one_policy_to_run_them_all.pdf)

12. **Learning Multiple-Gait Quadrupedal Locomotion via Hierarchical Reinforcement Learning**
    *  **Authors:** Lang Wei, Yunxiang Li, Yunfei Ai, Yuze Wu, Hao Xu, Wei Wang, Guoming Hu 
    *  **Published:** 2023
    *  **Link:** [https://link.springer.com/article/10.1007/s12541-023-00885-6](https://link.springer.com/article/10.1007/s12541-023-00885-6)

**2022 and earlier**

1.  **DayDreamer: World Models for Physical Robot Learning**
    *  **Authors:** Alejandro Escontrela, Danijar Hafner, Philipp Wu, Ken Goldberg, Pieter Abbeel
    *  **Published:** Jun, 2022
    *  **Institutions:** University of California, Berkeley
    *  **Link:** [https://danijar.com/project/daydreamer/](https://danijar.com/project/daydreamer/)
    *  **PDF:** [papers/day_dreamer.pdf](papers/day_dreamer.pdf)

2.  **Learning the Quadruped Robot by Reinforcement Learning (RL)**
    *  **Authors:** A. A. Issa, A. A. Aldair
    *  **Published:** 2022
    *  **PDF:** [papers/lq_rl.pdf](papers/lq_rl.pdf)

3.  **Learning Quadrupedal Locomotion over Challenging Terrain**
    *  **Authors:** Joonho Lee, Jemin Hwangbo, Lorenz Wellhausen, Vladlen Koltun, Marco Hutter
    *  **Published:** Oct, 2020
    *  **Institutions:** ETH Zurich, KAIST, Intel
    *  **Link:** [https://leggedrobotics.github.io/rl-blindloco/](https://leggedrobotics.github.io/rl-blindloco/)
    *  **PDF:** [papers/challenging_terrain.pdf](papers/challenging_terrain.pdf)


Contributions to improve or expand this list are welcome.
