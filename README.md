## nd608 - AI Photo Editing With Inpainting

### Introduction

This is repo contains my implementation for Udacity's Generative AI Nanodregree "AI Photo Editing With Inpainting" project. I've copied and modified the [`starter.ipynb`](Udacity-Provided-Workspace/Computer-Vision-and-Generative-AI-Project/starter/starter.ipynb) to remove the instructions. I also had to
modify the [`app`](Udacity-Provided-Workspace/Computer-Vision-and-Generative-AI-Project/starter/app.py) module to adapt it to a newer version of `gradio`. I used two of my own images to test the infilling app.

I've also included `poetry` project specs to run project outside of Udacity's workspace.

### Contents

| File/Folder | Description |
|-------------|-------------|
| [`Udacity-Provided-Workspace`](Udacity-Provided-Workspace) | Contents of Udacity's provided workspace as-is. |
| [`AI-Photo-Editing-with-Inpainting.ipynb`](AI-Photo-Editing-with-Inpainting.ipynb) | Jupyter notebook with the project submission. |
| [`AI-Photo-Editing-with-Inpainting.html`](AI-Photo-Editing-with-Inpainting.html) | HTML version Jupyter notebook with the project submission. |
| [`IMG_20140501_232805.jpg`](IMG_20140501_232805.jpg) | Picture of a cat to test the infilling app. |
| [`PXL_20220510_002823589.jpg`](PXL_20220510_002823589.jpg) | Picture of a famous vehicle to test the infilling app. |
| [`cat_step1.png`](cat_step1.png) | Screenshot loading the picture of the cat. |
| [`cat_step2.png`](cat_step2.png) | Screenshot generating a mask of the cat. |
| [`cat_step3.png`](cat_step3.png) | Screenshot infilling the cat's background. |
| [`cat_step4.png`](cat_step4.png) | Screenshot infilling the cat itself. |
| [`van_step1.png`](van_step1.png) | Screenshot loading a picture of the van. |
| [`van_step2.png`](van_step2.png) | Screenshot generating the mask of the van. |
| [`van_step3.png`](van_step3.png) | Screenshot generating the mask of the van with a second point. |
| [`van_step4.png`](van_step4.png) | Screenshot generating the mask of the van with a third point. |
| [`van_step5.png`](van_step5.png) | Screenshot infilling the van's background. |
| [`van_step6.png`](van_step6.png) | Screenshot infilling the van itself. |
| [`pyproject.toml`](pyproject.toml) | `poetry` project spec file. |
| [`poetry.lock`](poetry.lock) | `poetry` dependencies lock file. |