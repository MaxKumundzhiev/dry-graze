### Details: https://spacy.io/models/ru#ru_core_news_sm

Russian pipeline optimized for CPU. Components: tok2vec, morphologizer, parser, senter, ner, attribute_ruler, lemmatizer.

| Feature | Description |
| --- | --- |
| **Name** | `ru_core_news_sm` |
| **Version** | `3.7.0` |
| **spaCy** | `>=3.7.0,<3.8.0` |
| **Default Pipeline** | `tok2vec`, `morphologizer`, `parser`, `attribute_ruler`, `lemmatizer`, `ner` |
| **Components** | `tok2vec`, `morphologizer`, `parser`, `senter`, `attribute_ruler`, `lemmatizer`, `ner` |
| **Vectors** | 0 keys, 0 unique vectors (0 dimensions) |
| **Sources** | [Nerus](https://github.com/natasha/nerus) (Alexander Kukushkin) |
| **License** | `MIT` |
| **Author** | [Explosion](https://explosion.ai) |

### Label Scheme

<details>

<summary>View label scheme (900 labels for 3 components)</summary>

| Component | Labels |
| --- | --- |
| **`morphologizer`** | `Case=Nom\|Degree=Pos\|Number=Plur\|POS=ADJ`, `Animacy=Anim\|Case=Nom\|Gender=Masc\|Number=Plur\|POS=NOUN`, `Aspect=Perf\|Mood=Ind\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Act`, `Animacy=Inan\|Case=Acc\|POS=NUM`, `Animacy=Inan\|Case=Gen\|Gender=Fem\|Number=Plur\|POS=NOUN`, `Case=Gen\|Degree=Pos\|Gender=Masc\|Number=Sing\|POS=ADJ`, `Animacy=Inan\|Case=Gen\|Gender=Masc\|Number=Sing\|POS=NOUN`, `POS=ADP`, `Case=Gen\|Gender=Fem\|Number=Sing\|POS=DET`, `Animacy=Inan\|Case=Gen\|Gender=Fem\|Number=Sing\|POS=NOUN`, `POS=PUNCT`, `Degree=Pos\|POS=ADV`, `Aspect=Imp\|Mood=Ind\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Mid`, `Animacy=Inan\|Case=Nom\|Gender=Masc\|Number=Plur\|POS=NOUN`, `Animacy=Anim\|Case=Gen\|Gender=Masc\|Number=Plur\|POS=NOUN`, `Aspect=Perf\|Case=Gen\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Case=Loc\|Degree=Pos\|Number=Plur\|POS=ADJ`, `Animacy=Inan\|Case=Loc\|Gender=Neut\|Number=Plur\|POS=NOUN`, `Animacy=Inan\|Case=Loc\|Gender=Neut\|Number=Sing\|POS=PRON`, `Aspect=Imp\|Mood=Ind\|Number=Sing\|POS=VERB\|Person=Third\|Tense=Pres\|VerbForm=Fin\|Voice=Act`, `Animacy=Inan\|Case=Nom\|Gender=Neut\|Number=Sing\|POS=NOUN`, `Foreign=Yes\|POS=PROPN`, `Case=Loc\|Gender=Fem\|Number=Sing\|POS=NUM`, `Aspect=Imp\|Gender=Neut\|Mood=Ind\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Act`, `Animacy=Anim\|Case=Gen\|Gender=Masc\|Number=Sing\|POS=NOUN`, `Animacy=Inan\|Case=Loc\|Gender=Masc\|Number=Sing\|POS=NOUN`, `POS=NUM`, `Animacy=Inan\|Case=Gen\|Gender=Masc\|Number=Plur\|POS=NOUN`, `Case=Nom\|Gender=Masc\|Number=Sing\|POS=PRON\|Person=Third`, `Aspect=Imp\|Gender=Masc\|Mood=Ind\|Number=Sing\|POS=AUX\|Tense=Past\|VerbForm=Fin\|Voice=Act`, `Animacy=Anim\|Case=Ins\|Gender=Masc\|Number=Sing\|POS=NOUN`, `Animacy=Inan\|Case=Dat\|Gender=Neut\|Number=Sing\|POS=NOUN`, `POS=DET`, `Animacy=Inan\|Case=Nom\|Gender=Fem\|Number=Sing\|POS=NOUN`, `Aspect=Perf\|Gender=Fem\|Mood=Ind\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Act`, `Case=Dat\|Degree=Pos\|Number=Plur\|POS=ADJ`, `Animacy=Inan\|Case=Dat\|Gender=Fem\|Number=Plur\|POS=NOUN`, `Animacy=Inan\|Case=Nom\|Gender=Masc\|Number=Sing\|POS=NOUN`, `Aspect=Perf\|Gender=Masc\|Mood=Ind\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Act`, `POS=SCONJ`, `Animacy=Inan\|Case=Ins\|Gender=Neut\|Number=Sing\|POS=NOUN`, `Case=Acc\|Gender=Neut\|Number=Sing\|POS=PRON\|Person=Third`, `Case=Acc\|POS=NUM`, `Case=Ins\|Degree=Pos\|Number=Plur\|POS=ADJ`, `Animacy=Inan\|Case=Ins\|Gender=Masc\|Number=Plur\|POS=NOUN`, `POS=CCONJ`, `Case=Nom\|POS=NUM`, `Animacy=Inan\|Case=Dat\|Gender=Masc\|Number=Sing\|POS=NOUN`, `Aspect=Perf\|Gender=Masc\|Number=Sing\|POS=VERB\|StyleVariant=Short\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Case=Nom\|Degree=Pos\|Gender=Masc\|Number=Sing\|POS=ADJ`, `Case=Ins\|Degree=Pos\|Gender=Neut\|Number=Sing\|POS=ADJ`, `Aspect=Imp\|Mood=Ind\|Number=Plur\|POS=VERB\|Person=Third\|Tense=Pres\|VerbForm=Fin\|Voice=Act`, `Case=Nom\|Gender=Masc\|Number=Sing\|POS=DET`, `Aspect=Imp\|Gender=Masc\|Mood=Ind\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Act`, `Case=Acc\|Degree=Pos\|Gender=Fem\|Number=Sing\|POS=ADJ`, `Animacy=Inan\|Case=Acc\|Gender=Fem\|Number=Sing\|POS=NOUN`, `Case=Nom\|Gender=Fem\|Number=Sing\|POS=PRON`, `Aspect=Imp\|Mood=Ind\|Number=Sing\|POS=VERB\|Person=Third\|Tense=Pres\|VerbForm=Fin\|Voice=Mid`, `Case=Ins\|Degree=Pos\|Gender=Fem\|Number=Sing\|POS=ADJ`, `Animacy=Anim\|Case=Nom\|Gender=Fem\|Number=Sing\|POS=NOUN`, `Case=Dat\|Degree=Pos\|Gender=Fem\|Number=Sing\|POS=ADJ`, `Animacy=Inan\|Case=Dat\|Gender=Fem\|Number=Sing\|POS=NOUN`, `Animacy=Inan\|Case=Gen\|Gender=Neut\|Number=Sing\|POS=NOUN`, `Animacy=Inan\|Case=Nom\|Gender=Neut\|Number=Plur\|POS=NOUN`, `Degree=Pos\|Number=Plur\|POS=ADJ\|StyleVariant=Short`, `Aspect=Imp\|Mood=Ind\|Number=Plur\|POS=AUX\|Tense=Past\|VerbForm=Fin\|Voice=Act`, `Aspect=Perf\|POS=VERB\|VerbForm=Inf\|Voice=Act`, `Animacy=Inan\|Case=Acc\|Gender=Neut\|Number=Sing\|POS=PRON`, `Case=Loc\|Degree=Pos\|Gender=Fem\|Number=Sing\|POS=ADJ`, `Animacy=Inan\|Case=Loc\|Gender=Fem\|Number=Sing\|POS=NOUN`, `Animacy=Inan\|Case=Loc\|Gender=Masc\|Number=Plur\|POS=NOUN`, `Case=Gen\|Degree=Pos\|Gender=Fem\|Number=Sing\|POS=ADJ`, `Aspect=Perf\|Number=Plur\|POS=VERB\|StyleVariant=Short\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Animacy=Anim\|Case=Acc\|Gender=Masc\|POS=NUM`, `Animacy=Anim\|Case=Gen\|Gender=Fem\|Number=Plur\|POS=NOUN`, `Animacy=Anim\|Case=Acc\|Gender=Neut\|Number=Plur\|POS=NOUN`, `Mood=Cnd\|POS=SCONJ`, `Case=Nom\|Number=Plur\|POS=PRON\|Person=Third`, `POS=PART\|Polarity=Neg`, `Aspect=Imp\|POS=VERB\|VerbForm=Inf\|Voice=Mid`, `Animacy=Inan\|Aspect=Perf\|Case=Acc\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Animacy=Inan\|Case=Acc\|Gender=Fem\|Number=Plur\|POS=NOUN`, `POS=SPACE`, `Case=Nom\|Number=Plur\|POS=DET`, `Aspect=Imp\|Mood=Ind\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Act`, `Animacy=Anim\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=NOUN`, `Aspect=Imp\|Gender=Neut\|Mood=Ind\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Mid`, `Animacy=Inan\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=NOUN`, `Animacy=Anim\|Case=Acc\|Number=Plur\|POS=PRON`, `Animacy=Inan\|Case=Acc\|Gender=Neut\|Number=Sing\|POS=NOUN`, `Case=Gen\|Degree=Pos\|Gender=Neut\|Number=Sing\|POS=ADJ`, `Animacy=Anim\|Case=Gen\|Gender=Masc\|Number=Sing\|POS=PROPN`, `Animacy=Anim\|Case=Nom\|Gender=Fem\|Number=Sing\|POS=PROPN`, `Aspect=Imp\|Gender=Fem\|Mood=Ind\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Act`, `POS=INTJ`, `Animacy=Inan\|Case=Loc\|Gender=Fem\|Number=Plur\|POS=NOUN`, `Animacy=Inan\|Case=Nom\|Gender=Neut\|Number=Sing\|POS=PRON`, `Aspect=Imp\|Gender=Fem\|Mood=Ind\|Number=Sing\|POS=AUX\|Tense=Past\|VerbForm=Fin\|Voice=Act`, `Case=Nom\|Degree=Pos\|Gender=Fem\|Number=Sing\|POS=ADJ`, `Case=Acc\|Gender=Masc\|Number=Sing\|POS=PRON\|Person=Third`, `Case=Nom\|Number=Plur\|POS=PRON`, `Aspect=Imp\|Gender=Masc\|Mood=Ind\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Mid`, `Aspect=Imp\|Gender=Masc\|Mood=Ind\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Pass`, `Degree=Pos\|Gender=Fem\|Number=Sing\|POS=ADJ\|StyleVariant=Short`, `Case=Gen\|Gender=Masc\|Number=Sing\|POS=PRON\|Person=Third`, `Case=Gen\|POS=PRON`, `Animacy=Inan\|Case=Dat\|Gender=Neut\|Number=Plur\|POS=NOUN`, `Animacy=Anim\|Case=Nom\|Gender=Masc\|Number=Sing\|POS=PROPN`, `Aspect=Imp\|POS=VERB\|VerbForm=Inf\|Voice=Act`, `Animacy=Anim\|Case=Nom\|Gender=Masc\|Number=Sing\|POS=NOUN`, `Case=Acc\|Gender=Fem\|Number=Sing\|POS=PRON\|Person=Third`, `Animacy=Inan\|Case=Acc\|Number=Plur\|POS=DET`, `Case=Nom\|POS=PRON`, `Animacy=Anim\|Case=Ins\|Gender=Masc\|Number=Plur\|POS=NOUN`, `POS=ADJ`, `Case=Loc\|Degree=Pos\|Gender=Masc\|Number=Sing\|POS=ADJ`, `Animacy=Inan\|Case=Gen\|Gender=Fem\|Number=Sing\|POS=PROPN`, `Aspect=Imp\|Mood=Ind\|Number=Sing\|POS=AUX\|Person=Third\|Tense=Pres\|VerbForm=Fin\|Voice=Act`, `Case=Nom\|Gender=Fem\|Number=Sing\|POS=PRON\|Person=Third`, `Case=Ins\|Gender=Masc\|Number=Sing\|POS=DET`, `Animacy=Inan\|Case=Ins\|Gender=Masc\|Number=Sing\|POS=NOUN`, `Aspect=Perf\|Case=Acc\|Gender=Neut\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Animacy=Inan\|Case=Loc\|Gender=Neut\|Number=Sing\|POS=NOUN`, `Animacy=Inan\|Case=Gen\|Gender=Masc\|Number=Sing\|POS=PROPN`, `Case=Nom\|Number=Sing\|POS=PRON\|Person=First`, `Aspect=Imp\|Mood=Ind\|Number=Sing\|POS=VERB\|Person=First\|Tense=Pres\|VerbForm=Fin\|Voice=Act`, `Animacy=Inan\|Case=Acc\|Degree=Pos\|Gender=Masc\|Number=Sing\|POS=ADJ`, `Mood=Cnd\|POS=AUX`, `Case=Nom\|Number=Plur\|POS=PRON\|Person=First`, `Case=Gen\|Number=Plur\|POS=DET`, `Animacy=Inan\|Case=Ins\|Gender=Masc\|Number=Sing\|POS=PROPN`, `Aspect=Imp\|Case=Gen\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Animacy=Inan\|Case=Ins\|Gender=Neut\|Number=Sing\|POS=PRON`, `Aspect=Perf\|POS=VERB\|VerbForm=Inf\|Voice=Mid`, `Aspect=Perf\|Case=Gen\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Animacy=Inan\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=PROPN`, `Animacy=Inan\|Case=Acc\|Gender=Neut\|Number=Sing\|POS=DET`, `POS=PART`, `Case=Dat\|Gender=Masc\|Number=Sing\|POS=DET`, `Aspect=Perf\|Mood=Ind\|Number=Plur\|POS=VERB\|Person=Third\|Tense=Fut\|VerbForm=Fin\|Voice=Mid`, `Aspect=Perf\|Gender=Masc\|Mood=Ind\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Mid`, `Case=Nom\|Gender=Masc\|Number=Sing\|POS=NUM`, `Animacy=Anim\|Case=Dat\|Gender=Fem\|Number=Sing\|POS=PROPN`, `Aspect=Perf\|Mood=Ind\|Number=Sing\|POS=VERB\|Person=Third\|Tense=Fut\|VerbForm=Fin\|Voice=Mid`, `Case=Loc\|Gender=Masc\|Number=Sing\|POS=DET`, `Aspect=Perf\|Gender=Neut\|Mood=Ind\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Act`, `Degree=Pos\|Gender=Neut\|Number=Sing\|POS=ADJ\|StyleVariant=Short`, `Animacy=Inan\|Case=Gen\|Gender=Neut\|Number=Plur\|POS=NOUN`, `Animacy=Anim\|Case=Dat\|Gender=Masc\|Number=Sing\|POS=NOUN`, `Case=Nom\|Gender=Neut\|Number=Sing\|POS=PRON\|Person=Third`, `Aspect=Perf\|Gender=Neut\|Number=Sing\|POS=VERB\|StyleVariant=Short\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Animacy=Inan\|Case=Loc\|Gender=Fem\|Number=Sing\|POS=PROPN`, `Animacy=Inan\|Case=Acc\|Gender=Masc\|Number=Plur\|POS=NOUN`, `Aspect=Perf\|Mood=Ind\|Number=Plur\|POS=VERB\|Person=Third\|Tense=Fut\|VerbForm=Fin\|Voice=Act`, `Aspect=Perf\|Mood=Ind\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Mid`, `Animacy=Inan\|Case=Gen\|Gender=Neut\|Number=Sing\|POS=PRON`, `Aspect=Perf\|Case=Loc\|Gender=Neut\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Animacy=Inan\|Case=Loc\|Gender=Neut\|Number=Sing\|POS=PROPN`, `Case=Dat\|Degree=Pos\|Gender=Masc\|Number=Sing\|POS=ADJ`, `Animacy=Inan\|Case=Dat\|Gender=Masc\|Number=Plur\|POS=PROPN`, `Animacy=Inan\|Case=Acc\|Degree=Pos\|Number=Plur\|POS=ADJ`, `Animacy=Inan\|Case=Acc\|Gender=Neut\|Number=Plur\|POS=NOUN`, `Foreign=Yes\|POS=X`, `Animacy=Inan\|Case=Loc\|Gender=Masc\|Number=Sing\|POS=PROPN`, `Aspect=Imp\|POS=VERB\|Tense=Pres\|VerbForm=Conv\|Voice=Act`, `Case=Gen\|Degree=Pos\|Number=Plur\|POS=ADJ`, `Animacy=Inan\|Case=Ins\|Gender=Fem\|Number=Sing\|POS=NOUN`, `Aspect=Imp\|Gender=Neut\|Mood=Ind\|Number=Sing\|POS=AUX\|Tense=Past\|VerbForm=Fin\|Voice=Act`, `Case=Nom\|Degree=Pos\|Gender=Neut\|Number=Sing\|POS=ADJ`, `Aspect=Imp\|Case=Nom\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Case=Gen\|POS=NUM`, `Animacy=Inan\|Case=Acc\|Gender=Masc\|POS=NUM`, `Aspect=Imp\|Case=Gen\|Number=Plur\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Animacy=Inan\|Case=Ins\|Gender=Fem\|Number=Sing\|POS=PROPN`, `Animacy=Inan\|Case=Ins\|Gender=Neut\|Number=Sing\|POS=PROPN`, `Animacy=Inan\|Case=Nom\|Gender=Fem\|Number=Plur\|POS=NOUN`, `Aspect=Imp\|Mood=Ind\|Number=Sing\|POS=VERB\|Person=Third\|Tense=Pres\|VerbForm=Fin\|Voice=Pass`, `Aspect=Imp\|POS=VERB\|VerbForm=Inf\|Voice=Pass`, `Case=Gen\|Gender=Fem\|Number=Sing\|POS=NUM`, `Case=Ins\|Degree=Pos\|Gender=Masc\|Number=Sing\|POS=ADJ`, `Animacy=Inan\|Case=Acc\|Degree=Pos\|Gender=Neut\|Number=Sing\|POS=ADJ`, `Aspect=Perf\|Mood=Ind\|Number=Sing\|POS=VERB\|Person=Third\|Tense=Fut\|VerbForm=Fin\|Voice=Act`, `Animacy=Inan\|Case=Ins\|Gender=Neut\|Number=Plur\|POS=NOUN`, `Case=Loc\|Gender=Fem\|Number=Sing\|POS=DET`, `Animacy=Inan\|Case=Nom\|Gender=Masc\|Number=Sing\|POS=PROPN`, `Case=Loc\|Gender=Masc\|Number=Sing\|POS=PRON`, `Aspect=Perf\|Gender=Neut\|Mood=Ind\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Mid`, `Animacy=Anim\|Case=Dat\|Gender=Masc\|Number=Plur\|POS=NOUN`, `Animacy=Anim\|Case=Acc\|Gender=Masc\|Number=Plur\|POS=NOUN`, `Animacy=Anim\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=PROPN`, `Animacy=Anim\|Case=Ins\|Gender=Masc\|Number=Sing\|POS=PROPN`, `Aspect=Perf\|Case=Gen\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Animacy=Inan\|Case=Nom\|Gender=Fem\|Number=Sing\|POS=PROPN`, `Animacy=Inan\|Case=Acc\|Number=Plur\|POS=PRON\|Person=Third`, `Case=Nom\|Gender=Masc\|Number=Sing\|POS=PRON`, `Case=Dat\|POS=PRON`, `Aspect=Imp\|Mood=Ind\|Number=Plur\|POS=VERB\|Person=Third\|Tense=Pres\|VerbForm=Fin\|Voice=Mid`, `Animacy=Inan\|Case=Nom\|Gender=Neut\|Number=Sing\|POS=PROPN`, `Animacy=Inan\|Case=Nom\|Gender=Fem\|Number=Plur\|POS=PROPN`, `Case=Dat\|Gender=Fem\|Number=Sing\|POS=PRON`, `Case=Ins\|Number=Plur\|POS=PRON\|Person=Third`, `Animacy=Inan\|Case=Acc\|Gender=Fem\|Number=Sing\|POS=PROPN`, `Animacy=Inan\|Case=Dat\|Gender=Masc\|Number=Plur\|POS=NOUN`, `Aspect=Perf\|Case=Gen\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Aspect=Imp\|POS=AUX\|VerbForm=Inf\|Voice=Act`, `Aspect=Imp\|Mood=Ind\|Number=Plur\|POS=AUX\|Person=Third\|Tense=Pres\|VerbForm=Fin\|Voice=Act`, `Aspect=Imp\|Case=Gen\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Aspect=Perf\|Case=Dat\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Degree=Pos\|Gender=Masc\|Number=Sing\|POS=ADJ\|StyleVariant=Short`, `Degree=Cmp\|POS=ADV`, `Aspect=Perf\|Case=Loc\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Aspect=Imp\|Case=Ins\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Pass`, `Aspect=Perf\|Gender=Fem\|Mood=Ind\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Mid`, `Aspect=Imp\|Gender=Neut\|Mood=Ind\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Pass`, `Aspect=Imp\|Mood=Ind\|Number=Plur\|POS=AUX\|Person=First\|Tense=Pres\|VerbForm=Fin\|Voice=Act`, `Case=Ins\|Number=Plur\|POS=DET`, `Aspect=Perf\|Mood=Ind\|Number=Plur\|POS=VERB\|Person=First\|Tense=Fut\|VerbForm=Fin\|Voice=Act`, `Aspect=Imp\|Case=Acc\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Animacy=Inan\|Case=Dat\|Gender=Neut\|Number=Sing\|POS=PRON`, `Case=Loc\|Degree=Pos\|Gender=Neut\|Number=Sing\|POS=ADJ`, `Animacy=Inan\|Case=Gen\|Gender=Fem\|Number=Plur\|POS=PROPN`, `Case=Nom\|Gender=Neut\|Number=Sing\|POS=DET`, `Animacy=Inan\|Case=Gen\|Gender=Neut\|Number=Sing\|POS=PROPN`, `Aspect=Imp\|Case=Nom\|Number=Plur\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Case=Gen\|Gender=Masc\|POS=NUM`, `Animacy=Anim\|Case=Dat\|Gender=Fem\|Number=Sing\|POS=NOUN`, `Aspect=Imp\|Case=Ins\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Animacy=Anim\|Case=Ins\|Gender=Fem\|Number=Sing\|POS=NOUN`, `Aspect=Imp\|Case=Nom\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Aspect=Perf\|Gender=Fem\|Number=Sing\|POS=VERB\|StyleVariant=Short\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Aspect=Perf\|POS=VERB\|Tense=Past\|VerbForm=Conv\|Voice=Act`, `Aspect=Imp\|Case=Ins\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Pass`, `Case=Loc\|Gender=Neut\|Number=Sing\|POS=DET`, `Animacy=Anim\|Case=Gen\|Gender=Fem\|Number=Sing\|POS=NOUN`, `Animacy=Inan\|Case=Acc\|Gender=Neut\|Number=Sing\|POS=PROPN`, `Aspect=Imp\|Case=Loc\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Aspect=Imp\|Case=Dat\|Number=Plur\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Aspect=Perf\|Case=Nom\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Aspect=Perf\|Case=Loc\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Case=Dat\|Number=Sing\|POS=PRON\|Person=Second`, `Case=Nom\|Gender=Fem\|Number=Sing\|POS=DET`, `POS=ADV`, `Case=Acc\|POS=PRON`, `Animacy=Anim\|Case=Loc\|Gender=Masc\|Number=Sing\|POS=NOUN`, `Case=Ins\|Gender=Masc\|Number=Sing\|POS=NUM`, `Case=Ins\|POS=NUM`, `Aspect=Imp\|Mood=Ind\|Number=Plur\|POS=VERB\|Person=First\|Tense=Pres\|VerbForm=Fin\|Voice=Act`, `Aspect=Perf\|Case=Nom\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Animacy=Inan\|Case=Ins\|Gender=Fem\|Number=Plur\|POS=NOUN`, `Case=Gen\|Gender=Masc\|Number=Sing\|POS=DET`, `Aspect=Imp\|Case=Nom\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Animacy=Anim\|Case=Acc\|Degree=Pos\|Number=Plur\|POS=ADJ`, `Case=Dat\|Gender=Fem\|Number=Sing\|POS=PRON\|Person=Third`, `Case=Gen\|Gender=Masc\|Number=Sing\|POS=NUM`, `Case=Acc\|Gender=Masc\|Number=Sing\|POS=DET`, `Aspect=Perf\|Case=Ins\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Case=Loc\|POS=PRON`, `Animacy=Inan\|Case=Acc\|Degree=Pos\|Number=Plur\|POS=DET`, `Animacy=Inan\|Case=Dat\|Gender=Masc\|Number=Sing\|POS=PROPN`, `Case=Loc\|Gender=Masc\|Number=Sing\|POS=PRON\|Person=Third`, `Animacy=Anim\|Aspect=Perf\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Case=Loc\|Gender=Fem\|Number=Sing\|POS=PRON`, `Aspect=Perf\|Case=Ins\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Animacy=Anim\|Case=Acc\|Degree=Pos\|Gender=Masc\|Number=Sing\|POS=ADJ`, `Aspect=Imp\|Mood=Imp\|Number=Plur\|POS=VERB\|Person=Second\|VerbForm=Fin\|Voice=Act`, `Case=Nom\|Number=Plur\|POS=PRON\|Person=Second`, `Aspect=Perf\|Mood=Ind\|Number=Plur\|POS=VERB\|Person=Second\|Tense=Fut\|VerbForm=Fin\|Voice=Act`, `POS=SYM`, `Degree=Cmp\|POS=ADJ`, `Animacy=Inan\|Case=Dat\|Gender=Fem\|Number=Sing\|POS=PROPN`, `Aspect=Imp\|Case=Nom\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Pass`, `Case=Acc\|Gender=Masc\|POS=NUM`, `Animacy=Inan\|Case=Nom\|Gender=Masc\|Number=Plur\|POS=PROPN`, `Case=Nom\|Gender=Fem\|POS=NUM`, `Animacy=Inan\|Case=Loc\|Gender=Masc\|Number=Plur\|POS=PROPN`, `Animacy=Anim\|Case=Acc\|Gender=Fem\|Number=Sing\|POS=NOUN`, `Animacy=Anim\|Case=Acc\|Gender=Fem\|Number=Sing\|POS=PROPN`, `Aspect=Perf\|Case=Gen\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Animacy=Inan\|Case=Gen\|Gender=Masc\|Number=Plur\|POS=PROPN`, `Degree=Pos\|POS=ADJ`, `Case=Ins\|Degree=Sup\|Gender=Fem\|Number=Sing\|POS=ADJ`, `Animacy=Inan\|Case=Ins\|Gender=Masc\|Number=Plur\|POS=PROPN`, `Animacy=Anim\|Case=Dat\|Gender=Masc\|Number=Sing\|POS=PROPN`, `Aspect=Imp\|Mood=Ind\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Pass`, `Aspect=Imp\|Case=Acc\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Pass`, `Case=Gen\|Number=Plur\|POS=PRON\|Person=Third`, `Animacy=Inan\|Case=Acc\|Number=Plur\|POS=PRON`, `Animacy=Anim\|Case=Nom\|Gender=Neut\|Number=Plur\|POS=NOUN`, `Animacy=Anim\|Case=Gen\|Gender=Neut\|Number=Plur\|POS=NOUN`, `Degree=Pos\|Gender=Neut\|Number=Sing\|POS=PUNCT\|StyleVariant=Short`, `Case=Ins\|Degree=Sup\|Gender=Neut\|Number=Sing\|POS=ADJ`, `Aspect=Imp\|Case=Nom\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Pass`, `Animacy=Anim\|Case=Ins\|Gender=Fem\|Number=Plur\|POS=NOUN`, `Animacy=Anim\|Case=Acc\|Gender=Fem\|Number=Plur\|POS=NOUN`, `Case=Dat\|Degree=Pos\|Gender=Neut\|Number=Sing\|POS=ADJ`, `Animacy=Anim\|Case=Nom\|Gender=Fem\|Number=Plur\|POS=NOUN`, `Animacy=Anim\|Case=Dat\|Gender=Fem\|Number=Plur\|POS=NOUN`, `Animacy=Inan\|Case=Nom\|Gender=Neut\|Number=Sing\|POS=SCONJ`, `Case=Loc\|Gender=Neut\|Number=Sing\|POS=PRON`, `Aspect=Imp\|Case=Nom\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Aspect=Imp\|Gender=Fem\|Mood=Ind\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Mid`, `Aspect=Imp\|Mood=Ind\|Number=Sing\|POS=VERB\|Person=First\|Tense=Pres\|VerbForm=Fin\|Voice=Mid`, `Case=Dat\|Number=Sing\|POS=PRON\|Person=First`, `Case=Acc\|Gender=Fem\|Number=Sing\|POS=DET`, `Aspect=Imp\|Mood=Ind\|Number=Plur\|POS=VERB\|Person=Second\|Tense=Pres\|VerbForm=Fin\|Voice=Mid`, `POS=NOUN`, `Case=Dat\|Number=Plur\|POS=PRON\|Person=Third`, `Degree=Cmp\|POS=NUM`, `Case=Gen\|Gender=Neut\|Number=Sing\|POS=NUM`, `Aspect=Imp\|Case=Nom\|Number=Plur\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Pass`, `Case=Loc\|Number=Plur\|POS=DET`, `Aspect=Perf\|Case=Gen\|Gender=Neut\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Aspect=Perf\|Case=Nom\|Gender=Neut\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Case=Dat\|POS=NUM`, `Animacy=Anim\|Aspect=Imp\|Case=Acc\|Number=Plur\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Case=Ins\|Gender=Fem\|Number=Sing\|POS=PRON\|Person=Third`, `Animacy=Anim\|Case=Voc\|Gender=Masc\|Number=Sing\|POS=NOUN`, `Case=Gen\|Gender=Fem\|Number=Sing\|POS=PRON\|Person=Third`, `Case=Nom\|Degree=Pos\|Gender=Fem\|Number=Sing\|POS=NUM`, `Animacy=Anim\|Case=Gen\|Gender=Fem\|Number=Sing\|POS=PROPN`, `Animacy=Anim\|Case=Nom\|Gender=Neut\|Number=Sing\|POS=NOUN`, `Animacy=Inan\|Case=Acc\|Gender=Fem\|POS=NUM`, `Aspect=Perf\|Case=Loc\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Aspect=Perf\|Case=Acc\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Animacy=Anim\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=PRON`, `Case=Ins\|Gender=Fem\|Number=Sing\|POS=DET`, `Animacy=Anim\|Case=Gen\|Gender=Masc\|Number=Plur\|POS=PROPN`, `Animacy=Inan\|Case=Par\|Gender=Masc\|Number=Sing\|POS=NOUN`, `Aspect=Imp\|Gender=Fem\|Mood=Ind\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Fin\|Voice=Pass`, `Aspect=Perf\|Case=Nom\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Case=Gen\|Gender=Masc\|Number=Sing\|POS=PRON`, `Case=Gen\|Number=Plur\|POS=DET\|Person=Third`, `Animacy=Inan\|Case=Dat\|Gender=Neut\|Number=Sing\|POS=PROPN`, `Animacy=Inan\|Case=Gen\|Gender=Masc\|Number=Sing\|POS=ADV`, `Case=Nom\|Gender=Fem\|Number=Sing\|POS=NUM`, `Aspect=Perf\|Case=Loc\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Aspect=Imp\|Case=Gen\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Pass`, `Case=Nom\|Gender=Masc\|POS=NUM`, `Aspect=Imp\|Case=Dat\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Case=Loc\|Gender=Fem\|Number=Sing\|POS=PRON\|Person=Third`, `Animacy=Anim\|Case=Ins\|Gender=Neut\|Number=Plur\|POS=NOUN`, `Animacy=Inan\|Aspect=Perf\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Aspect=Imp\|Case=Nom\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Aspect=Perf\|Case=Gen\|Gender=Neut\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Case=Gen\|Gender=Fem\|POS=NUM`, `Animacy=Anim\|Aspect=Imp\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Aspect=Perf\|Case=Nom\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `POS=ADV\|Polarity=Neg`, `Case=Dat\|Gender=Neut\|Number=Sing\|POS=PRON`, `Aspect=Perf\|Case=Nom\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Case=Acc\|Gender=Neut\|POS=NUM`, `Aspect=Imp\|Mood=Imp\|Number=Sing\|POS=VERB\|Person=Second\|VerbForm=Fin\|Voice=Act`, `Case=Gen\|Number=Sing\|POS=PRON\|Person=First`, `Case=Nom\|Gender=Neut\|POS=NUM`, `Case=Gen\|POS=VERB\|Polarity=Neg`, `Aspect=Imp\|Mood=Ind\|Number=Plur\|POS=VERB\|Person=Second\|Tense=Pres\|VerbForm=Fin\|Voice=Act`, `Case=Gen\|Gender=Fem\|Number=Sing\|POS=PRON`, `Aspect=Imp\|Case=Dat\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Case=Loc\|Number=Plur\|POS=PRON`, `Case=Loc\|Number=Plur\|POS=PRON\|Person=Third`, `Case=Gen\|Number=Plur\|POS=PRON`, `Aspect=Perf\|Case=Dat\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Case=Acc\|Gender=Fem\|Number=Sing\|POS=NUM`, `Aspect=Imp\|Case=Dat\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Animacy=Inan\|Aspect=Perf\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `POS=CCONJ\|Polarity=Neg`, `Animacy=Inan\|Aspect=Imp\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Aspect=Imp\|Case=Gen\|Number=Plur\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Pass`, `Case=Ins\|Gender=Masc\|Number=Sing\|POS=PRON\|Person=Third`, `Case=Dat\|Gender=Neut\|Number=Sing\|POS=DET`, `Aspect=Imp\|Gender=Neut\|Mood=Ind\|Number=Sing\|POS=PRON\|Tense=Past\|VerbForm=Fin\|Voice=Act`, `Aspect=Imp\|POS=VERB\|Tense=Pres\|VerbForm=Conv\|Voice=Mid`, `Case=Gen\|Gender=Neut\|Number=Sing\|POS=DET`, `Case=Nom\|Number=Sing\|POS=PRON\|Person=Second`, `Aspect=Imp\|Mood=Ind\|Number=Sing\|POS=VERB\|Person=Second\|Tense=Pres\|VerbForm=Fin\|Voice=Act`, `Animacy=Inan\|Case=Loc\|Gender=Fem\|Number=Plur\|POS=PROPN`, `Aspect=Perf\|Case=Nom\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Aspect=Imp\|Mood=Ind\|Number=Plur\|POS=VERB\|Person=Third\|Tense=Pres\|VerbForm=Fin\|Voice=Pass`, `Case=Ins\|Gender=Neut\|Number=Sing\|POS=DET`, `Animacy=Anim\|Case=Acc\|POS=NUM`, `Aspect=Imp\|Number=Plur\|POS=VERB\|StyleVariant=Short\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Aspect=Imp\|Gender=Masc\|Number=Sing\|POS=VERB\|StyleVariant=Short\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Case=Dat\|Gender=Masc\|Number=Sing\|POS=PRON\|Person=Third`, `Case=Loc\|Gender=Masc\|Number=Sing\|POS=NUM`, `Case=Dat\|Gender=Masc\|Number=Sing\|POS=NUM`, `Aspect=Imp\|Case=Gen\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Animacy=Anim\|Case=Gen\|Gender=Neut\|Number=Sing\|POS=NOUN`, `Case=Loc\|Degree=Sup\|Gender=Masc\|Number=Sing\|POS=ADJ`, `Case=Gen\|Number=Plur\|POS=PRON\|Person=First`, `Case=Dat\|Number=Plur\|POS=PRON\|Person=First`, `Case=Gen\|Number=Plur\|POS=PRON\|Person=Second`, `Aspect=Perf\|Mood=Imp\|Number=Plur\|POS=VERB\|Person=Second\|VerbForm=Fin\|Voice=Act`, `Aspect=Perf\|Case=Acc\|Gender=Neut\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Case=Acc\|Number=Sing\|POS=PRON\|Person=First`, `Foreign=Yes\|POS=PUNCT`, `Aspect=Imp\|Mood=Ind\|Number=Sing\|POS=PRON\|Person=Third\|Tense=Pres\|VerbForm=Fin\|Voice=Act`, `Aspect=Imp\|Mood=Ind\|Number=Sing\|POS=AUX\|Person=First\|Tense=Pres\|VerbForm=Fin\|Voice=Act`, `Case=Gen\|Gender=Fem\|Number=Sing\|POS=DET\|Person=Third`, `Case=Dat\|Degree=Sup\|Number=Plur\|POS=ADJ`, `Aspect=Perf\|Case=Acc\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Aspect=Perf\|Case=Dat\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Case=Loc\|POS=NUM`, `Aspect=Imp\|Mood=Ind\|Number=Plur\|POS=VERB\|Person=First\|Tense=Pres\|VerbForm=Fin\|Voice=Mid`, `Case=Dat\|Number=Plur\|POS=DET`, `Aspect=Imp\|POS=AUX\|Tense=Pres\|VerbForm=Conv\|Voice=Act`, `Aspect=Perf\|Case=Ins\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Aspect=Imp\|Case=Nom\|Gender=Neut\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Case=Ins\|POS=PRON`, `Case=Ins\|Gender=Neut\|Number=Sing\|POS=PRON`, `Aspect=Perf\|Case=Loc\|Gender=Neut\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Case=Dat\|Gender=Neut\|Number=Sing\|POS=PRON\|Person=Third`, `Aspect=Imp\|Mood=Imp\|Number=Sing\|POS=VERB\|Person=Second\|VerbForm=Fin\|Voice=Mid`, `Case=Nom\|Gender=Neut\|Number=Sing\|POS=PRON`, `Animacy=Inan\|Aspect=Imp\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `POS=PROPN`, `Aspect=Perf\|Case=Loc\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Aspect=Imp\|Case=Gen\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Pass`, `Aspect=Perf\|Mood=Ind\|Number=Sing\|POS=VERB\|Person=Second\|Tense=Fut\|VerbForm=Fin\|Voice=Act`, `Case=Gen\|Degree=Sup\|Number=Plur\|POS=ADJ`, `Animacy=Anim\|Case=Ins\|Gender=Fem\|Number=Sing\|POS=PROPN`, `Animacy=Inan\|Case=Ins\|Gender=Fem\|Number=Plur\|POS=PROPN`, `Case=Ins\|Number=Plur\|POS=PRON\|Person=Second`, `Case=Gen\|Gender=Neut\|Number=Sing\|POS=PRON\|Person=Third`, `Animacy=Anim\|Case=Loc\|Gender=Fem\|Number=Sing\|POS=NOUN`, `Aspect=Imp\|Case=Ins\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Animacy=Inan\|Aspect=Imp\|Case=Acc\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Aspect=Imp\|Case=Dat\|Number=Plur\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Pass`, `Aspect=Imp\|Case=Loc\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Pass`, `Case=Ins\|Number=Sing\|POS=PRON\|Person=First`, `Aspect=Imp\|Case=Acc\|Gender=Neut\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Aspect=Imp\|Case=Loc\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Case=Loc\|Degree=Pos\|Gender=Masc\|Number=Sing\|POS=DET`, `Case=Gen\|Gender=Masc\|Number=Sing\|POS=DET\|Person=Third`, `Aspect=Imp\|Case=Nom\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Aspect=Imp\|Case=Gen\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Case=Ins\|Gender=Fem\|Number=Sing\|POS=NUM`, `Animacy=Inan\|Case=Gen\|Gender=Fem\|Number=Sing\|POS=PUNCT`, `Animacy=Anim\|Case=Dat\|Gender=Neut\|Number=Plur\|POS=NOUN`, `Aspect=Imp\|Case=Ins\|Number=Plur\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Aspect=Imp\|Case=Loc\|Gender=Neut\|Number=Sing\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Case=Ins\|Gender=Masc\|Number=Sing\|POS=PRON`, `Animacy=Anim\|Aspect=Imp\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Aspect=Perf\|Case=Ins\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Animacy=Inan\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=PRON`, `Animacy=Inan\|Case=Acc\|Number=Plur\|POS=PRON\|Person=First`, `Animacy=Anim\|Aspect=Perf\|Case=Acc\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Aspect=Imp\|Case=Gen\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Animacy=Inan\|Aspect=Imp\|Case=Acc\|Number=Plur\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Animacy=Anim\|Case=Acc\|Gender=Neut\|Number=Sing\|POS=NOUN`, `Case=Ins\|Number=Sing\|POS=PRON\|Person=Second`, `Aspect=Perf\|Case=Dat\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Case=Dat\|Gender=Fem\|Number=Sing\|POS=DET`, `Animacy=Anim\|Aspect=Perf\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Case=Acc\|Gender=Fem\|Number=Sing\|POS=PRON`, `Aspect=Perf\|Case=Dat\|Gender=Neut\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Case=Nom\|Degree=Sup\|Gender=Masc\|Number=Sing\|POS=ADJ`, `Animacy=Inan\|Case=Acc\|Degree=Sup\|Gender=Masc\|Number=Sing\|POS=ADJ`, `Aspect=Imp\|Case=Loc\|Number=Plur\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Pass`, `Case=Dat\|Number=Plur\|POS=PRON`, `Animacy=Inan\|Case=Ins\|Gender=Neut\|Number=Plur\|POS=PROPN`, `Animacy=Anim\|Case=Loc\|Gender=Masc\|Number=Sing\|POS=PROPN`, `Animacy=Anim\|Case=Gen\|Number=Plur\|POS=DET`, `Aspect=Perf\|Case=Gen\|Gender=Fem\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Animacy=Inan\|Case=Acc\|Gender=Masc\|Number=Plur\|POS=PROPN`, `Case=Ins\|Degree=Sup\|Number=Plur\|POS=ADJ`, `Case=Ins\|Degree=Pos\|Gender=Fem\|Number=Sing\|POS=DET`, `Case=Dat\|Degree=Sup\|Gender=Masc\|Number=Sing\|POS=ADJ`, `Animacy=Anim\|Case=Nom\|Gender=Masc\|Number=Sing\|POS=ADV`, `Foreign=Yes\|POS=PART`, `Case=Gen\|Gender=Neut\|Number=Sing\|POS=PRON`, `Aspect=Perf\|Mood=Ind\|Number=Sing\|POS=VERB\|Person=First\|Tense=Fut\|VerbForm=Fin\|Voice=Act`, `Case=Gen\|Degree=Sup\|Gender=Masc\|Number=Sing\|POS=ADJ`, `Animacy=Inan\|Aspect=Imp\|Case=Acc\|Number=Plur\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Pass`, `Animacy=Inan\|Case=Dat\|Gender=Fem\|Number=Plur\|POS=PROPN`, `Case=Nom\|Degree=Pos\|Number=Plur\|POS=DET`, `Case=Loc\|Gender=Fem\|POS=NUM`, `Animacy=Anim\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=DET`, `Aspect=Perf\|POS=VERB\|Tense=Past\|VerbForm=Conv\|Voice=Mid`, `Aspect=Imp\|Case=Loc\|Number=Plur\|POS=VERB\|Tense=Pres\|VerbForm=Part\|Voice=Act`, `Animacy=Inan\|Case=Gen\|Gender=Masc\|Number=Sing\|POS=PUNCT`, `Animacy=Anim\|Case=Loc\|Gender=Fem\|Number=Sing\|POS=PROPN`, `Aspect=Perf\|Case=Ins\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Case=Acc\|Degree=Pos\|Gender=Fem\|Number=Sing\|POS=DET`, `Aspect=Perf\|Case=Ins\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Animacy=Inan\|Case=Acc\|Gender=Masc\|Number=Sing\|POS=DET`, `Animacy=Anim\|Aspect=Imp\|Case=Acc\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Case=Loc\|Gender=Neut\|Number=Sing\|POS=PRON\|Person=Third`, `Case=Acc\|Degree=Pos\|Gender=Fem\|Number=Sing\|POS=PUNCT`, `Aspect=Imp\|Case=Nom\|Gender=Neut\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Animacy=Anim\|Case=Loc\|Gender=Masc\|Number=Plur\|POS=NOUN`, `Aspect=Perf\|Case=Nom\|Gender=Neut\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Pass`, `Animacy=Inan\|Aspect=Perf\|Case=Acc\|Number=Plur\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Animacy=Inan\|Case=Ins\|Gender=Fem\|Number=Sing\|POS=ADV`, `Case=Nom\|Degree=Pos\|Gender=Masc\|Number=Sing\|POS=DET`, `Aspect=Imp\|Case=Loc\|Gender=Masc\|Number=Sing\|POS=VERB\|Tense=Past\|VerbForm=Part\|Voice=Act`, `Aspect=Perf\|Mood=Ind\|Number=Plur\|POS=VERB\|Person=First\|Tense=Fut\|VerbForm=Fin\|Voice=Mid`, `Case=Nom\|Degree=Sup\|Number=Plur\|POS=ADJ`, `Aspect=Perf\|Mood=Imp\|Number=Sing\|POS=VERB\|Person=Second\|VerbForm=Fin\|Voice=Act`, `Case=Nom\|Degree=Pos\|Gender=Fem\|Number=Sing\|POS=DET`, `Case=Loc\|Number=Sing\|POS=PRON\|Person=First`, _(truncated: full list in pipeline meta)_ |
| **`parser`** | `ROOT`, `acl`, `acl:relcl`, `advcl`, `advmod`, `amod`, `appos`, `aux`, `aux:pass`, `case`, `cc`, `ccomp`, `compound`, `conj`, `cop`, `csubj`, `csubj:pass`, `dep`, `det`, `discourse`, `expl`, `fixed`, `flat`, `flat:foreign`, `flat:name`, `iobj`, `list`, `mark`, `nmod`, `nsubj`, `nsubj:pass`, `nummod`, `nummod:entity`, `nummod:gov`, `obj`, `obl`, `obl:agent`, `orphan`, `parataxis`, `punct`, `xcomp` |
| **`ner`** | `LOC`, `ORG`, `PER` |

</details>

### Accuracy

| Type | Score |
| --- | --- |
| `TOKEN_ACC` | 99.68 |
| `TOKEN_P` | 97.28 |
| `TOKEN_R` | 98.31 |
| `TOKEN_F` | 97.79 |
| `POS_ACC` | 98.77 |
| `MORPH_ACC` | 97.03 |
| `MORPH_MICRO_P` | 98.68 |
| `MORPH_MICRO_R` | 97.98 |
| `MORPH_MICRO_F` | 98.33 |
| `SENTS_P` | 99.89 |
| `SENTS_R` | 99.89 |
| `SENTS_F` | 99.89 |
| `DEP_UAS` | 95.87 |
| `DEP_LAS` | 94.62 |
| `TAG_ACC` | 98.77 |
| `LEMMA_ACC` | 0.00 |
| `ENTS_P` | 94.88 |
| `ENTS_R` | 95.09 |
| `ENTS_F` | 94.98 |