# Weekly update - 08 Feb 2018

## Topics

* BMS Paper
* IPDPS
* EnTK
* Other

## Updates

### BMS Paper

* Status
    * In progress
        * Work on section 5 (application adaptivity)
            Building mathematical notation to describe adaptation loop and modes
            of adaptivity
        * Description of use cases using the derived mathematical notation
        * Work on section 7 (experiments)
            * Proposed new experiments of characterization of adaptivity overhead.
            Add pseudoplots and description (subsection 7.2).
    * Pending
        * Related work (section 3) - Not able to find many frameworks that support
          application adaptivity. Currently the prevalent method seems to be to 
          manually perform it via scripts or Copernicus in the case of MSM. Want
          to go through [this](https://github.com/common-workflow-language/common-workflow-language/wiki/Existing-Workflow-systems) list.
        * EnTK (section 6)  - Mapping of components to operations of the adaptation loop
                            - Adding enhancements made to EnTK to support adaptivity
    * Closed
        * None
* Deadline: March 28 (SC'18)
* Weekly call with Travis - Thursdays at 1 pm E
    * Status of experiments
        * Using both PoE and EoP -- might have experiments for both
        * Profiles to be stored and handed over for relevant experiments
        * VB: To test FIFO scheduler and notify Travis
    * Check if any blocking issues
        * No blocking issues
    * Iterations on the science sections of the paper - requested
    * Pseudoplots in the paper - requested


### IPDPS

* Status
    * In progress
        * VB making minor edits to the paper. 
        * Address comments from reviewers
        * Multiple revisions to check for grammatical errors.
    * Pending
        * PhD Forum
            * Draft of SoI done and waiting for reviews by SJ, MT
            * Pending work on poster
    * Closed        
        * Draft for SoI
* Deadline: 
    * Feb 28 for camera ready paper
    * Feb 15 for PhD Forum (Feb 4 internal deadline for draft)


### EnTK

* [Status](https://github.com/radical-cybertools/radical.entk/projects/2)
    * Release of 0.6 in Feb 3rd week
    * Termination issue #199 and testing critical issue for the release
    * Other issues are straight-forward
    * Closed issues
        * Added notion of session in EnTK
        * Multiple straight-forward issues resolved, closed old issues.    
* Deadline:
    * Release planned for week of Feb 19

### Other

* Setup GPU enabled script for extasy-grlsd
* General support in the extasy-coco and repex projects