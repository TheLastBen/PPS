# Fast Stable Diffusion

[![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)](https://console.paperspace.com/github/TheLastBen/PPS?machine=Free-GPU)

## Run these notebooks with Paperspace Gradient

To run these notebooks in Gradient on a Free GPU, click the Run on Gradient above or follow the instructions below.

- Log in to your [Paperspace account](https://console.paperspace.com)
- Open a Project of your choice, or create a new one, in a Team of your choice
- Select the "Create" button. The button can be found in the center of the web page in an empty Project, and the top right of the page in a project with existing Notebooks
- In the Create Notebook page, scroll down to the "Select a machine" section, and select a Free GPU machine. You can also select a more powerful machine, like the A100-80G or A6000, if you want to generate images more quickly or if the Free GPU machines are unavailable. Learn more about our GPU offerings [here](https://docs.paperspace.com/gradient/machines/)
- Scroll down to the "Advanced options" section, and click the toggle next to the text.
- In the newly opened dropdown, navigate to the advanced options section and paste this URL https://github.com/TheLastBen/PPS in the field labeled "Workspace URL"
- Click "Start Notebook" at the bottom left of the screen to open the Fast Stable Diffusion Paperspace repo in a Gradient Notebook

## This repository includes

- **PPS-A1111.ipynb**: this notebook facilitates a quick and easy means to access the Automatic1111 Stable Diffusion Web UI. Simply click run all at the top of the screen to get a link to the web app. Additionally, you may change the default model/path, and set a username and password for the session.
- **PPS-Dreambooth-v1.ipynb && PPS-Dreambooth-v2.ipynb**: these notebooks makes it easy to quickly train a Dreambooth checkpoint on any images. This method makes it simple to directly upload and caption your own images via the upload modal. Alternatively, users may paste the path to an uploaded directory of images on the instance.
  **NOTE** The Dreambooth notebook's upload button is currently blocked in the Gradient Notebook GUI. To use the uploader, select the Jupyter Lab button using the left-hand sidebar to open your instance in Jupyter Labs, and re-run the notebook code.)

Credits & tips:

Dreambooth paper: https://dreambooth.github.io/

SD implementation by @XavierXiao: https://github.com/XavierXiao/Dreambooth-Stable-Diffusion
