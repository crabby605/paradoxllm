# Small Semi-Functional LLM on Colab

This repository provides a small Language Model (LLM) demonstration using Google Colab. The LLM is hosted and executed in a Colab notebook, allowing users to interact with it easily without the need for local installations.

## Colab Link

You can access the project and run the LLM on Colab using the following link:
[Run the LLM on Google Colab](https://colab.research.google.com/drive/1ihLuPxHpYL4zLFsYHP5PE1MqwyhwJTYJ#scrollTo=qCg6m45q1SvQ)

## Features

- **Interactive LLM**: Use the model to generate text based on your inputs.
- **No Local Setup Required**: Everything is hosted on Google Colab, so you don't need to install anything on your local machine.
- **Free to Use**: The project leverages the free GPU resources available on Google Colab.

## How to Use

1. Click on the provided Colab link.
2. Once the notebook opens, click on `Runtime` -> `change runtime type` to -> `select T4 GPU`
3. After step two use one of the three provided txt's or use your own data
4. change the file names as per your wish and run it all
5. In the last cell type in your prompt in `prompt`

## Requirements

- **Google Account**: You need to sign in to your Google account to use Google Colab.
- **Internet Connection**: A stable internet connection is required to access Colab and run the model.

## How It Works

This project uses a lightweight LLM designed to process and generate text based on user input. The Colab notebook handles all computations in the cloud, and users only need to provide inputs through the notebook interface.

## Usage Example

1. Once you run the notebook, you'll find a text box where you can enter your prompts.
2. Type a prompt such as "Tell me about the wizard."
3. The model will generate a response based on your prompt.

## Customization

Feel free to modify the notebook and adjust the parameters of the LLM to suit your specific use cases. The code is written in Python and can be easily updated within Colab.

## Troubleshooting

- If the notebook disconnects, click on the `Reconnect` button at the top to reconnect to a Colab runtime.
- If you run out of available GPU quota, consider using Colab Pro for extended access.

## License

This project is open source and free to use under the MIT License. You are free to copy, modify, and distribute the code, as long as you provide proper attribution.
