<h2>Creates a rectangle around a center point</h2>


```python

$pip install cv2-rectangle-around-center

from cv2_rectangle_around_center import line_rectangle_center, rectangle_center
# Allowed image formats: url/path/buffer/base64/PIL/np


im1 = line_rectangle_center(
    image=r"https://raw.githubusercontent.com/hansalemaos/screenshots/main/diff.png",
    center=(150, 150),
    width=200,
    height=280,
    thickness=6,
    color1=(255, 0, 0),
    color2=(255, 255, 0),
    color3=(255, 0, 255),
    color4=(0, 255, 255),
    save_path="f:\\recta\\lines.png",
)

im2 = rectangle_center(
    image=r"https://raw.githubusercontent.com/hansalemaos/screenshots/main/diff.png",
    center=(150, 150),
    width=200,
    height=280,
    thickness=6,
    color=(255, 0, 0),
    save_path="f:\\recta\\rect1.png",
)

im3 = rectangle_center(
    image=r"https://raw.githubusercontent.com/hansalemaos/screenshots/main/diff.png",
    center=(150, 150),
    width=200,
    height=280,
    thickness=-1,
    color=(255, 255, 0),
    save_path="f:\\recta\\rect2.png",
)

```

<img src="https://raw.githubusercontent.com/hansalemaos/screenshots/main/diff.png"/>


<img src="https://github.com/hansalemaos/screenshots/raw/main/lines.png"/>


<img src="https://github.com/hansalemaos/screenshots/raw/main/rect1.png"/>



<img src="https://github.com/hansalemaos/screenshots/raw/main/rect2.png"/>