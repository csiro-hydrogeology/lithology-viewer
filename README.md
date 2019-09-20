# lithology-viewer

<!-- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jtpio/voila-gpx-viewer/master?urlpath=voila%2Frender%2Fapp.ipynb) -->

Experimental web app for exploring borehole log data. Built with Jupyter, ipywidgets, ipyleaflet, bqplot and voila

<!-- Placeholder for a screencast -->

## Usage

```bash
voila app.ipynb
```

To automatically cull idle kernels:

```bash
voila --MappingKernelManager.cull_interval=10 --MappingKernelManager.cull_idle_timeout=10 app.ipynb
```

## Acknowledgments

This sample is derived from the [voila-gpx-viewer](https://github.com/jtpio/voila-gpx-viewer)