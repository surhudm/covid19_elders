# Elders whatsapp

A gui to help in string placements of translations on FAQ images.

## Requirements to run the code:

1. You need `python3` to run the code. The code requires the `tkinter` package which should be installed with most python platforms automatically. We also require the latest python imaging library (pillow >=6.2.2), install using 

```
pip install pillow
```

2. You need to download the Noto fonts from the Google noto repository (email me
if you need a link). Unzip and store in a directory named `Noto` within the
repository.

3. Download the translations csv file from google sheets and save it as `Elders.csv`.


## Running the code

```
python gui.py language
```

Select string by pressing `1` (question string), `2` (answer string), `3` (Title string in English).

Increase or decrease the font size with `i` or `d`, respectively.

Increase or decrease the length of the string by using `l` or `s`, respectively.

Move to the next image by pressing `n`.

Save the placements and fonts file using `w` (this can be done at any stage).

