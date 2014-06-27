# K-Mean Image Clustering

Python script to identify different regions in an input image using K-Mean clustering algorithm.

Visit my related [blog post](http://iabhimanyu.wordpress.com/2012/07/10/k-mean-image-clustering-in-python/) for more info.
## Dependencies
Python Image Library

```
PIL-1.1.7
```

## Usage

```
$ python kmean_image_clustering.py
```

Interactively ask for no of clusters (in which you want to cluster the image pixels), seed mean RGB tuple values for the no. of clusters you entered. Once the program is done clustering it will ask the RGB tuple values representing the color with which user want to color the clusters.

## Example
Input images to be stored in `input` folder kept in the same directory from where user wants to run the script.
Output images will be stored in folder named `output`.

```
$ python kmean_image_clustering.py
enter the number of clusters 2
enter the mean of cluster  rgb tuple 0
10
20
30
enter the mean of cluster  rgb tuple 1
111
121
131
new mean of cluster  0  =  [57, 60, 65]
new mean of cluster  1  =  [167, 155, 135]
new mean of cluster  0  =  [78, 83, 83]
new mean of cluster  1  =  [186, 170, 146]
new mean of cluster  0  =  [91, 93, 88]
new mean of cluster  1  =  [194, 176, 152]
new mean of cluster  0  =  [96, 97, 90]
new mean of cluster  1  =  [197, 179, 155]
new mean of cluster  0  =  [98, 99, 91]
new mean of cluster  1  =  [198, 180, 156]
new mean of cluster  0  =  [99, 99, 91]
new mean of cluster  1  =  [199, 181, 156]
new mean of cluster  0  =  [99, 99, 91]
new mean of cluster  1  =  [199, 181, 156]
enter k colors
 R value of 0 color 10
 G value of 0 color 20
 B value of 0 color 30
 R value of 1 color 230
 G value of 1 color 100
 B value of 1 color 155
 1 sample2.jpg
```

