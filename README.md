# Death Penalty SubStance Dataset

This repository is the home of the Death Penalty SubStance dataset -- A dataset of YouTube comments annoated with stance on death penalty and towrds two sets of targets.

__Background__

People often do not express their stance on topics directly, but rather by discussing subordinated or otherwise related targets. 
For instance, one can express a stance on death penalty by uttering *a false conviction is irreversible*.
Strictly speaking, the utterance only expresses a stance about the *irreversibility of convictions*, but most people would agree that in the context of the death penalty debate the person is rather against death penalty.
This characteristic of how people express stance can e.g. be modelled by not only quantifying stance towards the overall topic, but also towards a set of related targets (e.g.*irreversibility of convictions*, *humaneness of execution*).

While for concrete objects these sets can often be derived from product components directly, for abstract topics -- such as the death penalty -- defining suitable targets is more challenging.
NLP researchers have used different strategies to come up with suitable target sets: they heuristically define them, they rely on expert knowledge, or they use data-driven procedures. 
However, it remains an open research question how well different sets are able to describe stance expressed in social media debates, or which characteristics these sets should ideally have.
Sets may differ regarding quality criteria such as (i) how easily people can apply these sets in the form of a concrete annotation scheme (reliability), (ii) how many instances of a data set are covered by the set (coverage), and (iii) whether the targets meaningfully describe stance on the topic (topicality).

To shed light on these questions, we create a new data set of YouTube comments on the death penalty that we annotate with stance towards the death penalty and stance towards two sets of related targets -- (i) one expert set extracted from *idebate.com* and (ii) one representing the wisdom of the crowd from *reddit.com*.
To compare the two sets, we quantitatively analyze their reliability, their coverage, and their topicality.
To quantify the topicality, we examine how well stance can be predicted using the targets, and the relationship between targets and models that are trained to predict stance from text.

__License__

This work is licensed under Attribution-NonCommercial 2.0 Generic license (CC BY-NC 2.0)
(https://creativecommons.org/licenses/by-nc/2.0/)

_You are free to:_

* Share — copy and redistribute the material in any medium or format

* Adapt — remix, transform, and build upon the material

_Under the following terms:_

* Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

* NonCommercial — You may not use the material for commercial purposes.

__How to cite?__
If you want to use the SubStance dataset, please cite:
>@inproceedings{wojatzki2018femhate, <br />
 > &nbsp; title={Comparing Target Sets for Stance Detection: A Case Study on YouTube Comments on Death Penalty},<br />
 > &nbsp; author={Wojatzki, Michael and Zesch, Torsten},<br />
 > &nbsp; booktitle={Proceedings of the Konvens},<br />
 > &nbsp; year={2018}<br />
>}


