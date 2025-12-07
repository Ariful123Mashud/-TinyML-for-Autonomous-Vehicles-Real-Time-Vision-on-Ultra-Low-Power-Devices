# -TinyML-for-Autonomous-Vehicles-Real-Time-Vision-on-Ultra-Low-Power-Devices

🚗💡 TinyML for Autonomous Vehicles: Real-Time Vision on Ultra-Low-Power Devices

Excited to share my latest project: deploying a fully quantized, real-time computer vision model on an embedded device using TensorFlow Lite, with direct applications in autonomous vehicles and edge-based perception systems.

Using the CIFAR-10 dataset, I trained a compact CNN, achieved competitive accuracy, and then compressed the model from several MB down to ~130 KB using full INT8 quantization—making it efficient enough for deployment on Arduino-class microcontrollers and other resource-constrained hardware.

🔧 Key Features

✨ Real-time inference on live camera input (OpenCV + TFLite)

 ✨ INT8 fully quantized model for low latency, low memory footprint

 ✨ 32×32 low-resolution object detection pipeline, ideal for tasks where speed > complexity

 ✨ Optimized for Edge AI and TinyML deployments

🚘 Why It Matters for Autonomous Vehicles

Future autonomous systems will increasingly rely on distributed intelligence, where small, low-power microcontrollers preprocess sensor data before handing it off to central compute units.

This project demonstrates how:

 🔹 Object classification can run directly on microcontrollers, reducing bandwidth and latency

 🔹 Edge-level perception improves reliability when connectivity or compute is limited

 🔹 Systems become safer through local fallback/backup vision models

 🔹 Energy-efficient sensing extends battery life in EV and UAV platforms

Imagine an autonomous vehicle where:

Small edge nodes identify obstacles at the sensor level

Low-resolution classifiers act as health monitors for cameras

Redundant TinyML models provide safety in case of main GPU/CPU failure

This kind of architecture is critical for next-generation autonomous vehicles, drones, and robots.

📦 Outputs

📉 Training + validation accuracy visualization

 📈 ~130 KB TFLite model ready for Arduino deployment

 🎥 Real-time webcam demo with top-3 predictions

 ⚡ Inference in just a few milliseconds

🧠 Tech Stack

TensorFlow • TensorFlow Lite • TinyML • OpenCV • Python • Embedded Vision • Edge AI

If you're interested in autonomous systems, embedded ML, or real-time perception, I’d love to connect and discuss these technologies further! 🚀

#TinyML #EdgeAI #AutonomousVehicles #DeepLearning #ComputerVision #MachineLearning #EmbeddedSystems #AIonMicrocontrollers #MLOps #AIEngineering




Included files
1) Python code 
2) Live Demo videography.
2) hex-file to deploy this project on micrcontrollers.
