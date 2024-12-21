# self_driving_car
Self Driving Car AI using Pytorch and Kivy

Programmed and devised a self driving car AI from scratch using PyTorch & Kivy, with 4 performance levels & 90% precision.

This project focuses on simulating a self-driving car using deep learning and AI techniques. The goal was to create a model that allows a simulated car to make real-time decisions regarding steering, speed, and obstacle avoidance, based on its sensor inputs. The car's performance is optimized through reinforcement learning, achieving high levels of precision in navigation and obstacle detection.

1. Neural Network for Autonomous Control
Model: A deep learning model was developed using PyTorch to enable the car to make decisions on steering, acceleration, and braking in real time.
Input: The model processes sensor data (e.g., camera, lidar) to simulate the car's decision-making process for navigation.
Output: The model predicts steering angles and speed adjustments, ensuring smooth and autonomous operation.

2. Custom GUI with Kivy
Interactive Interface: A custom graphical user interface (GUI) was created using Kivy to visualize the car's performance and control its parameters.
User Control: The GUI allows the user to manually control the car or watch the AI take over, with real-time feedback on the car’s movements, speed, and sensor data.
Difficulty Levels: The interface supports four different levels of difficulty, adjusting the complexity of the environment and the car’s performance.

3. Reinforcement Learning Integration
Optimization: Reinforcement learning techniques were incorporated to allow the car to learn and adapt its behavior based on environmental feedback.
Performance Metrics: The car achieved 90% precision in obstacle detection and navigation, demonstrating effective learning in various driving scenarios.
Reward System: The model was trained using a reward-based system, rewarding the car for safe and efficient navigation while penalizing it for collisions or unsafe behavior.

Setup and Installation Requirements
Python 3.x
PyTorch
Kivy
OpenCV (for sensor data processing)
NumPy
Matplotlib (for data visualization)

