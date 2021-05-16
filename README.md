# SI for washtenaw county

<!--ts-->
* [**1. summary and research questions**](#summary-and-research-questions)
* [**2. results**](#results)
* [**3. data**](#data)

<!--te-->

## summary and research questions

This is fairly difficult to answer, but I can definitely say a few things

* want to breakdown location-based data into social-investigable tracts of land. 
    * In this case, that probably means specific apartment complexes or city blocks
    * not school districts, voting districts, or wards; these are broader
    * also, project housing is often intermixed within much wealthier housing in AA
    * **from the meeting with James and Joey**:
        * Thinking of using Census data, which has been added to the project but not the repository (size constraints)

* how does crime factor into this analysis?
    * can define some basic metrics of crime rates using violent crime/ some other categories
    * can also include rates in which calls come in

* housing stuff
    * population density
    * racial demographics
    * policing stuff
    * owners etc.

* Current next steps: get census breakdowns by tract and visualize in a meaningful way. Also add apartment buildings as blocks.

## results

* nothing to visualize yet. I'll add some screenshots later.

## data

All data thus far was pulled with a series of Python scripts, contained mostly in the [`analysis.ipynb`](/analysis.ipynb) file. A central `QGIS` file is given by the [`main.qgz`](/main.qgz) file.

Data itself is contained in the (data)[/data] folder, which includes a number of random things I thought looked interesting. The census data is not added to this list because its ginormous, though I plan to pare it down to strictly the things we need ASAP. 