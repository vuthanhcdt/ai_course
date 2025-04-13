# 🦿 Training the Humanoid Robot H1: A Reinforcement Learning Approach

Welcome to the training project for the **Unitree H1** humanoid robot! This notebook is introduced by the [Network Robotics System Laboratory (NRSL)](https://sites.google.com/site/yenchenliuncku) and leverages the powerful [MuJoCo](https://mujoco.org/) simulation environment developed by Google DeepMind.

The training is built upon the [MuJoCo Playground](https://playground.mujoco.org/) and utilizes the [MuJoCo XLA (MJX)](https://github.com/google-deepmind/mujoco/tree/main/mjx) — a JAX-based implementation of MuJoCo — enabling efficient reinforcement learning (RL) policy training within minutes using a single GPU.

🚀 **Goal:** Accelerate development and training of humanoid robots using state-of-the-art reinforcement learning techniques in a high-fidelity physics simulator.

---

## 🎥 H1 Simulation Demonstration

### 🚫 Before Training (No Policy Applied)
<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; width: 100%; max-width: 1200px; margin: auto;">
  <video style="width: 100%; height: auto;" controls autoplay loop>
    <source src="video_intro/no_policy_track.mp4.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <video style="width: 100%; height: auto;" controls autoplay loop>
    <source src="video_intro/no_policy_side.mp4.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <video style="width: 100%; height: auto;" controls autoplay loop>
    <source src="video_intro/no_policy_back.mp4.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <video style="width: 100%; height: auto;" controls autoplay loop>
    <source src="video_intro/no_policy_front.mp4.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

### ✅ After Training (Learned Locomotion Policy)
<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; width: 100%; max-width: 1200px; margin: auto;">
  <video style="width: 100%; height: auto;" controls autoplay loop>
    <source src="video_intro/video_track.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <video style="width: 100%; height: auto;" controls autoplay loop>
    <source src="video_intro/video_side.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <video style="width: 100%; height: auto;" controls autoplay loop>
    <source src="video_intro/video_back.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <video style="width: 100%; height: auto;" controls autoplay loop>
    <source src="video_intro/video_front.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

---

## ⚙️ Getting Started on Google Colab

You can quickly get started with training by running the notebook directly on Google Colab. No local installation required — just click and run!

| 💻 Colab | 📋 Description |
|---------|----------------|
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vuthanhcdt/ai_course/blob/main/humanoid_h1.ipynb) | Train the Unitree H1 humanoid robot using reinforcement learning |s

---

# 📚 Learning Resources

- [MuJoCo Official Website](https://mujoco.org/) – Multibody physics engine
- [MuJoCo Playground](https://playground.mujoco.org/) – Interactive demo environment
- [MuJoCo Playground GitHub Repo](https://github.com/google-deepmind/mujoco_playground)
- [MuJoCo XLA (MJX)](https://github.com/google-deepmind/mujoco/tree/main/mjx) – JAX-native MuJoCo for machine learning
- [Unitree H1 Robot Overview](https://www.unitree.com/h1) – Hardware specifications and real-world applications

# 🧠 Suggested Assignments / Exercises

Here are a few ways instructors can integrate this project into coursework:

- 🔧 Modify the reward function to improve stability
- 🏃‍♂️ Train for different locomotion goals (e.g., walking backward, sidestepping)
- 📈 Plot learning curves to analyze policy performance
