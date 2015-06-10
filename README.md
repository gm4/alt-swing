# alt-swing
This is an IPython Notebook implementation of the SE multi-objective decision analysis framework described at [http://sebokwiki.org/wiki/Decision_Management].  For detailed instructions, follow the [User Guide](gm4.github.io/alt-swing/).

## Use
Assess a set of alternatives, scoring performance using swing weights, and display the results.
The assessment follows this process:
*  Define a set of objectives with an associated value function and importance value for each objective
*  Establish a set of alternatives with corresponding performance measures for each objective
*  Determine the swing weight for each objective, considering both the importance and 'swing' in system value for each alternative
*  Calculate the resulting system value for all alternatives using the value contributed to each objective
*  Display results of the analysis

## To Do

* Allow an arbitrary Objectives hierarchy (currently limited to two levels - Objectives and Measures)
* Allow arbitrary naming scheme for Objectives, Measures and Alternatives
* Remove Alternatives with scores that do not meet threshold criteria


## License
Licensed under the MIT License.  See https://github.com/gm4/alt-swing/blob/master/LICENSE
