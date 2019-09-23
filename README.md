# lithology-viewer

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/csiro-hydrogeology/lithology-viewer/master?urlpath=voila%252Frender%252Fapp.ipynb)

Experimental web app for exploring borehole log data. Built with Jupyter, ipyleaflet, ipysheet and voila

![Borehole descriptive lithology](./img/canberra_litho.png)

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