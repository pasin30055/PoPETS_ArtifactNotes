# Artifact Badges

For PETS 2024, each accepted artifact will be granted one of the following two badges. During the submission, the authors must select which badge they want their artifacts to be evaluated against. 

## Artifacts Available
This "Available" badge indicates that the artifacts are publicly available at a permanent location with clear documentation on how it relates to the corresponding paper and, if applicable, how to execute the artifact/evaluation without execution error. This badge does *not* mean that the reviewers have reproduced the results.

Authors whose artifacts require extremely specialized hardware or software are encouraged to choose this option. Similarly, authors whose artifacts are "not reproducible" (e.g., outcomes of surveys) should also select this option.

### Examples
**Machine Learning Models** If a machine learning model is required to execute the presented tool, the authors should provide it unless they have a good reason not to do so (e.g., the model is incredibly big or proprietary). If they can't share the full model, we'd expect them to share some dummy model (perhaps with worse performance but a more manageable size).

**User Studies** The (anonymized/pseudonymized) raw user study data should be provided, incl. the evaluation scripts. However, we allow for exceptions for this point if a publication of raw data is not possible because of legal requirements, privacy, or ethical concerns, e.g., if a the data cannot be pseudonymized properly.

## Artifacts Reproduced
The "Reproduced" badge indicates everything the "Available" badge does and, in addition, that the submitted artifacts reproduce the main findings of the paper. Note that this does not necessarily cover all experiments/data presented in the paper. To submit artifacts for this badge, the authors must specify the commands to run the artifacts clearly and describe how to reproduce each main finding of the paper. Also, they must highlight which results of the paper are not reproducible with the given artifacts. The artifact's quality, structure, and documentation must allow the reviewers to check whether the artifact works as claimed in the paper.

Even if the authors choose this option, the review committee may request to grant only an "available" badge if the reviewers cannot reproduce the results (e.g., lack of computational resources).
