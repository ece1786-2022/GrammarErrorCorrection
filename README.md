# GrammarErrorCorrection
baseline model folder:

baseline_model.ipynb: train the GPT-2 medium model and its inference and evaluation

train.txt, train_new.txt, valid.txt, valid_new.txt: split data set for gpt-2 training

data_collection folder:
data_collect.ipynb: retrieve real error patterns from FCE dataset and reverse them as perturbation schemes, apply perturbation on TOEFL writing

c4_200m_sub.csv: subset of C4 200M dataset

data_combine.csv: final dataset(combine cleaned C4 200M dataset with new created data)

fce.train.gold.bea19.m2: FCE dataset

new_create_data.csv: new created data

test.csv, test_combine.csv: our test data

tpo.txt: TOEFL writing sentences

t5_model folder:

grammar_correction_on_t5.ipynb: train several t5 model and their inference and evaluation

gradio_implementation.ipynb: gradio implementation of the baseline model and the t5-base model

