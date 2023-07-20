# MGF Developer Meeting - July 21, 2023 

a monthly developer meeting for maintainers, contributors, and users to discuss MGF endorsed software projects.

July 21 @ 8 am PST on [Jitsi](https://meet.jit.si/mgf-materials-science-demo-friday)

## agenda


* **[pycalphad](https://github.com/pycalphad/pycalphad)**
  * Path to 1.0: https://github.com/pycalphad/pycalphad/projects/2
      * How ready does [`Workspace`](https://github.com/pycalphad/pycalphad/pull/432) need to be in order to ship? (continuation of in-person discussion between me and @bocklund last week)
    * Prospects for advanced phase diagram mapping prototype; release as a separate package versus integration, also does it need to integrate with `Workspace` or is it okay if it doesn't (yet)?
  * Paper using pycalphad published in _npj Computational Materials_: https://www.nature.com/articles/s41524-023-01058-9
    * Associated code: https://zenodo.org/record/7767663
  * Sam Krimmel presented on space charge models implemented with pycalphad; how much of this work can be merged into mainline?

* **[ESPEI](https://github.com/phasesresearchlab/espei)**
    * ?? [needs project input]

* **[Kawin](https://github.com/materialsgenomefoundation/kawin)**
  * Kawin paper published: https://www.sciencedirect.com/science/article/abs/pii/S1359645423003191
  * Regarding paraequilibrium calculations, there's an interesting new paper that may be relevant for future implementation: https://link.springer.com/article/10.1007/s11669-022-00969-2

* **[Scheil](https://github.com/pycalphad/scheil)**
  * Any lingering compatibility issues now that recent PRs have merged? Any architectural changes that should be made to ease this issue for the future?

* **[PySIPFENN](https://github.com/PhasesResearchLab/pySIPFENN)**
    * ?? [needs project input]

* **[DFTTK](https://github.com/PhasesResearchLab/dfttk)**
    * Maintainership currently in transition for this project, Penn State is working on it, who is the interim POC?
    * What can MGF do to help?

* **Multi-Project Issues**
    * Where should MGF-affiliated projects live on GitHub? Is there a need to insist on the MGF org, or is it okay if they are disparate?
    * Communication between developers, between developers and users, and users with each other: Discord versus Matrix versus something else
    * How do we decide on this meeting agenda in the future?

* **Open Discussion**