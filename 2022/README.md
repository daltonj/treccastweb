# 2022 Topics Overview

For CAsT year 4, topics are represented as a tree containing one or more conversation paths. 
Each turn within a topic (asides the first) have a `parent_turn` field through which each conversation path can be traced.

The contents of this directory are as follows:

- The file `2022_automatic_evaluation_topics_tree_v1.0.json` contains each conversation tree (topic) with an automatic rewrite generated for each user utterance.
- The file `2022_evaluation_topics_turn_ids.json` contains each conversation tree (topic) with the gold standard rewrite for each manual utterance.
- The file `2022_evaluation_topics_tree_v1.0.json` contains all ids that responses/ranked passages need to be returned for.