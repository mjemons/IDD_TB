# Infectious Disease Dynamics - Antibiotic Susceptibility and Vaccination Trade-offs

This repository was created in the context of a lab rotation at the [theoretical biology group](https://tb.ethz.ch/) of [Prof Sebastian Bonhoeffer](https://usys.ethz.ch/en/people/profile.sebastian-bonhoeffer.html) at [ETH Zurich](https://ethz.ch/en.html). Supervisor of this project is [Dr. Sonja Lehtinen](https://usys.ethz.ch/en/people/profile.MjYyNjQ5.TGlzdC82MzcsMzIwMTk3MjIy.html).

A common concept in evolutionary theory is the [virulence transmission trade-off](https://science.sciencemag.org/content/343/6177/1243727). As in the case for HIV-1 in this paper we hypothesis that the same concept applies to antibiotic resistance and vaccination. Antibiotic resistance is a cost for the bacterium, resulting in a reduced fitness. We hypothesise that the introduction of vaccination and thus the rise in immune patients will result in a drop of available hosts that results in a transient shift towards higher virulence. 

This hypothesis will be simulated using an epidemiological model.

## Outline

* Compartmental model quantifying the dynamics of antibiotic resistance in `simulation-SIS.ipynb`
* Compartmental model quantifying the dynamics of antibiotic resistance in response to vaccination in `simulation-SISV.ipynb`
* Data Analysis on the Massachussets pneumococcal dataset trying to verify our hypothesis from above in `data-analysis.ipynb`
* Report summarising the results and discussing them in `IDD-Rotation.pdf`

## Dependencies

The requirements for this project can be found in the subfolder [scripts](https://github.com/mjemons/IDD_TB/scripts) with the name `requirements.txt`.
After cloning the repository activate an environment and run `pip install -r requirements.txt` in your shell.

## Literature

Literature is available in the folder `literature`. The full list of papers used is indicated in the report bibliography

The two most important papers for this project are

* Lehtinen, S., Blanquart, F., Croucher, N. J., Turner, P., Lipsitch, M., & Fraser, C. (2017). Evolution of antibiotic resistance is linked to any genetic mechanism affecting bacterial duration of carriage. *Proceedings of the National Academy of Sciences*, 114(5), 1075-1080.
* Fraser, C., Lythgoe, K., Leventhal, G. E., Shirreff, G., Hollingsworth, T. D., Alizon, S., & Bonhoeffer, S. (2014). Virulence and pathogenesis of HIV-1 infection: an evolutionary perspective. *Science*, 343(6177).
