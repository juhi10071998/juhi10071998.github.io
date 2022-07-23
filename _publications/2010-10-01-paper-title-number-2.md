---
title: "WWBP-SQT-lite: Difference Embeddings and Multi-level Models for Moments of Change Identification in Mental Health Forums"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'This paper evaluates two approaches to capturing psychological changes in text: the first relies on computing the difference between the embedding of a message with the one that precedes it, the second relies on a "human-aware" multi-level recurrent transformer (HaRT).'
date: 2022-07-01
venue: 'CLPsych Task at North American Chapter of the ACL (Association for Computational Linguistics) [NAACL]'
paperurl: 'https://aclanthology.org/2022.clpsych-1.25.pdf'

Psychological states unfold dynamically; to understand and measure mental health at scale we
need to detect and measure these changes from
sequences of online posts. We evaluate two
approaches to capturing psychological changes
in text: the first relies on computing the difference between the embedding of a message
with the one that precedes it, the second relies
on a "human-aware" multi-level recurrent transformer (HaRT). The mood changes of timeline posts of users were annotated into three
classes, ‘ordinary,’ ‘switching’ (positive to negative or vice versa) and ‘escalations’ (increasing in intensity). For classifying these mood
changes, the difference-between-embeddings
technique – applied to RoBERTa embeddings
– showed the highest overall F1 score (0.61)
across the three different classes on the test
set. The technique particularly outperformed
the HaRT transformer (and other baselines) in
the detection of switches (F1 = .33) and escalations (F1 = .61). Consistent with the literature, the language use patterns associated
with mental-health related constructs in prior
work (including depression, stress, anger and
anxiety) predicted both mood switches and escalations.

[Download paper here](http://academicpages.github.io/files/paper2.pdf)
