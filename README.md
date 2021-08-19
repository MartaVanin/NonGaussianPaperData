# PaperData
This repository shows how to obtain the data used for simulations in some paper(s) of which I am (co)author.

## Install and Use
This repository takes the form of a julia package, so that it is easily accessible via the julia package manager.

## Paper(s)

### Exact Modeling of Non-Gaussian Measurement Uncertainty in Distribution System State Estimation

```julia
using PaperData
data = get_EU_LV_feeder_data()
```
