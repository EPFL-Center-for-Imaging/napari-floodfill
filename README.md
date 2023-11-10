# 🌊 napari-floodfill

Interactive object annotation in Napari using a *flood fill* tool.

<p align="center">
    <img src="https://github.com/MalloryWittwer/napari-floodfill/blob/main/assets/screenshot.gif" height="400">
</p>

## Installation

You can install `napari-floodfill` via [pip]:

    pip install napari-floodfill

## Usage

- Select the plugin from the `Plugins` menu of Napari.
- Open an image to annotate (2D, 2D+t, or 3D).
- Click on the button "Start live wire" or press `S`. A new `Labels` layer *Live wire (current edit)* should appear.
- With the *Live wire* layer selected, click on the image to annotate the contour of an object.
- Double-click to close the annotation path and fill the inside of the annotated object.

## Contributing

Contributions are very welcome. Please get in touch if you'd like to be involved in improving or extending the package.

## License

Distributed under the terms of the [BSD-3] license,
"napari-floodfill" is free and open source software

## Issues

If you encounter any problems, please file an issue along with a detailed description.

----------------------------------

This [napari] plugin was generated with [Cookiecutter] using [@napari]'s [cookiecutter-napari-plugin] template.

[napari]: https://github.com/napari/napari
[Cookiecutter]: https://github.com/audreyr/cookiecutter
[@napari]: https://github.com/napari
[MIT]: http://opensource.org/licenses/MIT
[BSD-3]: http://opensource.org/licenses/BSD-3-Clause
[GNU GPL v3.0]: http://www.gnu.org/licenses/gpl-3.0.txt
[GNU LGPL v3.0]: http://www.gnu.org/licenses/lgpl-3.0.txt
[Apache Software License 2.0]: http://www.apache.org/licenses/LICENSE-2.0
[Mozilla Public License 2.0]: https://www.mozilla.org/media/MPL/2.0/index.txt
[cookiecutter-napari-plugin]: https://github.com/napari/cookiecutter-napari-plugin

[napari]: https://github.com/napari/napari
[tox]: https://tox.readthedocs.io/en/latest/
[pip]: https://pypi.org/project/pip/
[PyPI]: https://pypi.org/
