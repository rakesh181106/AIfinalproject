# Aircraft Damage Classification and Captioning

This project classifies aircraft surface damage as **dent** or **crack** using a VGG16-based image classifier, then uses the pretrained BLIP model to generate an image caption and summary.

## Notebook

- [`Final_Project_Completed.ipynb`](Final_Project_Completed.ipynb) — prepared notebook containing the ten assignment tasks.

## Workflow

1. Load and prepare the aircraft damage image dataset.
2. Create training, validation, and test image generators.
3. Build and train a VGG16 feature-extraction classifier.
4. Inspect the model summary and compile the model.
5. Plot training and validation accuracy for feature extraction.
6. Fine-tune selected VGG16 layers.
7. Plot fine-tuning loss and accuracy.
8. Compare predictions on a test image using both models.
9. Generate a caption and summary with BLIP.

## Ten-task submission checklist

- [ ] 1. Print the TensorFlow version.
- [ ] 2. Create the test image generator.
- [ ] 3. Print the number of training batches.
- [ ] 4. Display the model summary.
- [ ] 5. Compile the model.
- [ ] 6. Plot feature-extraction training and validation accuracy.
- [ ] 7. Plot fine-tuned training and validation loss.
- [ ] 8. Plot fine-tuned training and validation accuracy.
- [ ] 9. Display the test image and prediction using the feature-extraction model (index 1).
- [ ] 10. Display the test image and prediction using the fine-tuned model (index 1).

## Run the notebook

Open the notebook in the course JupyterLab environment and run all cells from top to bottom. Dataset/model downloads require internet access, and training and BLIP inference require adequate memory and runtime. Save the notebook after execution to preserve outputs.

## Verification status

The notebook structure and Python cell syntax were checked. **The full notebook has not yet been executed end-to-end**, so model training, plots, test predictions, and BLIP outputs still need to be verified in the target JupyterLab environment before final submission.
