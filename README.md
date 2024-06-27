# estrannaise.js
estrannaise.js is a small playground for estradiol pharmacokinetics. It can simulate estradiol blood levels under arbitrary dosing regimes and schedules. In the near future it will allow users to infer model parameters from outside sources, including their own personal blood levels.

Under the hood, estrannaise.js uses pharmacokinetic compartments models and MCMC inference using either a flat Gaussian model or our very own homebrewed hierarchical Bayesian amodel called Emix.

**estrannaise.js is entirely client-side. Your data, whether entered, imported, or stashed, remains exclusively within your browser and will never be transmitted to the developer(s) or any third-party.**

# TODO
- Shorten shared url
- Allow to manual set x-axis limits
- Allow possibility of changing patch wear time
- Offer different ways to visualize the uncertainty (parallel sigma lines and cloud ensemble of curves)
- Oral/sublingual/iv models

# Disclaimer
estrannaise.js is designed as a playground to explore estradiol pharmacokinetics and provides a simulation for informational and entertainment purposes only. The developer(s) cannot guarantee the accuracy of the predictions generated by the simulator. Users acknowledge that the software is offered "as is," without any warranties. The developer(s) assume no liability for direct or indirect damages, either physical, psychological, or otherwise, resulting from the use of the simulator. Users are strongly advised to exercise caution and seek professional medical advice for health-related queries.