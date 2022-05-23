# VIST Human Evaluation Data
VHED is the dataset of ACL 2022 long paper “Learning to Rank Visual Stories from Human Ranking Data”. This dataset is a collection of human evaluation results from three VIST studies: KG-Story [1], PR-VIST [2], and Stretch-VST [3]. The below Figure shows the construction of VHED:
![figure](https://github.com/AcademiaSinicaNLPLab/VHED/blob/main/VHED%20workflow.jpg)

## CSV Attributes:
	a. sent1 : Content of Story 1
	b. sent2 : Content of Story 2
	c. label : Difference between the two average rankings(without normalization)
	d. story_id : Story identification number
	e. model_base : Generation model of story 1	
	f. model_comp : Generation model of story 2
	g. agreement : Number of human agreements
	h. img_seq : Image sequence ids
	i. avg_rank_base : Average ranking of story 1
	j. avg_rank_comp : Average ranking of story 2
	k. order : Number of rankers
	l. rank_norm : Normalized ranking gap

[1] Chao-Chun Hsu et al., “<a href="https://ojs.aaai.org//index.php/AAAI/article/view/6303">Knowledge-enriched visual storytelling</a>,” Proceedings of Thirty-Fourth AAAI Conference on Artificial Intelligence (2020).

[2] Chi-Yang Hsu et al., “<a href="https://aclanthology.org/2021.findings-acl.390.pdf">Plot and Rework: Modeling Storylines for Visual Storytelling</a>, ” Findings of the Association for Computational Linguistics: ACL-IJCNLP (2021).

[3] Chi-Yang Hsu et al., “<a href="https://aclanthology.org/2021.acl-demo.42/">Stretch-VST: Getting Flexible With Visual Stories</a>,” Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics (2021).