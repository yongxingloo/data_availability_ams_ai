# Database for results

**Paper** : Estimating wind speeds from geostationary satellite data using deep learning

**file hierarchy** :
```
raw_results_folder/
└── model_day_128x128_year-month-day_C06/
    ├── inference_year-month-day_hour-00-'00/
    │   ├── data_goes_image.npy
    │   ├── data_lat.npy
    │   ├── data_wind_speeds.npy
    │   ├── plot_goes_image.png
    │   └── plot_wind_speeds.png
    ├── buoy_comparison.csv
    ├── epoch_n.pth
    ├── loss_plot.png
    ├── rmse_per_range.csv
    ├── scatter_plot.png
    ├── test_labels.npy
    ├── test_loss.npy
    └── test_output.npy

buoy_plots/
├── year-month-time_buoy_validation.pdf
└── year-month-time_buoy_validation.png

era5_comparison/
└── year-month-day.mp4
```

The trained models can't be accessed in this repository because of Github file limit size. You can send an email to yloo@tudelft.nl to request the trained models ```epoch_n.pth```. You can also train your own models from the package windscangeo.github.io. This package is meant to replicate the process of the project from GOES data extraction from AWS, training to inference.
