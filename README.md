# Biologically Plausible NN Learning Rules
Reserach project for Neuromatch Academy's NeuroAI Coursework

### Project Overview
This project investigates potential modifications for control theory-based learning algorithms and architectures to optimize neural networks for more biologically plausible learning rules, such as Hebbian learning rules. We aim to determine if Hebbian-style learning rules can achieve comparable performance to backpropagation on classification tasks and identify what modifications may be needed to make them effective.

### Research Focus
We will explore the following aspects:

1. Comparison of Learning Algorithms:

    - Evaluate Hebbian learning and backpropagation on simple image classification tasks.
    - Assess performance on noisy/adversarial image classification tasks.

2. Modifications to Hebbian Learning:

    - Investigate the effect of output clamping and layer-specific learning rates.
    - Explore combinations of Hebbian learning with error backpropagation or feedback control loops to improve performance.

3. Performance Analysis:

    - Compare accuracy on noisy input between models employing backpropagation and combinations of Hebbian learning with feedback control.
    - Use t-SNE and Representational Dissimilarity Matrix (RDM) on intermediate layers to examine if the networks learn similar or different representations of images.

### Hypothesis
We hypothesize that introducing feedback control into the model will allow it to perform better on noisy data. To confirm this, we will compare accuracies on an image classification task.

### Project Goals
1. Understanding and Implementation:
    - Comprehend the chosen learning rules and feasibly implement them in a neural network.
    - Formulate different modifications and hyperparameters to apply to the implemented rule to improve performance.

2. Dataset Selection and Preparation:
    - Choose a dataset (e.g., MNIST) and preprocess it for the chosen task.

3. Experimentation:
    - Prepare neural networks with the chosen learning rule and different modifications for varying experiments.
    - Conduct a series of experiments comparing the learning rule and backpropagation on multiple classes from the chosen dataset (e.g., 2-class vs. 3-class vs. full 10-class classification task on MNIST).

4. Analysis:
    - Analyze results by observing network activity, learning curves, and accuracies.
    - Use t-SNE on intermediate layers to explore contrastive learning or representational geometries.

### Repository Structure

```plaintext
Biologically_Plausible_NN_Learning/
│
├── data/
│   ├── test/              # MNIST Test data
│   ├── train/             # MNIST Train data
│
├── notebooks/                 # Jupyter notebooks for exploration and analysis
│
├── scripts/
│   ├── data_preprocessing.py  # Script for data preprocessing
│   ├── model_training.py      # Script for training models
│   ├── evaluation.py          # Script for evaluating models
│
├── models/                    # Saved models
│
├── results/
│   ├── figures/               # Figures and plots
│   ├── logs/                  # Training and evaluation logs
│
├── README.md                  # Project overview and instructions
├── requirements.txt           # List of dependencies
├── LICENSE                    # License for the project
└── .gitignore                 # Git ignore file
```


# Task Assignment and Progress

| Task                                 | Description                                           | Assigned Member(s)           | Status       | Comments                    |
|--------------------------------------|-------------------------------------------------------|------------------------------|--------------|-----------------------------|
| Setup                                | Preparing and setting up the codebase                 | Hardik Goel                  | Not Started  | Get GitHub IDs for contributors |
| Data Preprocessing                   | MNIST for training, Adversarial MNIST Data for Testing| Hardik Goel                  | Not Started  | Use code from NMA workbook  |
| Implementing new model               | Meshing new model into data pipeline                  | Albert Ting, Dhiren, Hardik  | Not Started  |                             |
| Applying Feedback control to new model | Reading papers, coding implementation                 | Mahdie Tayeb, Dhiren         | Not Started  | Sacramento paper            |
| Weight and data visualization        | Visualize weight updates and data representations     | Maya                         | Not Started  |                             |
| Comparison between new model and backprop |                                                    |                              |              |                             |

## Contributors

- **Albert Ting**
- **Mahdie Tayeb**
- **Dhiren**
- **Maya**
- **Hardik Goel**

## Submission Links

- [W1D4 Proposal Submission Airtable Link](#)
- [W2D3 Progress Report Submission Airtable Link](#)
- [W2D5 Final Presentation Submission Airtable Link](#)
