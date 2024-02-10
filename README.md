# Arithmetic Word Problem Solver

This repository contains the code for an Arithmetic Word Problem Solver developed as part of an assignment under the guidance of Prof. Shirish Shevade in August 2023. The project utilizes a Transformer model and T5 Tokenizer to translate English text representing arithmetic word problems into corresponding arithmetic expressions. The model achieved a commendable 72% accuracy by evaluating the generated postfix arithmetic expressions and obtaining a single numerical result.

## Problem Statement

The primary objective of this project is to leverage Transformer networks to solve simple arithmetic word problems. These problems are treated as machine translation tasks, where the goal is to convert English language text into the language of arithmetic expressions. The generated arithmetic expressions, represented as equations, are then processed using the provided input numbers to produce the final output.

## Dataset

The dataset used for training the model is available in the file named `ArithOpsTrain`. This dataset comprises information such as Description, Question, and Input Numbers. During testing, the model is presented with similar information in the test set, and the expected output is a single numerical result. The output file, formatted according to the provided template, should be uploaded when submitting the results.

## Implementation Details

The project employs a T5 Tokenizer for preprocessing the input data and builds a Transformer model from scratch to perform the translation task. The model is trained on the available dataset to learn the mapping from English text to arithmetic expressions. The evaluation is based on the accuracy achieved in generating postfix arithmetic expressions and obtaining the corresponding numerical result.

## Usage

To use the Arithmetic Word Problem Solver, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/arithmetic-word-problem-solver.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the solver on a sample input:

    ```bash
    python solve_problem.py --input "Your English language arithmetic word problem here."
    ```

4. Evaluate the model on the test set and generate the output file:

    ```bash
    python evaluate_test_set.py
    ```

## Results

The model's performance is assessed based on the accuracy achieved in translating English language text into arithmetic expressions and producing the correct numerical output. The results are detailed in the project report.

## Acknowledgments

We would like to express our gratitude to Prof. Shirish Shevade for providing guidance and support throughout the development of this Arithmetic Word Problem Solver.
