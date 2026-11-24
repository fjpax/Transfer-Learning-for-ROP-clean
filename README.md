# Volve-clean
Config files 1-4 contains json configurations. Each config folder uses different data, e.g., 
all json files under config 1 uses "F-11B_time_8.5in", and config 4 uses the shale csv.

configurations under the same config folder only differs on the data split percentage.

Config_NEwmodel.json files are used for retraining a new model with the same architecture

From the retrain1.ipynb, just look for the two cells which states "configurations" so you will see what to change in order to run. 


## Citation

If you use this repository in your research, please cite the following articles.

### The original study

Pacis, F. J., Alyaev, S., Ambrus, A., & Wiktorski, T. (2022). Transfer Learning Approach to Prediction of Rate of Penetration in Drilling. In *Computational Science – ICCS 2022* (Lecture Notes in Computer Science, Vol. 13351, pp. 358–371). Springer. [https://doi.org/10.1007/978-3-031-08754-7_44](https://doi.org/10.1007/978-3-031-08754-7_44)

```bibtex
@inproceedings{pacis2022transfer,
  author    = {Pacis, Felix James and Alyaev, Sergey and Ambrus, Adrian and Wiktorski, Tomasz},
  title     = {Transfer Learning Approach to Prediction of Rate of Penetration in Drilling},
  booktitle = {Computational Science -- ICCS 2022},
  editor    = {Groen, Derek and de Mulatier, Cl{\'e}lia and Paszynski, Maciej and Krzhizhanovskaya, Valeria V. and Dongarra, Jack J. and Sloot, Peter M. A.},
  series    = {Lecture Notes in Computer Science},
  volume    = {13351},
  pages     = {358--371},
  year      = {2022},
  publisher = {Springer},
  doi       = {10.1007/978-3-031-08754-7_44},
  url       = {https://doi.org/10.1007/978-3-031-08754-7_44}
}
```

### The extended peer-reviewed journal publication

Pacis, F. J., Ambrus, A., Alyaev, S., Khosravanian, R., Kristiansen, T. G., & Wiktorski, T. (2023). Improving predictive models for rate of penetration in real drilling operations through transfer learning. *Journal of Computational Science, 72*, 102100. [https://doi.org/10.1016/j.jocs.2023.102100](https://doi.org/10.1016/j.jocs.2023.102100).

```bibtex
@article{pacis2023improving,
  author  = {Pacis, Felix James and Ambrus, Adrian and Alyaev, Sergey and Khosravanian, Rasool and Kristiansen, Tron Golder and Wiktorski, Tomasz},
  title   = {Improving predictive models for rate of penetration in real drilling operations through transfer learning},
  journal = {Journal of Computational Science},
  year    = {2023},
  volume  = {72},
  pages   = {102100},
  doi     = {10.1016/j.jocs.2023.102100},
  url     = {https://doi.org/10.1016/j.jocs.2023.102100}
}
```
