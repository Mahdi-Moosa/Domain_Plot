# Domain_Plot.py
Python script - plots protein domains and motifs from annotations. Domain annotation should be provided as a json file. An example json file is provided.

The script saves domain organization plot as svg file. SVG file can be imported to Inkscape/ Adobe Illustrator/ Affinity Designer for further processing. If you need pdf format of the image, please open the svg file in your browser of choice and save as pdf.

Command to run the script: *python Domain_Plot.py input_file_with_protein_annotation.json*

# Domain_Plot.ipynb
Jupyter notebook, does the same thing as aforementioned python script. Also, has an additional cell to convert svg file to pdf.

# protein_annotation.json
Example input file for the script.

## Requirements
1. matplotlib
2. drawSvg
