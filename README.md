# Language-Understanding-and-Patronizing-Detection

This task is organized by SemEval 2022 Competition 

Patronizing and Condescending Language  (PCL) detection is difficult both for humans and NLP systems, due to its subtle nature, its subjectivity and the fair amount of world knowledge and commonsense reasoning required to understand this kind of language. With this task, we expect to push the boundaries of this new challenge in the NLP community.
About the task:
The minimum linguistic unit in this task is the paragraph (i.e., sentences in context). Paragraphs are extracted from news articles from a range of outlets. These paragraphs may contain one or more instances of PCL targeting a set of predefined vulnerable communities. This challenge is divided into two subtasks.

Subtask 1: Binary classification.
Given a paragraph, a system must predict whether or not it contains any form of PCL.
Examples
In the last week of April, 1,100 migrants died or went missing off Libya in nine separate incidents. - NO PCL
People across Australia ordered pizzas to be delivered on Saturday night, with the ample leftovers donated to local homeless shelters. - PCL



Subtask 2: Multi-label classification.
Given a paragraph, a system must identify which PCL categories express the condescension. Our PCL taxonomy has been defined based on previous works on PCL. We consider the following categories:
Unbalanced power relations. The author distances themselves from the community or the situation they are talking about and expresses the will, capacity or responsibility to help those in need. It is also present when the author entitles themselves to give something positive to others in a more vulnerable situation, especially when what the author concedes is a right which they do not have any authority to decide to give. 
Shallow solution. A simple and superficial charitable action by the privileged community is presented either as life-saving/life-changing for the unprivileged one or as a solution for a deep-rooted problem.
Presupposition. When the author assumes a situation as certain without having all the information or generalises their or somebody else’s experience as a categorical truth without presenting a valid, trustworthy source for it (e.g. a research work or survey). The use of stereotypes or clichés is also considered to be examples of presupposition.
Authority voice. When the author stands themselves as a spokesperson of the group, or ex-plains or advises the members of a community about the community itself or a specific situation they are living.
Metaphor. They can conceal PCL, as they cast an idea in another light, making a comparison between unrelated concepts, often with the objective of depicting a certain situation in a softer way. For the annotation of this dataset, euphemisms are considered as an example of metaphors.
Compassion. The author presents the vulnerable individual or community as needy, raising a feeling of pity and compassion from the audience towards them. It is commonly characterized by the use of flowery wording that does not provide information, but the author enjoys the detailed and poetic description of the vulnerability.
The poorer, the merrier. The text is focused on the community, especially on how the vulnerability makes them better (e.g. stronger, happier or more resilient) or how they share a positive attribute just for being part of a vulnerable community. People living in vulnerable situations have values to admire and learn from. The message expresses the idea of vulnerability as something beautiful o or poetic. We can think of the typical example of ‘poor people are happier because they don’t have material goods’. 
