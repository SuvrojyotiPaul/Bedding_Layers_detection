# Bedding_Layers_detection
Automated Detection of Bedding Layers in Geological Structures

This project deals with drone-gathered images of rocky outcrops in a spe-
cific zone of geological enquiry. These rocky outcrops are unique geological
structures made by the aggregation of mineral bands one on top of the other
over time. The goal of this project is to use computer vision techniques to
automate the detection of boundaries between the different mineral bands
or layers also known as bedding layers. Detection and characterisation of
these boundaries is of immense value to geologists. It allows easy detection of
anomalous or unique structures, the study of which can be taken up in greater
detail to generate novel insights about geological processes

# Dataset preparation
The dataset contains 162 images extracted from drone footages of the
specific geographical zone. It is provided with a .csv file containing annota-
tions specific to three separate tasks namely, a/ outcrop annotation (marking
the rock formation in images for segmentation), b/ bedding plane detection
(present or not), and c/ identifying bedding plane boundaries. Task item ‘c’
is of interest to this project, and the annotations available for this task, in
JSON format, include task label, coordinates of line segments marking bed-
ding plane boundaries, and corresponding image filenames.
We referenced the annotation file, and retained 134 images with a total
of 918 annotations of line segments marking the bedding plane boundaries.
The boundaries are not exhaustively marked, one boundary may be marked
by multiple users, the annotations are often noisy since they are not provided
or verified by experts

# The whole project has been divided into three files
1)The Basic data modelling file
2)The Advanced data modelling file
3)The Ideas of Future file

# You can refer the report pdf and the files for better understanding the files and approach.  
