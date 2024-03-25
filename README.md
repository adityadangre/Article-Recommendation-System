# Article-Recommender-System
The objective is to recommend relevant items for users, based on their preference. Preference and relevance are subjective, and they are generally inferred by items users have consumed previously.

There are three main category of recommender systems:

Content-Based Filtering: This method uses attributes of the items to model similarity of items or user's preferences (based on previousely consumed items). In other words, these algorithms try to recommend items that are similar to those that a user liked in the past (or is examining in the present). In particular, various candidate items are compared with items previously rated by the user and the best-matching (ranked) items are recommended.

Collaborative Filtering: This method filters items to model interests of a user by collecting preferences or taste information from other users collaboration. The underlying assumption of the collaborative filtering approach is that if a person A has the same opinion as a person B on a set of items, A is more likely to have B's opinion for a given item than that of a randomly chosen person.

Hybrid methods: Recent research has demonstrated that a hybrid approach, combining collaborative filtering and content-based filtering could be more effective than pure approaches in some cases. These methods can also be used to overcome some of the common problems in recommender systems such as cold start and the sparsity problem.
