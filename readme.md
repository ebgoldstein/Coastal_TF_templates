## Templates for coastal ML projects using TensorFlow

Being built for teaching and for prototyping.

*more details soon...*

these can be used in Google colab:

- set runtime to GPU!!! go to 'Runtine > Set Runtime > GPU'

- mount your google drive. it will be visible in the file navigator on the left of the colab notebook. there should be a folder in your drive with your data:

```
from google.colab import drive
drive.mount('/content/gdrive')
```
- put all your data (e.g., images and labels) in a folder called 

for segmentation from doodler data, the dir structure is:
``` 
── fromDoodler
       ├──images
       |     └──images
       |          └── <someimage.jpg>
       └──labels
            └──labels
                   └── <someimage_label.jpg>
```

- for train and val directories, use something like:
`/content/gdrive/MyDrive/fromDoodler/images'`