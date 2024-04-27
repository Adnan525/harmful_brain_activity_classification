# Harmful Brain Activity Classification

Classify seizures and other patterns of harmful brain activity in critically ill patients

## Development Environment
- Kaggle Notebook P100 and T4 x 2 GPU

## Submission Requirement
- No internet
- Runtime less than 9 hours
- Have to generate a probability distribution
- Evaluated using KL Divergence Loss

## Usage
Since internet is disabled, I fine-tuned and saved a Resnet34 model in a different notebook, uploaded it to Kaggle and imported the model in the submission notebook.  
[Resnet34D_hmsBrain_5E_512I](https://www.kaggle.com/models/muntasiradnan/resnet34d_hmsbrain_5e_512i)

## KL Divergence
![kl_divergence](https://github.com/Adnan525/harmful_brain_activity_classification/blob/main/kl_div.png)

## Training
![training](https://github.com/Adnan525/harmful_brain_activity_classification/blob/main/training.png)

## Loss at each epoch
![loss_epoch](https://github.com/Adnan525/harmful_brain_activity_classification/blob/main/loss_epoch.png)

## Loss
![loss](https://github.com/Adnan525/harmful_brain_activity_classification/blob/main/loss.png)

## Accuracy
![ACC](https://github.com/Adnan525/harmful_brain_activity_classification/blob/main/accuracy_test20.png)

## Kaggle Submission
![kaggle](https://github.com/Adnan525/harmful_brain_activity_classification/blob/main/kaggle_score.png)
