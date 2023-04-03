# Pymaceuticals

In this project I used Pandas and Matplotlib to analyze and visualize the effect of different drug regimens on mice in a pharmaceutical study.

## Analysis

- 1 Mouse was removed from the results because it had two different sets of data collected for the same time points. This is why the bar char data for total timepoints tested is lower for the 'Propriva' regimen.
- The mice in the study were split by sex nearly 50/50 between male and female.
- When comparing the regimens, Capomulin, Ramicane, Infubinol, and Ceftamin, we see that Capomulin and Ramicane were effective in reducing the tumor volume over 45 days to below the starting volume of 45 mm³ in the vast majority of mice, while the other two increased the tumor volume.
- Specifically for mice tested with the Capomulin regimen, we can see that the volume of the tumor decreased over time, but not consistently, even sometimes going up between measurement days.
- Finally, for Capomulin mice, we can determine that the average tumor volume is strongly correlated (0.842) with the weight of the given mouse.

## Selected Visualizations
More can be found inside the [pymaceuticals.ipynb](/Pymaceuticals/pymaceuticals.ipynb) notebook.

Mice Tested per Drug Regimen

![Mice Tested per Drug Regimen](/Pymaceuticals/images/mice_tested.png)

Tumor Volume Distribution for Selected drugs

![Tumor Volume Distribution](/Pymaceuticals/images/volume_distributions.png)

Mouse Weight vs Tumor Volume for Capomulin mice

![Mouse Weight vs Tumor Volume](/Pymaceuticals/images/weight_v_volumne_trend.png)

### Extra:
All 25 Capomulin mice Tumor Volume over time

![All 25 Capomulin mice tumor volume over time](/Pymaceuticals/images/capomulin_all_mice_volume_over_time.png)