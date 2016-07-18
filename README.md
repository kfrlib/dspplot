# DSPPlot

Matlab-style plots in python

* Impulse response
* Frequency response
* Phase response
* wvtool
* Highly configurable

## Installation

> Windows: Install latest prebuilt numpy, scipy and matplotlib before installing dspplot

```bash
python setup.py install
```

## Usage

### Plotting Window functions

```python
import dspplot

data = [] # create the data
dspplot.plot(
    data,
    freqresp=True,
    padwidth=1024,
    log_freq=False,
    horizontal=False,
    normalized_freq=True,
    title='Hamming window',
    # remove next line to show the plot interactively
    file='../svg/window_hamming.svg'
    )
````
## License

> MIT license
