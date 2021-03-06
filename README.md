## Spatial Analytics Exam: Biking Patterns in Boston 
This project spatially explores the BlueBikes biking patterns in Boston in 2019 and 2020. BlueBikes provided two csv files on Kaggle. The csv files are too big to upload here, so retrieve the data from this link: https://www.kaggle.com/datasets/jackdaoud/bluebikes-in-boston

The project uses different overlays to spatially investigate where the users of the bikes move between. Furthermore, it explores how use differs over time, and how elevation affects the patterns.

The ```biking_patterns``` script explores which areas the users move within through overlays of polygons and intersections

The ```patterns_over_time``` script explores how the use differs month to month and explore 2019 and 2020 through histograms

The ```routes_and_elevation``` script explores which routes are the most popular, the average and mean route length in euclidean space as well as how the dispersal of the points interact with the elevation in the city.

To run the code and reproduce the results you should:
- Pull this repository with this folder structure
- Download the csv files and place them in ```data```
- Install the packages mentioned in ```requirements.txt``` in ```documents```
- Set your current working directory to ```scripts```

The histograms in ```data_outputs``` are saved in the code with ```ggsave()```. The rest of the outputs I saved manually.
