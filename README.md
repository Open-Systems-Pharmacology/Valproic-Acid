# Valproic acid-Model
Whole-body PBPK model of valproic acid including non-linear binding with albumin in adults, children and children with hypoalbuminemia.
This repository contains:
- a PK-Sim snapshot (*.json ) file of the current PBPK model
- static content (*.md files) as inputs for an evaluation plan
- an evaluation plan (evaluation-plan.json) to create an evaluation report using the snapshot and static text blocks to display the performance of the model 
This PBPK model is intended to be used as a basis for the implementation of non-linear protein binding using PBPK/Mobi.  The PBPK model helped assess the nonlinear dose-exposure relationship of VPA and the impact of albumin concentrations on the achievement of target exposure.
This whole-body PBPK model of valproic acid has been developed using in published information and the parameters were optimized based on pharmacokinetic clinical data. 

The model has then been evaluated simulating a large number of clinical studies and comparing with respective observed data, obtained from published clinical pharmacokinetic studies. 

This model has been published[<sup>1</sup>](#references).

## Code of conduct
Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution
We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License
The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## References
[1]  Karatza, E., Sinha, J., Maglalang, P. D., Edginton, A., & Gonzalez, D. (2024). Physiologically-Based Pharmacokinetic Modeling of Total and Unbound Valproic Acid to Evaluate Dosing in Children With and Without Hypoalbuminemia. Clinical pharmacokinetics, 63(10), 1435–1448. [https://doi.org/10.1007/s40262-024-01418-8](https://doi.org/10.1007/s40262-024-01418-8)
