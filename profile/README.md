# 🤖 Droid · formerly Open Droids

<img src="https://github.com/Open-Droids-robot/.github/blob/0288ee99cef87920cae03fc10852bbca988aefd0/assets/open_droids_logo.jpg" alt="OpenDroids Logo" width="150"/>

> **"Skillnet > Skynet"** — We believe that community-driven development can prevent closed, monopolistic AI systems and create a future where robotics serves humanity, not the other way around.

Welcome to **OpenDroids**, where we're not just building robots—we're architecting the very foundation of tomorrow's automated world. We are a passionate collective of innovators, engineers, and visionaries dedicated to revolutionizing robotics through the transformative power of open-source collaboration.

---

## Start building with R2D3

Droid, formerly Open Droids, publishes robotics software here. Visit [droid.org](https://droid.org/) for the current company and platform overview.

For developers, [R2D3_ros2](https://github.com/Open-Droids-robot/R2D3_ros2) is the ROS 2 Jazzy workspace for the dual-arm mobile manipulator. Its maintained README starts with simulation and provides separate hardware instructions.

| You want to… | Start here |
|---|---|
| Run the container-based simulation | [R2D3 README: quick start](https://github.com/Open-Droids-robot/R2D3_ros2#-quick-start-simulation-in-a-container) |
| Understand container setup and platform requirements | [Container guide](https://github.com/Open-Droids-robot/R2D3_ros2/blob/main/docs/container.md) |
| Use Gazebo Harmonic | [Gazebo quick start](https://github.com/Open-Droids-robot/R2D3_ros2/blob/main/simulation_quickstart_gz.md) |
| Use MuJoCo | [MuJoCo quick start](https://github.com/Open-Droids-robot/R2D3_ros2/blob/main/simulation_quickstart_mujoco.md) |
| Check usage and redistribution terms | [R2D3 Apache-2.0 license](https://github.com/Open-Droids-robot/R2D3_ros2/blob/main/LICENSE) |

The repository documents this container entry point:

```bash
git clone https://github.com/Open-Droids-robot/R2D3_ros2.git
cd R2D3_ros2
./droid up
```

Read the current container guide for Docker and platform requirements. The README describes a CPU rendering fallback on machines without a supported GPU; performance depends on the host. For physical hardware, follow the repository's model-specific configuration and bring-up instructions.

### Make a useful contribution

Documentation fixes, reproducible simulation bug reports and focused code changes help other builders get started. Before opening an issue, check the repository's existing issues and instructions. Include the commit you tested, your OS/CPU, simulator, exact command, expected and observed behavior, and relevant logs with credentials or private data removed. Say whether the result came from simulation or physical hardware.

---

## 🌟 Our Vision: The Future is Open

Imagine a world where advanced robotics isn't locked behind corporate walls or proprietary systems. A world where anyone—from a curious student to a startup founder—can access, modify, and contribute to cutting-edge robotic technologies. This isn't just our dream; it's our mission.

At OpenDroids, we envision a future where every innovator has access to world-class robotic platforms, every community can customize robots for their unique needs, every breakthrough is shared openly for the benefit of all humanity, and every robot is built on transparent, trustworthy foundations.

We're crafting the infrastructure of tomorrow with our vision of open-source robotics—because the future belongs to everyone, not just a select few.

---

## 🚀 What We're Building: The Next Generation of Robotics

We're creating revolutionary robotic platforms that embody the spirit of open innovation. Our **R2D3 Dual-Arm Platform** serves as our flagship system, capable of folding laundry, washing dishes, serving customers, and adapting to countless other tasks. Built entirely on open-source principles, it's designed to be extended, modified, and improved by our global community.

Complementing this is our **R1D1, R1D2, R1D3 Single-Arm Platform**, a versatile solution perfect for precision tasks across manufacturing and healthcare applications. Every component is open-source, every line of code is transparent.

These platforms represent more than just hardware—they're complete ecosystems powered by AI-driven intelligence, featuring machine learning capabilities, real-time perception, and intelligent control systems. Built on ROS 2 foundations, they're fully customizable and industry-ready, spanning applications from homes to healthcare, hospitality, and manufacturing.

---

## 🌍 Why Open Source? The Foundation of Our Future

Open-source robotics isn't just a development methodology—it's a revolutionary approach that's reshaping how we build the future. By making robotic designs and software freely available, we eliminate the financial constraints that prevent brilliant minds from contributing to robotics. A worldwide community of developers, researchers, and enthusiasts can contribute their unique perspectives and expertise, accelerating innovation and turning months of development into weeks of collaborative breakthroughs.

Every algorithm, every design decision, every line of code is open for inspection and improvement. This complete visibility ensures that ethical considerations are built into the foundation, not added as an afterthought. Open-source robotics becomes a powerful tool for teaching the next generation of roboticists while fostering trust through transparency.

The combined knowledge of thousands of contributors far exceeds what any single organization can achieve. Open platforms enable solutions for problems we haven't even imagined yet, while shared development costs make advanced robotics accessible to startups, researchers, and developing nations.

### 🏆 **Inspiring Open Source Success Stories**

We've seen this transformative power before:

- **Linux** — From a student project to the foundation of the internet, powering everything from smartphones to supercomputers
- **Arduino** — Democratized electronics development, enabling millions of makers worldwide to bring their ideas to life  
- **ROS** — Became the standard framework for robotics research across academia and industry
- **TensorFlow** — Google's open-source machine learning platform accelerated AI development globally
- **OpenCV** — The computer vision library that powers everything from autonomous vehicles to medical imaging

These aren't just success stories—they're proof that open-source development creates lasting, positive change.

---

## ⚡ The Bigger Picture: Why Robotics Must Not Be Controlled by One Entity

Imagine a future where a single corporation controls all advanced robotics. This dystopian scenario would lead to monopolistic control dictating the pace and direction of robotic development, innovation constrained by corporate interests rather than human needs, and technologies held back to maximize profits rather than benefit society.

Economic inequality would follow, with only the wealthy able to afford advanced robotic solutions, potential mass unemployment without community-driven solutions, and pricing and availability controlled by corporate interests. Ethical concerns would mount as centralized systems enable unprecedented surveillance, single-source AI systems perpetuate and amplify societal biases, and critical decisions affecting millions lack community oversight.

### 🌟 **Our Solution: Decentralized, Community-Driven Robotics**

By championing open-source robotics, we're building a future where:

- **Community Governance** — Decisions about robotic development are made by the community, for the community
- **Shared Benefits** — Advancements benefit everyone, not just shareholders  
- **Distributed Innovation** — Breakthroughs can come from anywhere in the world
- **Affordable Solutions** — Open-source development dramatically reduces costs
- **Local Adaptation** — Communities can customize robots for their specific needs and cultures
- **Educational Empowerment** — Open platforms become powerful tools for learning and teaching
- **Transparent Development** — Every decision is open for community review and discussion
- **Inclusive Design** — Diverse perspectives ensure robots serve all of humanity
- **Accountable Systems** — Community oversight ensures responsible development

---

## 🛠️ Our Technology Stack: Built for the Future

Our platforms are built on cutting-edge technology that ensures both performance and accessibility. We leverage **ROS 2** as our next-generation robot operating system, combined with **MoveIt!2** for advanced motion planning and manipulation. Our development environment includes **Gazebo** for high-fidelity robot simulation, **RViz** for 3D visualization and debugging, **Docker** for containerized development environments, and **GitHub Actions** for automated testing and deployment.

### **Software Foundation**
- **C++** — High-performance robotics applications
- **Python** — Rapid prototyping and AI integration  
- **TensorFlow & PyTorch** — Machine learning and neural networks
- **OpenCV** — Computer vision and image processing

### **Hardware Platform**
- **NVIDIA Jetson** — Edge AI computing power
- **LiDAR & RGB-D Cameras** — Advanced perception systems
- **IMUs & Microphones** — Multi-modal sensor fusion
- **Custom Manipulators** — Purpose-built robotic arms

### **AI Capabilities**
- **Computer Vision** — Real-time object recognition and tracking
- **Natural Language Processing** — Human-robot communication
- **Speech Recognition** — Voice command processing
- **Collision-Safe Autonomy** — Safe operation in dynamic environments

---

## 🌟 Join the Revolution: Be Part of the Future

The future of robotics is being written right now, and you have the power to help shape it. Whether you're a developer looking to contribute code and help build the next generation of robotic software, a researcher seeking access to cutting-edge platforms for your projects, an entrepreneur wanting to build commercial applications on our open-source foundation, or a student eager to learn through hands-on experience with real robotic systems—there's a place for you in our community.

### **How You Can Contribute**

- **🔧 Developers & Engineers** — Contribute code, design hardware, improve AI algorithms, and share knowledge
- **🔬 Researchers & Academics** — Access cutting-edge platforms, publish open research, collaborate globally, mentor students
- **🚀 Entrepreneurs & Startups** — Build commercial applications, reduce development costs, access global talent, scale rapidly
- **🎓 Students & Enthusiasts** — Learn by doing, join our community, contribute fresh ideas, build your future

We're not just building robots—we're building the foundation of tomorrow's world. Every line of code we write, every design we share, every breakthrough we achieve brings us closer to a future where advanced robotics serves all of humanity.

The question isn't whether robots will transform our world—it's whether that transformation will be controlled by a few or shaped by everyone. At OpenDroids, we choose everyone.

---

## 🌐 Connect With Our Global Community

Join our worldwide movement of innovators, dreamers, and builders:

- 🌐 **Website** — [www.opendroids.com](https://www.opendroids.com)
- 💼 **LinkedIn** — [OpenDroids](https://www.linkedin.com/company/open-droids/)
- 🐦 **Twitter/X** — [@open_droids](https://x.com/open_droids)
- ▶️ **YouTube** — [OpenDroids Channel](https://www.youtube.com/@opendroids)
- 📧 **Email** — [contact@opendroids.com](mailto:contact@opendroids.com)
- 💬 **Discord** — Join our community discussions

---

## 🚀 The Future Starts Now

We're not just building robots—we're building the foundation of tomorrow's world. Every line of code we write, every design we share, every breakthrough we achieve brings us closer to a future where advanced robotics serves all of humanity.

**The question isn't whether robots will transform our world—it's whether that transformation will be controlled by a few or shaped by everyone.**

At OpenDroids, we choose everyone.

**Join us. Build the future. Make it open.**

---

*Together, we can forge the infrastructure of tomorrow with our vision of open-source robotics. The future is open—let's build it together!*

**Skillnet > Skynet. Always.**