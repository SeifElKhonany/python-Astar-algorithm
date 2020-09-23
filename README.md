# python-Astar-algorithm
A* path planning algorithm implementation with Python

## How to use
* Create a python environment and install the requirements.
`pip install requirements.txt`
* Replace this image with a path to a black and white image, and adjust the scale as desired.
```python
img = cv2.imread("garage.png")[:, :, 0]

img = cv2.resize(img, (100, 25), interpolation=cv2.INTER_AREA)
```
* Replace these points with the desired start and goal points.
```python
gx = 85
gy = 6

sx = 1
sy = 3
```
