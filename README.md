# GLiNER LitServe

[![Open In Studio](https://pl-bolts-doc-images.s3.us-east-2.amazonaws.com/app-2/studio-badge.svg)](https://lightning.ai/sitammeur/studios/gliner-litserve)

[GLiNER](https://github.com/urchade/GLiNER), a flexible Named Entity Recognition model using a BERT-like architecture, offers a cost-effective alternative to traditional NER and LLMs for identifying diverse entity types in resource-constrained environments. ModernGLiNER, a GLiNER model version that utilizes a bi-encoder architecture ([ModernBERT-large](https://huggingface.co/answerdotai/ModernBERT-large) and [BGE-base-en](https://huggingface.co/BAAI/bge-base-en-v1.5)), overcomes limitations of traditional unicoder GLiNER models by enabling recognition of unlimited entities with faster inference for preprocessed embeddings and better generalization to unseen entities. This project demonstrates using the GLiNER model for the Named Entity Recognition (NER) task served using LitServe, an easy-to-use, flexible serving engine for AI models built on FastAPI.

## Project Structure

The project is structured as follows:

- `server.py`: The file containing the main code for the web server.
- `client.py`: The file containing the code for client-side requests.
- `LICENSE`: The license file for the project.
- `README.md`: The README file that contains information about the project.
- `assets`: The folder containing screenshots for working on the application.
- `.gitignore`: The file containing the list of files and directories to be ignored by Git.

## Tech Stack

- Python (for the programming language)
- PyTorch (for the deep learning framework)
- Hugging Face Transformers Library (for the model)
- LitServe (for the serving engine)

## Getting Started

To get started with this project, follow the steps below:

1. Run the server: `python server.py`
2. Upon running the server successfully, you will see uvicorn running on port 8000.
3. Open a new terminal window.
4. Run the client: `python client.py`

Now, you can see the model output based on the input text and labels. The model will predict the named entities in the text according to the labels provided.

## Usage

The project can be used to serve the GLiNER model using LitServe. Here, the model predicts named entities in the text based on the labels provided. This suggests potential applications in information extraction, news aggregation, and content summarization.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please raise an issue to discuss the changes you want to make. Once the changes are approved, you can create a pull request.

## License

This project is licensed under the [Apache-2.0 License](LICENSE).

## Contact

Please contact me on my GitHub profile if you have any questions or suggestions about the project.

Happy coding! 🚀
