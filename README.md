# DeepSeek-R1 Testing and Comparison

This repository contains notebooks and resources for testing and comparing DeepSeek-R1, a family of open-source large language models (LLMs).

## Project Overview

The goal of this project is to provide a hands-on exploration of DeepSeek-R1's capabilities, including:

*   Performance benchmarking
*   Output quality assessment
*   Comparison with other LLMs (e.g., Gemini)
*   Reproducible testing environment

## Models Tested

The following DeepSeek-R1 models are included in the testing:

*   DeepSeek-R1 1.5B
*   DeepSeek-R1-Distill-Llama-8B
*   DeepSeek-R1-Distill-Llama-70B

## Getting Started

### Prerequisites

*   Python 3.7+
*   Jupyter Notebook or Jupyter Lab
*   A Google Cloud account with Vertex AI access

### Installation

1.  Clone this repository:

    ```bash
    git clone [https://github.com/analyticsrepo01/deepseek-r1.git](https://github.com/analyticsrepo01/deepseek-r1.git) 
    ```
    (Make sure to use your actual repo link)

2.  Navigate to the repository directory:

    ```bash
    cd deepseek-r1
    ```

3.  Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```
    (You might want to create a `requirements.txt` file listing the necessary packages, e.g., `transformers`, `torch`, `google-cloud-aiplatform`)

### Deploying the Model from Model Garden

The DeepSeek-R1 models are available on Google Cloud's Model Garden. The following screenshot illustrates the steps to deploy an endpoint for one of these models:

![How to deploy the model](How%20to%20deploy%20the%20model.png)

**Steps:**

1.  Go to Vertex AI in the Google Cloud console.
2.  Navigate to Model Garden.
3.  Search for "DeepSeek".
4.  Select the DeepSeek-R1 model you want to deploy.
5.  Click on "Deploy".
6.  Follow the instructions to configure and deploy the endpoint.

## Notebooks

The `notebooks` directory (you should create this directory) contains Jupyter notebooks that demonstrate how to interact with the deployed DeepSeek-R1 models and perform various tests.

## Contributing

Contributions are welcome! If you have any improvements, bug fixes, or additional tests, please feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.