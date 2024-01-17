![EPFL Center for Imaging logo](https://imaging.epfl.ch/resources/logo-for-gitlab.svg)
# 🌊 napari-floodfill

Interactive object annotation in Napari using a *flood fill* tool. This tool is based on the [`flood`](https://scikit-image.org/docs/stable/api/skimage.segmentation.html#skimage.segmentation.flood) function of Scikit-image.

<p align="center">
    <img src="https://github.com/MalloryWittwer/napari-floodfill/blob/main/assets/screenshot.gif" height="400">
</p>

## Installation

You can install `napari-floodfill` via [pip]:

    pip install napari-floodfill

## Usage

- Select the plugin from the `Plugins` menu of Napari.
- Open an image to annotate (2D, RGB, 2D+t, or 3D).
- Click on the button "Start flood fill" or press `S`. A new `Labels` layer *Flood fill (current edit)* should appear.
- With the *Flood fill* layer selected, move your cursor arounda nd click on the image to annotate objects.
- Double-click to confirm the annotation of an object and move to the next.

**Options and parameters**
- *Auto-increment label index*: Tick this option to increment the label index every time a new object is annotated (e.g. if you are annotating multiple objects).
- *Intensity range*: Pixels outside of this range will not trigger the flood fill computation. The extremities of the range represent the absolute minimum and maximum of the image. Set the range somewhere to the left if you are annotating dark objects on a bright background, or to the right if you are annotating bright objects.
- *Flood fill tolerance*: Controls the extent of the flood fill. A higher value will fill more pixels. The value selected is relative to the image intensity range.

## Contributing

Contributions are very welcome. Please get in touch if you'd like to be involved in improving or extending the package.

## License

Distributed under the terms of the [BSD-3] license,
"napari-floodfill" is free and open source software

## Issues

If you encounter any problems, please file an issue along with a detailed description.

----------------------------------

This [napari] plugin is an output of a collaborative project between the [EPFL Center for Imaging](https://imaging.epfl.ch/) and the [Galatea Lab](https://www.epfl.ch/labs/galatea/) in 2023.

[napari]: https://github.com/napari/napari
[BSD-3]: http://opensource.org/licenses/BSD-3-Clause
[napari]: https://github.com/napari/napari
[pip]: https://pypi.org/project/pip/
