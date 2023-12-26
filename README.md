# Test_Driven_Development_Sparse_Matrix_Design
This project implements a sparse recommender matrix in Python using a test-driven development approach. The matrix allows for efficient storage and manipulation of data, particularly in scenarios where the majority of entries are zero.

## Table of Contents
- Overview
- Prerequisites
- Installation
- Testing
- Docker Integration
- Continuous Integration with CircleCI

## Overview
The SparseMatrix class is designed to handle sparse matrices, providing methods for setting and getting values, adding movie matrices, converting to a dense matrix, and making recommendations based on user vectors. The project follows a test-driven approach, ensuring the reliability and correctness of the code.

## Prerequisites
Before running or testing the project, make sure you have the following installed:
- Python (>=3.8)
- pytest
- numpy

## Installation
1. Clone the repository to your local machine:
`https://github.com/Anjali0407-git/Test_Driven_Development_Sparse_Matrix_Design.git`

2. Navigate to the project directory:
`cd Test_Driven_Development_Sparse_Matrix_Design`

## Testing
The project includes comprehensive unit tests using pytest. To run the tests, execute the following command in the project root directory:
`pytest test_sparse_recommender.py`

## Docker Integration
The project includes Docker integration for building and running the application in a containerized environment. To build the Docker image, run the following commands:
`docker build --no-cache -t sparse-recommender:latest .`

To run the Docker container:
`docker run -it sparse-recommender:latest`

## Continuous Integration with CircleCI
The project is set up for continuous integration using CircleCI. The configuration file .circleci/config.yml defines the build and test workflows. The project is automatically built and tested on each push to the master branch.

