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
