# Image Scrapping Tool
This tool allows you to scrap images from Google based on a search term and save them to your local drive.

## Installation
To use this tool, you will need to install the following libraries:

* mechanicalsoup
* requests
* pillow

You can install these libraries using pip:
```
pip install mechanicalsoup requests pillow
```

## Usage
To use this tool, call the **`image_scrapping`** function and provide a search term as input. The images will be downloaded and saved to a folder with the same name as the search term.

python
```
from image_scrapping import image_scrapping_2

image_scrapping_2("cats")
```
By default, the images will be saved to the following directory:

css
```
/content/drive/MyDrive/[02] Data Analytics Tutor/Phase 1/Scrapping
```
You can modify this directory by changing the **`path`** variable in the code.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
