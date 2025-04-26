# Gradient Checking in Deep Neural Networks

This assignment implements **gradient checking** to verify the correctness of backpropagation in deep neural networks by comparing analytical gradients to numerically approximated gradients.  
It is part of **Week 3 (Course 2: Improving Deep Neural Networks – Hyperparameter Tuning, Regularization, and Optimization)** from the **Deep Learning Specialization** by **Andrew Ng** on Coursera.

##  Description

In this lab, I used gradient checking to debug the implementation of backpropagation. The method ensures that the gradients computed by backpropagation match the gradients approximated numerically using small perturbations, thus verifying the correctness of the neural network training process.

### Key Concepts Covered:
- Gradient approximation using finite differences
- Analytical gradients from backpropagation
- Gradient checking by comparing numerical vs analytical gradients
- Debugging techniques for complex deep learning models
- Understanding sources of errors in backprop implementation

##  Files Included

- `gradient_checking_lab.ipynb`: Main notebook for implementing and testing gradient checking
- `gradient_checking_utils.py`: Helper functions for computing gradients and costs
- `data/`: Datasets used for training and testing during gradient checking

> ⚠️ This repository includes only my original code and abides by Coursera’s Honor Code.

##  Tools Used

- Python 3
- NumPy
- Jupyter Notebook

##  Course Info

This assignment is part of:
> [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning)  
> Instructor: **Andrew Ng**  
> Course 2: Improving Deep Neural Networks  
> Week 3: Gradient Checking

##  License

This repository is intended for educational and portfolio purposes only. Please avoid using it for direct assignment submission on Coursera.

---

 If you're passionate about building reliable deep learning models, feel free to star this repository!
