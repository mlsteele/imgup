# imgup

CLI tool to upload images to imgur, scrub exif data for privacy, and print the direct links to the images.

HEIC images are converted to jpg.

## Installation

There is currently no installer. Clone the repo to run it.

```
git clone git@github.com:mlsteele/imgup.git imgup
cd imgup
pip install -r requirements.txt
```

## Usage
Upload from files
```
./imgup ~/Downloads/IMG_1038.HEIC ~/Downloads/IMG_1039.HEIC
https://i.imgur.com/2Hijmxq.jpg
```

Upload from the clipboard
```
./imgup paste
https://i.imgur.com/2Hijmxq.jpg
```
