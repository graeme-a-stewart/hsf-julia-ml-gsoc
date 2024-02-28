# Machine Learning in Julia for Calorimeter Showers - Evaluation Exercise

Welcome to the evaluation exercise for the JuliaHEP [Machine Learning in Julia for Calorimeter Showers](https://hepsoftwarefoundation.org/gsoc/2024/proposal_JuliaHEPShowersML.html) proposal.

## Task

Your task in this evaluation exercise is to demonstrate your ability to train a basic machine learning model in Julia and to distribute the code so that others can easily run it.

### Details

You should do the following:

- Download and install the latest version of [Julia](https://julialang.org)
- Install the [Flux package](https://fluxml.ai) into your local Julia environment (if you never used Julia you'll want to read the [package manager documentation](https://pkgdocs.julialang.org/v1/))
- Load the CSV training dataset, `dataset.csv`
  - The dataset consists of 3 coordinate parameters (`x, y, z`) and a label (`s` == signal, `b` == background)
- With Flux, train a network to distinguish between the signal and background

### Evaluation

Your solution should consist of the following:

- A GitHib repository with your code
- A Julia `Project.toml` with the correct Julia environment and packages, such that others can easily install dependencies
- Either a Julia notebook or a script that trains the network and then calculates its accuracy over the whole dataset
- A `README` file that briefly explains the choices made for the network, training and loss functions

The evaluation is less on the final accuracy of the result and more on the clarity of the code and the explanations.
