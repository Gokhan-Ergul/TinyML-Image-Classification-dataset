# TinyML Image Classification Dataset

This repository contains a small image dataset prepared for training a TinyML image classification model using [Edge Impulse](https://www.edgeimpulse.com/).

## Dataset Description

The dataset includes **three classes**:

- 🗝️ `key`: Images that contain a key.
- 📦 `box`: Images that contain a box.
- ⬜ `background`: Images with no relevant object (used to improve generalization).

Each class includes approximately **30 images**, manually collected and labeled via Edge Impulse's data acquisition tools with Nicla Vision. These samples are intended for lightweight image classification tasks on embedded systems (e.g., Arduino Nicla Vision, STM32, etc.).

## Use Case

This dataset is suitable for:

- Prototyping embedded image classification models
- Experimenting with TinyML vision tasks
- Benchmarking on resource-constrained devices

## How to Use

To train a model using this dataset, visit the Edge Impulse Studio project:

🔗 [Edge Impulse Project Dashboard](https://studio.edgeimpulse.com/studio/743950)

There, you can:
- View or download the dataset
- Train your model
- Test on live devices
- Deploy to embedded hardware

## License

This dataset is for educational and research purposes. Attribution is appreciated.

---

📌 Created with ❤️ by [Gökhan Ergül](https://github.com/Gokhan-Ergul)
