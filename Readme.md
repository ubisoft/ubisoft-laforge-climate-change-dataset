# Ubisoft Watch_Dogs 2(c) - Ubisoft La Forge - Simulated flood dataset


This dataset can be used for usage described in the common creative License 4.0 ( See License.txt )

In this dataset we can find 467 images taken from PC version of Watch_Dogs 2 (San Francisco), 4800x3600 pixel resolution.
Initial goal to create this dataset was to use simulated data to help improve GAN models of "Visualizing Climate Change" project (Mila).
For more information please take a look here: https://mila.quebec/en/ai-society/visualizing-climate-change/
However it can be used for other Machine Learning and Computer Vision algorithms and more. 

## There are 4 subfolders:
1. Normal - all the 467 normal images, captures of city landmarks that look like Google street view images
2. Flood  - flooded paires of 467 images that we have in Normal folder, same camera view, same size, only difference is the flood
3. Mask   - here we have 467 binary masks of the flooded images, so black and white images, where white is for water and black is for everything else

There is also corresponding .txt files with name of each folder. In that text files we have lists of all the file names and paths for each subfolder.

So in total there are 1401 images files in the dataset.

Total size of the dataset is around 21Gb.

