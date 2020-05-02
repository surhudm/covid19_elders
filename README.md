# covid19_elders
Elders whatsapp

A gui to help in string placements of translations on FAQ images.

## Requirements to run the code:

```
python3
```
The code requires the `tkinter` package which should be installed with most python platforms automatically. We also require the latest python imaging library (pillow), install using 

```
pip install pillow
```

You need to download the Noto fonts from the Google noto repository (email me
if you need a link). Unzip and store in a directory named `Noto` within the
repository.

## Running the code

```
python gui.py language
```

Select string by pressing `1` (question string), `2` (answer string), `3` (Title string in English).

Increase or decrease the font size with `i` or `d`, respectively.

Increase or decrease the length of the string by using `l` or `s`, respectively.

Move to the next image by pressing "n".

Save the placements and fonts file using `w` (this can be done at any stage).

