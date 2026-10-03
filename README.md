# ai-clone-demo

Replace the person in a video with a person from a photo, using Wan 2.2 Animate (GGUF) in ComfyUI on a free Kaggle T4.

1. Put `person.jpg` and `video.mp4` in `assets/`.
2. Import `wan_animate.ipynb` into Kaggle (GPU T4, Internet on) and run the cells.
3. Open the printed tunnel URL, load the `wan_animate` workflow, swap the model loader for **Unet Loader (GGUF)**, run.

Use only photos and videos you have rights to use.
