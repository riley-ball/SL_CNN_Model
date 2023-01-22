# SL_CNN_Model
A pre-trained image classification model for sign language images.

To import TensorFlow model into Python:

1. Extract zipped file
```python
import zipfile
with zipfile.ZipFile('my_model.zip', 'r') as zip_ref:
    zip_ref.extractall()
```

2. Import the model
```python
loaded_model = tf.saved_model.load('path/to/extracted/model', 'model_signature_name')
```
