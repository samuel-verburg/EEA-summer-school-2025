# EEA Summer School 2025: Measurement Methods for Sound Field Analysis, Reconstruction, and Reproduction

This repository contains educational material for the EEA Summer School 2025 focusing on advanced techniques for sound field analysis, reconstruction, and reproduction.

## Course Overview

The summer school covers modern approaches to acoustic field analysis and reconstruction, with a special focus on:
- Elementary wave expansions for sound field modeling
- Regularization techniques
- Machine learning applications in acoustics
- Physics-informed neural networks (PINNs) for sound field reconstruction

## Repository Contents

- **Exercise 1**: Sound Field Reconstruction, Wave Expansions, and Regularization
  - `exercise1.ipynb`: Complete notebook with solutions
  - `exercise1_student.ipynb`: Student version with exercises to complete

- **Exercise 2**: Machine Learning and Physics-Informed Neural Networks for Sound Field Reconstruction
  - `exercise2.ipynb`: Complete notebook with solutions
  - `exercise2_student.ipynb`: Student version with exercises to complete

## Prerequisites

The exercises require the following Python libraries:
- NumPy
- Matplotlib
- CVXPY (for optimization in Exercise 1)
- PyTorch (for neural networks in Exercise 2)
- tqdm (for progress bars)
- IPython and Jupyter (for notebook environment)

All required dependencies are listed in the `requirements.txt` file and can be installed with `pip install -r requirements.txt`.

## Getting Started

You can run these notebooks in two ways:

1. **Locally**: Clone this repository and run the notebooks in your local Jupyter environment
   ```bash
   git clone https://github.com/samuel-verburg/EEA-summer-school-2025.git
   cd EEA-summer-school-2025
   
   # Install required packages
   pip install -r requirements.txt
   ```

   The `requirements.txt` file contains all necessary Python dependencies for running the exercises.

2. **Google Colab**: Each notebook includes a "Open in Colab" button at the top that will open the notebook in Google Colab

## How to Use This Material

1. Start with Exercise 1 to learn the fundamentals of sound field reconstruction using elementary wave functions and regularization techniques
2. Proceed to Exercise 2 to explore how machine learning and physics-informed neural networks can be applied to sound field reconstruction problems
3. Use the student versions of the notebooks if you want to work through the exercises yourself
4. Refer to the complete notebooks for solutions and explanations

## License

This project is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

This means you are free to:
- Use this material for educational purposes
- Adapt and build upon the material for any purpose
- Use the material in research projects

Under the condition that you give appropriate credit to the original authors.

## Acknowledgments

- European Acoustics Association (EEA) for organizing the summer school
- All contributors and instructors involved in developing these materials: Samuel Verburg, Efren Fernandez Grande, Antonio Figueroa Duran.
