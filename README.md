[![GitHub license](https://img.shields.io/github/license/SINGHxTUSHAR/NextWordAI.svg)](https://github.com/SINGHxTUSHAR/NextWordAI/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/SINGHxTUSHAR/NextWordAI.svg)](https://GitHub.com/SINGHxTUSHAR/NextWordAI/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/SINGHxTUSHAR/NextWordAI.svg)](https://GitHub.com/SINGHxTUSHAR/NextWordAI/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/SINGHxTUSHAR/NextWordAI.svg)](https://GitHub.com/SINGHxTUSHAR/NextWordAI/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


[![GitHub watchers](https://img.shields.io/github/watchers/SINGHxTUSHAR/NextWordAI.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/NextWordAI/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/SINGHxTUSHAR/NextWordAI.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/NextWordAI/network/)
[![GitHub stars](https://img.shields.io/github/stars/SINGHxTUSHAR/NextWordAI.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/NextWordAI/stargazers/)

[![Open in Visual Studio Code](https://img.shields.io/static/v1?logo=visualstudiocode&label=&message=Open%20in%20Visual%20Studio%20Code&labelColor=2c2c32&color=007acc&logoColor=007acc)](https://open.vscode.dev/SINGHxTUSHAR/NextWordAI)


# NextWordAI
![Preview Image](https://github.com/SINGHxTUSHAR/NextWordAI/blob/3b63521de3d8cfc863b6631786d8b22c734f4ba8/preview.png)

#### Project Overview:
This project focuses on developing a deep learning model for predicting the next word in a given sequence of words using Long Short-Term Memory (LSTM) networks. LSTMs are particularly effective for sequence prediction tasks because they capture long-term dependencies in data. The model is trained on the text of Shakespeare's "Hamlet," providing a rich and complex dataset that challenges the model's predictive capabilities.

The project utilizes advanced deep-learning techniques to enhance natural language processing capabilities, specifically in next-word prediction tasks. By leveraging LSTM networks, it captures intricate patterns and dependencies within text data, ultimately providing a tool for applications such as text auto-completion and interactive chatbots. The deployment through a web application allows for user-friendly interaction with the model, showcasing its practical utility in real-time scenarios.



## Workflow Description
The project follows a structured workflow consisting of six key steps:

1- `Data Collection`: We use the text of Shakespeare's "Hamlet" as our dataset. This rich, complex text provides a good challenge for our model.

2- `Data Preprocessing`: The text data is tokenized, converted into sequences, and padded to ensure uniform input lengths. The sequences are then split into training and testing sets.

3- `Model Building`: An LSTM model is constructed with an embedding layer, two LSTM layers, and a dense output layer with a softmax activation function to predict the probability of the next word.

4- `Model Training`: The model is trained using the prepared sequences, with early stopping implemented to prevent overfitting. Early stopping monitors the validation loss and stops training when the loss stops improving.

5- `Model Evaluation`: The model is evaluated using a set of example sentences to test its ability to predict the next word accurately.

6- `Deployment`: A Streamlit web application is developed to allow users to input a sequence of words and get the predicted next word in real-time.


## Requirements💻 :

Ensure you have the following dependencies installed:

- Python (version 3.11.x || 3.12.x)
- IDE: VS-CODE or collab
- Virtual-environment(venv)
- Other dependencies (refer to the requirement.txt)

You can install the required Python packages using:

```bash
pip install -r requirement.txt
```


## Setup 💿:

- Clone the repository:
```bash
git clone https://github.com/SINGHxTUSHAR/NextWordAI.git
cd NextWordAI
```
- Create a virtual environment (optional but recommended):
```bash
python -m venv venv
```
- Activate the virtual environment:
  - On Windows:
   ```bash
   venv\Scripts\activate
   ```
  - On macOS/Linux:
  ```bash
  source venv/bin/activate
  ```


## Contributing 📌:
If you'd like to contribute to this project, please follow the standard GitHub fork and pull request process. Contributions, issues, and feature requests are welcome!

## Suggestion 🚀: 
If you have any suggestions for me related to this project, feel free to contact me at tusharsinghrawat.delhi@gmail.com or <a href="https://www.linkedin.com/in/singhxtushar/">LinkedIn</a>.

## License 📝:
This project is licensed under the <a href="https://github.com/SINGHxTUSHAR/NextWordAI/blob/main/LICENSE">MIT License</a> - see the LICENSE file for details.
