# Deep Learning Model for Vietnamese to English Translation

This project aims to build a deep learning model that can automatically translate from Vietnamese to English using Python and Keras. The dataset used for training the model is obtained from the ManyThings.org website.

## Dependencies

Make sure the following dependencies are installed:

- Tensorflow
- Keras
- NLTK
- NumPy
- Pandas

You can install them using the following command:

```pip install tensorflow keras nltk numpy pandas```

## Dataset

The dataset used for training the model can be downloaded from [this link](http://www.manythings.org/anki/vie-eng.zip). After downloading, extract the file and place it in the `data` directory.

## Preprocessing

The first step in building the model is preprocessing the dataset. Run the following command to preprocess the dataset:

```python load_file.py```
```python split_text.py```

This will create two files `input.txt` and `output.txt` in the `data` directory. These files will be used for training the model.

## Training

To train the model, run the following command:

```python train_model.py```

This will create a model file `model.h5` in the `model` directory.

## Testing

To test the model, run the following command:

```python test.py```

This will prompt you to enter a Vietnamese sentence. After entering the sentence, the model will translate it to English.

## Credits

The dataset used for training the model is obtained from the ManyThings.org website. Special thanks to the creators of Keras and NLTK for providing excellent tools for building deep learning models.

