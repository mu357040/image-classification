# Image Category Prediction Using Machine Learning

This project is a web application that uses machine learning to predict the category of an uploaded image. Users can upload an image, and the system will analyze the content and provide a category prediction from a predefined list of options.

## Prerequisites

Before running the project, make sure you have the following dependencies installed:

- Python 3.x
- TensorFlow
- TensorFlow Hub
- FastAPI
- Pillow (PIL)
- NumPy

You can install these dependencies using pip:

```bash
pip install tensorflow tensorflow-hub fastapi pillow numpy
```

## Running the Project

1. Clone the project repository:

```bash
git clone https://github.com/mariamubarthh/image-classification.git
cd image-classification
```

2. Run the FastAPI application:

```bash
python main.py
```

## Usage

Open your web browser and go to http://localhost:8000.

You will see a page with an option to upload an image. Choose an image and click the "Predict" button.

![Project Home Page](https://github.com/mariamubarthh/image-classification/blob/main/assets/home_page.png)

The application will process the image and display the predicted category along with a confidence score.

![Project Output](https://github.com/mariamubarthh/image-classification/blob/main/assets/result.png)

## Additional Details

- The project uses the MobileNetV2 model from TensorFlow Hub for image classification.
- Pretrained category names are defined in category_list.py.
- Uploaded images are preprocessed to meet the model's input requirements.
- The application is built using FastAPI for the backend and includes HTML templates for the frontend.

## Contributing

Contributions to Recipe Finder are welcome! If you find a bug or have a feature request, please open an issue or submit a pull request.

## License

Recipe Finder is licensed under the MIT License. See `LICENSE` for details.


## Acknowledgments

Special thanks to the instructors and teaching assistants of the Python programming course.
