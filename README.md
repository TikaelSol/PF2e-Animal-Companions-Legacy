This module is for people who do not want the behind the scenes manner of ability score and proficiency setting done in the main module available here: https://github.com/TikaelSol/PF2e-Animal-Companions

# PF2e-Animal-Companions-Legacy

Install this module by pasting this link: https://raw.githubusercontent.com/TikaelSol/PF2e-Animal-Companions-Legacy/main/module.json

into the install module dialog on the Foundry Add-on Module tab.

Once enabled in a world it will add 4 compendiums:
- The first contains all the animal companions released as of March 2021 statted up as ancestries to enable Foundry automation, as well as an Animal Companion class.  Just drag the correct ones to the PC sheet you are using for your Animal Companion.
- The second contains feats to automate the Mature, Nimble, and Savage damage bonuses (other bonuses are not automated).  Drag these feats to the animal companion sheet when your PC takes the associated feat.
- The third compendium contains actions for the Advanced Maneuvers.  these are not automatically added to the sheet and must be added when your companion gains access.
- The last contains the ancestry features linked to by the Ancestries.  You should not need to drag these to the sheet, they should automatically be added by the ancestries.

The name of the Animal Companion class and the ancestry can be edited once dragged to your sheet.

An Animal Companion specific sheet is in the works for the PF2e system, but until that is ready this can serve as a way to use the PF2e system automation.


# Known Issues
- Right now rule elements set the size of the animal companion, but this does not work to automate the size changes of the companions that can start at medium or large.  I am looking into active effects that can handle this but since size is not stored in a numeric value in the data structure the few companions that start larger than small may have to have their size adjusted manually.
