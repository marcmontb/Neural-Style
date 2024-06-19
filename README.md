# Neural-Style

This notebook details the implementation of the Neural-Style algorithm created by Leon A. Gatys, Alexander S. Ecker, and Matthias Bethge. Neural-Style, also known as Neural-Transfer, enables the transformation of an image by applying a new artistic style to it. The algorithm utilizes three images: an input image, a content image, and a style image. It modifies the input image to reflect the content of the content image and the artistic style of the style image.

**Underlying Principle**

The underlying principle is straightforward: we define two distances—one for content (`D_C`) and one for style (`D_S`). `D_C` measures the difference in content between two images, while `D_S` measures the difference in style between two images. The algorithm then takes a third image, the input, and transforms it to minimize both its content-distance to the content image and its style-distance to the style image.


The underlying principle is straightforward: we define two distances—one for content (`D_C`) and one for style (`D_S`). `D_C` measures the difference in content between two images, while `D_S` measures the difference in style between two images. The algorithm then takes a third image, the input, and transforms it to minimize both its content-distance to the content image and its style-distance to the style image.
