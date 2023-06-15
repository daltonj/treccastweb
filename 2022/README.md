# 2022 Topics Overview

For CAsT year 4, topics are represented as a tree containing one or more conversation paths. 
Each turn within a topic (asides the first) have a `parent_turn` field through which each conversation path can be traced.

The contents of this directory are as follows:

- The file `2022_automatic_evaluation_topics_tree_v1.0.json` contains each conversation tree (topic) with an automatic rewrite generated for each user utterance.
- The file `2022_evaluation_topics_turn_ids.json` contains each conversation tree (topic) with the resolved query for each user utterance.
- The file `2022_evaluation_topics_tree_v1.0.json` contains all ids that responses/ranked passages need to be returned for.
- The file `2022_evaluation_topics_flattened_duplicated_v1.0.json` contains all possible conversation paths across all the conversation trees.
- The file `2022_mixed_initiative_question_pool.json` contains the question pool for the mixed initiative sub task

## Other Resources

- [CAsT++](https://docs.google.com/document/d/1dWNhZiqCyvq9NJHmfm4qOLGMdLQ9Cdmr_jWrFqAc6Fc/edit?usp=sharing): Resources to evaluate clarification questions and responses.
