# 🧠 Neural Style Transfer with TensorFlow

This project implements Neural Style Transfer using TensorFlow to blend the **content of one image** with the **style of another**. It leverages a pre-trained **VGG19** network to extract deep features from both content and style images, synthesizing a new image that artistically merges the two.

---

## 🎯 Objective

- Understand and implement Neural Style Transfer using deep feature representations
- Extract content and style using intermediate layers of a CNN (VGG19)
- Optimize an image to minimize a weighted style and content loss
- Generate aesthetically pleasing outputs using gradient-based updates

---

## 📂 Dataset

You can use **any two images** for this task:

- 🖼️ `content.jpg` — the base image whose structure/content you want to preserve  
- 🎨 `style.jpg` — the reference painting/image whose artistic style you want to apply

Upload these in your Colab or working directory. Example content-style pairs include:
- Photo + Van Gogh’s *Starry Night*
- Portrait + Picasso’s *Cubism*
- Landscape + *The Great Wave off Kanagawa*

---

## 🧪 Training Configuration

| Setting       | Value                                |
|---------------|--------------------------------------|
| Epochs        | 10–50 (adjustable)                   |
| Image Size    | Auto-scaled to max dim 512           |
| Optimizer     | Adam (`lr=0.02`)                     |
| Framework     | TensorFlow 2.x                       |
| Device        | GPU Recommended (e.g., Colab T4)     |

---

## 📈 Output

For each content-style image pair:

- 🖼️ Original Content Image
- 🎨 Reference Style Image
- 🧠 Stylized Output (Generated Image)

Output image is stored and can be visualized or saved using `matplotlib` or `PIL`.

Output Example: [![CLICK HERE](output.jpg)](download.png)

---

## 📚 References
[TensorFlow Neural Style Transfer Tutorial](https://www.tensorflow.org/tutorials/generative/style_transfer)
[Original NST Paper by Gatys et al. (2015)](https://arxiv.org/abs/1508.06576)
[VGGNet Paper (Simonyan & Zisserman, 2014)](https://arxiv.org/abs/1409.1556)

---

## ✍️ Author
Indraneal Sajjankar
