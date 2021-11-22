# Awesome Semantic-Search [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)  [![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)



<img src ="logo.svg" />


Logo réalisé par [@createdbytango](https://instagram.com/createdbytango). 

Le référentiel suivant vise à servir de méta-référentiel pour [Recherche sémantique](https://en.wikipedia.org/wiki/Semantic_search) et [Similarité sémantique](http://nlpprogress.com/english/semantic_textual_similarity.html) tâches connexes.

La recherche sémantique ne se limite pas au texte! Cela peut être fait avec des images, de la parole, etc. Il existe donc de nombreux cas d'utilisation et applications différents de la recherche sémantique.

## Contenu

- [Papiers](#papers)
    - [2014](#2014)
    - [2015](#2015)
    - [2016](#2016)
    - [2017](#2017)
    - [2018](#2018)
    - [2019](#2019)
    - [2020](#2020)
    - [2021](#2021)
- [Des articles](#articles)
- [Bibliothèques et outils](#libraries-and-tools)
- [Ensembles de données](#datasets)
- [Étapes importantes](#milestones)

## Papiers

### 2010
- [Arbres prioritaires](https://arxiv.org/abs/1009.3527)

### 2014 
- [Un modèle sémantique latent avec mise en commun convolutive
Structure pour la recherche d'informations](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/cikm2014_cdssm_final.pdf) 📄

### 2015
- [Vecteurs de saut de pensée](https://arxiv.org/pdf/1506.06726.pdf) 📄
- [LSH pratique et optimal pour la distance angulaire](https://proceedings.neurips.cc/paper/2015/hash/2823f4797102ce1a1aec05359cc16dd9-Abstract.html)

### 2016
- [Sac d'astuces pour une classification de texte efficace](https://arxiv.org/abs/1607.01759) 📄
- [Enrichir les vecteurs de mots avec des informations sur les sous-mots](https://arxiv.org/abs/1607.04606) 📄
- [Recherche approximative du voisin le plus proche efficace et robuste à l'aide de graphiques Hierarchical Navigable Small World](https://arxiv.org/abs/1603.09320)
- [Sur la recherche approximative d'incorporations de mots similaires](https://www.aclweb.org/anthology/P16-1214.pdf) 
- [Apprendre des représentations distribuées de phrases à partir de données non étiquetées](https://arxiv.org/abs/1602.03483)📄
- [Recherche approximative du voisin le plus proche sur des données de grande dimension --- Expériences, analyses et améliorations](https://arxiv.org/abs/1610.02455)

### 2017
- [Supervised Learning of Universal Sentence Representations from Natural Language Inference Data](https://research.fb.com/wp-content/uploads/2017/09/emnlp2017.pdf) 📄

### 2018
- [Encodeur de phrases universel](https://arxiv.org/pdf/1803.11175.pdf) 📄
- [Apprendre la similarité textuelle sémantique à partir de conversations](https://arxiv.org/pdf/1804.07754.pdf) 📄
- [Google AI Blog : Avancées en matière de similarité textuelle sémantique](https://ai.googleblog.com/2018/05/advances-in-semantic-textual-similarity.html) 📄
- [Optimisation de l'indexation basée sur le graphique du k-plus proche voisin pour la recherche de proximité dans les données de grande dimension](https://arxiv.org/abs/1810.07355)
- [Recherche rapide approximative du voisin le plus proche avec le Navigation dans le graphique d'étalement](http://www.vldb.org/pvldb/vol12/p461-fu.pdf)
- [Le cas des structures d'index apprises](https://dl.acm.org/doi/10.1145/3183713.3196909)

### 2019
- [LASER : représentations de phrases indépendantes du langage](https://engineering.fb.com/2019/01/22/ai-research/laser-multilingual-sentence-embeddings/) 📄
- [Extension de document par prédiction de requête](https://arxiv.org/abs/1904.08375) 📄
- [Sentence-BERT : incorporations de phrases utilisant les réseaux BERT siamois](https://arxiv.org/pdf/1908.10084.pdf) 📄
- [Classement des documents en plusieurs étapes avec BERT](https://arxiv.org/abs/1910.14424) 📄
- [Récupération latente pour la réponse aux questions de domaine ouvert faiblement supervisé](https://arxiv.org/abs/1906.00300)
- [Réponse aux questions de bout en bout en domaine ouvert avec BERTserini](https://www.aclweb.org/anthology/N19-4013/)
- [BioBERT : un modèle de représentation du langage biomédical pré-entraîné pour l'exploration de textes biomédicaux](https://arxiv.org/abs/1901.08746)📄
- [Analyser et améliorer les représentations avec la perte douce du plus proche voisin](https://arxiv.org/pdf/1902.01889.pdf)📷
- [DiskANN : rapide et précis au milliard de points le plus proche Recherche de voisins sur un seul nœud](https://proceedings.neurips.cc/paper/2019/file/09853c7fb1d3f8ee67a61b6bf4a7f8e6-Paper.pdf)

### 2020
- [Déploiement rapide d'un moteur de recherche neuronal pour l'ensemble de données de recherche ouvert COVID-19 : réflexions préliminaires et leçons apprises](https://arxiv.org/abs/2004.05125) 📄
- [PASSAGE RECLASSEMENT AVEC BERT](https://arxiv.org/pdf/1901.04085.pdf) 📄
- [CO-Search : Récupération d'informations COVID-19 avec recherche sémantique, réponse aux questions et résumé abstrait](https://arxiv.org/pdf/2006.09595.pdf) 📄
- [LaBSE : intégration de phrases BERT indépendante de la langue](https://arxiv.org/abs/2007.01852) 📄
- [Covidex : modèles de classement neuronal et infrastructure de recherche de mots clés pour l'ensemble de données de recherche ouvert COVID-19](https://arxiv.org/abs/2007.07846) 📄
- [DeTect : un framework NLP approfondi pour une compréhension de texte intelligente](https://engineering.linkedin.com/blog/2020/open-sourcing-detext) 📄
- [Faire des inclusions de phrases unilingues multilingues à l'aide de la distillation des connaissances](https://arxiv.org/pdf/2004.09813.pdf) 📄
- [Transformateurs préformés pour le classement des textes : BERT et au-delà](https://arxiv.org/abs/2010.06467) 📄
- [REALM : pré-formation sur le modèle de langage amélioré par la récupération](https://arxiv.org/abs/2002.08909)
- [ELECTRA : LES ENCODEURS DE TEXTE DE PRÉ-FORMATION COMME DES DISCRIMINATEURS PLUTT QUE DES GÉNÉRATEURS](https://openreview.net/pdf?id=r1xMH1BtvB)📄
- [Améliorer l'apprentissage en profondeur pour la recherche Airbnb](https://arxiv.org/pdf/2002.05515)
- [Gérer la diversité dans la recherche Airbnb](https://arxiv.org/abs/2004.02621)📄
- [Apprentissage par contraste négatif approximatif du voisin le plus proche pour une recherche de texte dense](https://arxiv.org/abs/2007.00808v1)📄
### 2021
- [Approche hybride pour le calcul de similarité sémantique entre les mots tamouls](https://www.researchgate.net/publication/350112163_Hybrid_approach_for_semantic_similarity_calculation_between_Tamil_words) 📄
- [SBERT augmenté](https://arxiv.org/pdf/2010.08240.pdf) 📄
- [BEIR : une référence hétérogène pour l'évaluation à zéro des modèles de recherche d'informations](https://arxiv.org/abs/2104.08663) 📄
- [Recherche visuelle hétérogène tenant compte de la compatibilité](https://arxiv.org/abs/2105.06047) 📷
- [Apprendre le style personnel à partir de quelques exemples](https://chuanenlin.com/personalstyle)📷
- [TSDAE : Utilisation de l'encodeur automatique à débruitage séquentiel basé sur un transformateur pour l'apprentissage par incorporation de phrases non supervisé](https://arxiv.org/abs/2104.06979)📄
- [Une enquête sur les transformateurs](https://arxiv.org/abs/2106.04554)📄📷
- [Suggestions de requêtes de recherche associées de haute qualité à l'aide de l'apprentissage par renforcement approfondi](https://arxiv.org/abs/2108.04452v1)
- [Récupération de produits basée sur l'intégration dans la recherche Taobao](https://arxiv.org/pdf/2106.09297.pdf)📄📷
- [TPRM : un modèle de classement personnalisé basé sur des sujets pour la recherche sur le Web](https://arxiv.org/abs/2108.06014)📄
- [mMARCO : une version multilingue de l'ensemble de données de classement de passage MSMARCO](https://arxiv.org/abs/2108.13897)📄
- [Raisonnement de base de données sur le texte](https://aclanthology.org/2021.acl-long.241.pdf)📄
- [Comment le réglage fin accusatoire profite-t-il à BERT ?](https://arxiv.org/abs/2108.13602))📄
- [Train Short, Test Long : l'attention avec les biais linéaires permet l'extrapolation de la longueur d'entrée](https://arxiv.org/abs/2108.12409)📄
- [Introduction : À la recherche de transformateurs efficaces pour la modélisation du langage](https://arxiv.org/abs/2109.08668)📄
- [À quel point cela semble-t-il familier ? Représentation multilingue Analyse de similarité des plongements de mots acoustiques](https://arxiv.org/pdf/2109.10179.pdf)🔊
- [SimCSE : Apprentissage Contrastif Simple des Incorporations de Phrases](https://arxiv.org/abs/2104.08821#)📄
- [Attention compositionnelle : démêler la recherche et la récupération](https://arxiv.org/abs/2110.09419)📄📷
- [SPANN : recherche très efficace du voisin le plus proche à l'échelle d'un milliard](https://arxiv.org/abs/2111.08566)

## Des articles
- [S'attaquer à la recherche sémantique](https://adityamalte.substack.com/p/tackle-semantic-search/)
- [Recherche sémantique dans Azure Congnitive Search](https://docs.microsoft.com/en-us/azure/search/semantic-search-overview)
- [Comment nous avons utilisé la recherche sémantique pour rendre notre recherche 10 fois plus intelligente](https://zilliz.com/blog/How-we-used-semantic-search-to-make-our-search-10-x-smarter/)
- [Construire un moteur de recherche sémantique avec des inclusions de mots à double espace](https://m.mage.ai/building-a-semantic-search-engine-with-dual-space-word-embeddings-f5a596eb6d90)
- [Recherche de similarité sémantique à l'échelle d'un milliard avec FAISS+SBERT](https://towardsdatascience.com/billion-scale-semantic-similarity-search-with-faiss-sbert-c845614962e2)
- [Quelques observations sur les seuils de recherche de similarité](https://greglandrum.github.io/rdkit-blog/similarity/reference/2021/05/26/similarity-threshold-observations1.html)
- [Recherche d'images presque en double à l'aide du hachage sensible à la localité](https://keras.io/examples/vision/near_dup_search/)
- [Cours gratuit sur la recherche de similarité vectorielle et Faiss](https://link.medium.com/HtFoFKlKvkb)
- [Guide complet des algorithmes approximatifs des voisins les plus proches](https://link.medium.com/V62Z8drvEkb)
## Bibliothèques et outils
- [fastText](https://fasttext.cc/)
- [Universal Sentence Encoder](https://tfhub.dev/google/universal-sentence-encoder/4)
- [SBERT](https://www.sbert.net/)
- [ELECTRA](https://github.com/google-research/electra)
- [LaBSE](https://tfhub.dev/google/LaBSE/2)
- [LASER](https://github.com/facebookresearch/LASER)
- [Haystack](https://github.com/deepset-ai/haystack/)
- [Jina.AI](https://jina.ai/)
- [SentEval Toolkit](https://github.com/facebookresearch/SentEval?utm_source=catalyzex.com)
- [BEIR :Benchmarking IR](https://github.com/UKPLab/beir)
- [matchzoo-py](https://github.com/NTMC-Community/MatchZoo-py)
- [deep_text_matching](https://github.com/wangle1218/deep_text_matching)
- [Which Frame?](http://whichframe.com/)
- [PySerini](https://github.com/castorini/pyserini)
- [BERTSerini](https://github.com/rsvp-ai/bertserini)
- [BERTSimilarity](https://github.com/Brokenwind/BertSimilarity)
- [milvus](https://www.milvus.io/)
- [weaviate](https://github.com/semi-technologies/weaviate)
- [natural-language-youtube-search](https://github.com/haltakov/natural-language-youtube-search)
- [same.energy](https://www.same.energy/about)
- [scaNN](https://github.com/google-research/google-research/tree/master/scann)
- [REALM](https://github.com/google-research/language/tree/master/language/realm)
- [annoy](https://github.com/spotify/annoy)
- [nsg](https://github.com/ZJULearning/nsg)
- [FALCONN](https://github.com/FALCONN-LIB/FALCONN)
- [redis HNSW](https://github.com/zhao-lang/redis_hnsw)
- [autofaiss](https://github.com/criteo/autofaiss)
- [DPR](https://github.com/facebookresearch/DPR)
- [rank_BM25](https://github.com/dorianbrown/rank_bm25)
- [nearPy](http://pixelogik.github.io/NearPy/)
- [vearch](https://github.com/vearch/vearch)
- [PyNNDescent](https://github.com/lmcinnes/pynndescent)
- [pgANN](https://github.com/netrasys/pgANN)
- [Tensorflow Similarity](https://github.com/tensorflow/similarity)
- [opensemanticsearch.org](https://www.opensemanticsearch.org/)
- [GPT3 Semantic Search](https://gpt3demo.com/category/semantic-search)
- [searchy](https://github.com/lubianat/searchy)
- [txtai](https://github.com/neuml/txtai)
- [HyperTag](https://github.com/Ravn-Tech/HyperTag)
- [vectorai](https://github.com/vector-ai/vectorai)
- [embeddinghub](https://github.com/featureform/embeddinghub)
- [AquilaDb](https://github.com/Aquila-Network/AquilaDB)
## Ensembles de données
- [Hub de jeu de données de similarité de texte sémantique](https://github.com/brmson/dataset-sts)
- [Défi de similarité d'image Facebook AI](https://www.drivendata.org/competitions/79/competition-image-similarity-1-dev/?fbclid=IwAR31vRV0EdxRdrxtPy12neZtBJQ0H9qdLHm8Wl2DjHY09PtQdn1nEEIJVUo)
- [WIT : Ensemble de données de texte d'image basé sur Wikipédia](https://github.com/google-research-datasets/wit)
## Étapes importantes

Jetez un œil au [comité de projet](https://github.com/Agrover112/awesome-semantic-search/projects/1) pour que la liste des tâches contribue à l'un des problèmes ouverts.
