# タイトル

## 2. ソースコード

```python
# このああああああ
from PIL import Image
import sys

input_image = sys.argv[1]
output_image = sys.argv[2]

img = Image.open(input_image)

img_flip = img.transpose(Image.FLIP_LEFT_RIGHT)

img_flip.save(output_image)
```

## 3.1 aaaaa

- アアアアア

  ```bash
  python3 flip.py input.jpg output.jpg
  ```

- アアアアア

  |AAAAAA|VBBBB|
  |:------:|:-----:|
  |![aa](./input.jpg)|![bb](./output.jpg)|
