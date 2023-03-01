# Hate Speech Annotation

## Project Description

As part of the follow-on work of a previous analysis ([Xu, J. and Weiss, Z., 2022.](https://arxiv.org/abs/2211.06116)), the goal of this annotation project is to manually label a Hate Speech corpus (tweets) employing bianry scheme (no additional meta-data required for annotation). The plan is to at least annotate approx. 3000 tweets (collected in previous work) manually by two annotators to create a benchmark dataset for our analysis. The annotated dataset will be used to fine-tune LLMs such RoBERTa ([Liu Zhuang, Lin Wayne, Shi Ya, and Zhao Jun. 2021.](https://arxiv.org/abs/1907.11692)), BERT ([Devlin et al., NAACL 2019](https://aclanthology.org/N19-1423/)), BERTweet ([Dat Quoc Nguyen, Thanh Vu, and Anh Tuan Nguyen. 2020.](https://aclanthology.org/2020.emnlp-demos.2/)), Twitter-RoBERTa-base ([Francesco Barbieri, Jose Camacho-Collados, Luis Espinosa Anke, and Leonardo Neves. 2020.](https://aclanthology.org/2020.findings-emnlp.148/)) to improve the accuracy and reliability of our current automatic annotation pipeline for further extended analysis. 

The set-up and anticipated workload (amount of data to label) is flexible and depends on how many interested collaborators who decide to participate in the project as their term project for the Annotation Hauptseminar (or only part of the term project?), we could discuss distribution of work later in a meeting either in person or on Zoom.

Your work will be valued: __participants in the annotation project with sufficient contribution will be listed as co-authors__ of the follow-on work, as annotation will be an important part of the follow-on research project, which is planned to be submitted to an appropriate venue for review by Spetember 2023.

Simply drop me an email if you are interested :)

_Contact: [jinghua.xu@stud.uni-heidelberg.de](mailto:jinghua.xu@stud.uni-heidelberg.de) or [xujinghua1998@gmail.com](mailto:xujinghua1998@gmail.com)_



## Raw Data & Previous Work (Xu, J. and Weiss, Z., 2022.)


Raw data for annotation have been previously collected in [Xu, J. and Weiss, Z., 2022.](https://arxiv.org/abs/2211.06116). It contains over 2M English  tweets interested with our research topic. In previous work, all 2M tweets were labelled automatically with three LLMs for hate speech detection. 

* [link to paper](https://arxiv.org/abs/2211.06116)

* [link to code, data, analysis](https://github.com/JINHXu/how-much-hate-with-china)


## Extended Description on Follow-on work

* Annotation

* 


## Further Notes

* Annotation tool: [label studio](https://labelstud.io/) _(annotator friendly GUI)_

* Contact: [jinghua.xu@stud.uni-heidelberg.de](mailto:jinghua.xu@stud.uni-heidelberg.de) or [xujinghua1998@gmail.com](mailto:xujinghua1998@gmail.com)



### Reference

Xu, J. and Weiss, Z., 2022. How Much Hate with# china? A Preliminary Analysis on China-related Hateful Tweets Two Years After the Covid Pandemic Began. arXiv preprint arXiv:2211.06116.

Jacob Devlin, Ming-Wei Chang, Kenton Lee, and Kristina Toutanova. 2019. BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding. In Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1 (Long and Short Papers), pages 4171–4186, Minneapolis, Minnesota. Association for Computational Linguistics.

Liu Zhuang, Lin Wayne, Shi Ya, and Zhao Jun. 2021. A Robustly Optimized BERT Pre-training Approach with Post-training. In Proceedings of the 20th Chinese National Conference on Computational Linguistics, pages 1218–1227, Huhhot, China. Chinese Information Processing Society of China.

Dat Quoc Nguyen, Thanh Vu, and Anh Tuan Nguyen. 2020. BERTweet: A pre-trained language model for English Tweets. In Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing: System Demonstrations, pages 9–14, Online. Association for Computational Linguistics.

Francesco Barbieri, Jose Camacho-Collados, Luis Espinosa Anke, and Leonardo Neves. 2020. TweetEval: Unified Benchmark and Comparative Evaluation for Tweet Classification. In Findings of the Association for Computational Linguistics: EMNLP 2020, pages 1644–1650, Online. Association for Computational Linguistics.

