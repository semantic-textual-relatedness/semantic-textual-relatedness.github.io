
<center>

#   ** Semantic Textual Relatedness Task** 
SemEval 2024 Task 1: Semantic Textual Relatedness 

> Part of the [18th International Workshop on Semantic Evaluation](https://semeval.github.io/SemEval2024/tasks.html)

<!-- 
<center> -->
> Contact organizers at: [semrel@googlegroups.com](mailto:https://groups.google.com/d/forum/semrel-semeval-organisers)
<!-- 
<center> -->

> [Join Task Slack Group](https://join.slack.com/t/slack-1ga9972/shared_invite/zt-1z8um0fdi-ddx5VWCxvw~kcpTkuAXwrQ)


<!-- <center> -->


<!-- >  [Visit CodaLab competition website](https://codalab.lisn.upsaclay.fr/competitions/7320) -->

<!-- <font size=3> <span style="color: blue;"> AfriSenti dataset is available at task's:[GitHub repo](https://github.com/afrisenti-semeval/afrisent-semeval-2023) </span> </font>
 -->

</center>


---
## **Motivation**

The semantic relatedness of two language units has long been considered fundamental to understanding meaning (<cite>George,A Miller, 1991</cite>), and automatically determining relatedness has many applications such as evaluating sentence representation methods, question answering, and summarization (<cite>abdalla,2021</cite>).

Two sentences are considered semantically similar when they have a paraphrasal or entailment relation (e.g., <span style='color: blue;'>The boy scored the winning goal.</span>, <span style='color: blue;'>The boy scored the winning goal.</span>) On the other hand, relatedness is a much broader concept that accounts for all the commonalities between two sentences. For example  <span style='color: blue;'>The boy scored the winning goal </span> and <span style='color: blue;'>The boy's team moved onto the finals </span> would be related though not similar. 

<p>
However, much of past NLP work is on semantic similarity, and largely focused on English. In this shared task, we have covered 14 languages predominantly from Africa and Asia (Algerian Arabic, Amharic, English, Hausa, Hindi, Indonesian, Kinyarwanda, Makhuwa, Modern Standard Arabic (MSA), Morrocan Arabic, Mozambican Portuguese, Punjabi, Spanish, and Yoruba). .</p>

## **Task Overview**
<p>The <strong> Semantic Textual Relatedness Shared Task 1</strong> 
is the task of predicting semantic textual relatedness (STR) of sentence pairs. Participants will rank sentence pairs by their closeness in meaning (i.e., their degree of semantic relatedness) in 14 languages predominantly from Africa and Asia. All sentence pairs will have manually determined relatedness scores between 0 (completely unrelated) and 1 (maximally related). It consists of two sub-tasks. Participants can select one or more sub-tasks depending on their preference.</p>



<p><strong>Task B: Supervised</strong></p>
</blockquote>
<p> In this subtask, participants submit systems that have been trained using the provided labeled datasets (with scores ranging from 0 to 1 representing the degree of semantic textual relatedness). These datasets contain pairs of sentences that have been manually scored based on their degree of relatedness.</p>



<blockquote>
<p><strong>Task A: Unsupervised</strong></p>
</blockquote>
<p> In this subtask, participants are expected to submit systems that have been developed without the use of any labeled datasets pertaining to semantic relatedness. </p>

## **Important Dates**

| Descriptions                 | Deadlines                                    |
| ---------------------------- | -------------------------------------------- |
| Sample Data Ready            | <s>15 July 2022</s>                          |
| Training Data Ready          | 01 September 2023                            |
| Evaluation Start             | 10 January 2024                              |
| Evaluation End               | 31 January 2024                              |
| System Description Paper Due | 29 February 2024                             |
| Notification to authors      | 1 April 2024                                 |
| Camera ready due             | 22 April 2024                                |
| SemEval workshop 2023        | TBD (co-located with a major NLP conference) |

All deadlines are 23:59 UTC-12 ("anywhere on Earth").

## **Dataset**

<!-- ## **Communication**

- Join [Task Mailing List](https://groups.google.com/g/afrisenti-semeval)
- Join [Task Slack Channel](https://join.slack.com/t/afrisenti-semeval/shared_invite/zt-1fds98x1u-L3c~bpBI91IWRD80_Fy23Q) to communicate with the organizers.
- Contact Organizers: [afrisenti-semeval-organizers@googlegroups.com](mailto:afrisenti-semeval-organizers@googlegroups.com) -->


## **References**

1. George A Miller and Walter G Charles. 1991. Contex-
tual Correlates of Semantic Similarity. Language
and Cognitive Processes, 6(1):1–28

2. Abdalla, Mohamed, Krishnapriya Vishnubhotla, and Saif M. Mohammad. "What makes sentences semantically related: A textual relatedness dataset and empirical study." arXiv preprint arXiv:2110.04845 (2021).




<style>
body {
text-align: justify}
</style>
