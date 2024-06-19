# Neural-Style

This notebook provides a comprehensive guide to implementing the [Neural-Style algorithm](https://arxiv.org/abs/1508.06576) developed by Leon A. Gatys, Alexander S. Ecker, and Matthias Bethge. Known as Neural-Transfer or Neural-Style, this technique allows you to transform an image by infusing it with a new artistic style. The process involves three images: an input image, a content image, and a style image. The algorithm alters the input image to mirror the content of the content image while adopting the artistic style of the style image.

**Core Concept**

The core concept is simple: we establish two metrics—one for content (D<sub>C</sub>) and one for style (D<sub>S</sub>). The content distance (D<sub>C</sub>) quantifies how different the content is between two images, and the style distance (D<sub>S</sub>) assesses how different the styles are. The algorithm processes a third image, the input, and adjusts it to minimize both the content distance from the content image and the style distance from the style image.

