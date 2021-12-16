# Fire Detection API Project Challenges

In this project, you'll be tasked with designing and developing a neural network that can run in production as a basic image classifier.

To get full credit on this project, you'll have to accomplish at least three major objectives:

- Create a functioning CNN-based image classifier model that works with Fire Detection images.
- Deploy your best performant classifier online and test it with sample image uploads.
- Finish all required objectives throughout the `project/development.ipynb` notebook and this current `PROJECT.md` file.

---

For the sake of clarity, all objectives (both required and bonus) will be identified per subdirectory and file.

## 📍 REQUIRED OBJECTIVES 📍

1. Fork and clone a copy of this project repository to your local environment – you'll be using classic Jupyter rather than Colab to finish this project.

2. Save a copy of the `Fire-Detection-Image-Dataset` data **[found here](https://github.com/UPstartDeveloper/Fire-Detection-Image-Dataset)** to a project subfolder called `dataset/`.

3. Work through the `project/development.ipynb` notebook, solving all required objectives to ensure successful utility of your neural network architectures.

To get full credit for completing this notebook, ensure you meet the following objectives:

- Full completion of all required objectives across the notebook.
- Save your model summary as a screenshot and place it within your project subfolder.
- **Attempt at least THREE hyperparameter changes and tuning efforts across your CNN architecture. These can include the following:**
  - Different optimizers.
  - Different hyperparameters.
  - New layers.
  - Changes to layering structure.

More points and potential bonus points will be awarded for more creative changes to their model!

4. At the end of the `project/development.ipynb` notebook, be sure to **save your models** using the provided model saving functions.

5. Upload your changes to a new Git repository and **create a new release**. (Don't worry: your model states and dataset should automatically be ignored as long as you followed the correct repository workflow.)

6. After creating a new project release, go to `app/config.yaml` and modify the `model_file_paths`, `base_model_url`, and `model_sha256` parameters.

- The `model_file_paths` arguments should be the corresponding filename(s) of your saved model states from the final saving function of the development notebook.

- The `base_model_url` argument should be your precise GitHub URL for the current project release download version.

- The `model_sha256` argument should be a SHA-256 hash that you can get by going to your project releases and clicking on the seven-digit pre-hash key below the release version tag.

7. Run your project locally and upload a test image to attain accuracy calculation. (NOTE: Follow the `README.md` instructions on **"using a virtual environment"**.)

8. Take a screenshot of that and place it within your project subfolder for full project completion.

Your final project subfolder should contain the following files:

- development.ipynb
- PROJECT.md
- model_summary.png
- model_deployed.png

## ⚡️ BONUS OBJECTIVES ⚡️

- Add additional badges to your GitHub repository to make your project upload more unique! [+2]

- Deploy your project on Heroku instead of having it locally hosted! [+5]

- Create an alternate CNN model using the `ResNet50` model and compare results! [+10]

- **MAJOR CHALLENGE**: Try repeating this same project with a new image dataset and modify all configurations as needed. [+20]
