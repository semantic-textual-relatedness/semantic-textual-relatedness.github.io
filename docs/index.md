
<center>

#   **SemEval-2024 Task 1: Semantic Textual Relatedness for African and Asian Languages** 
---
A shared task on automatically detecting the degree of semantic relatedness between pairs of sentences. New textual datasets will be provided for Afrikaans, Algerian Arabic, Amharic, English, Hausa, Hindi, Indonesian, Kinyarwanda, Marathi, Moroccan Arabic, Modern Standard Arabic, Punjabi, Spanish, and Telugu.

---
 Part of the [18th International Workshop on Semantic Evaluation](https://semeval.github.io/SemEval2024/tasks.html)

<!-- 
<center> -->

 Contact organisers at [semrel-semeval-organisers@googlegroups.com](mailto:semrel-semeval-organisers@googlegroups.com)

 [Development Phase Website](https://codalab.lisn.upsaclay.fr/competitions/15715)
 
 [Evaluation Phase Website](https://codalab.lisn.upsaclay.fr/competitions/16799)


<!-- 
<center> -->

 [GitHub Page](https://github.com/semantic-textual-relatedness/Semantic_Relatedness_SemEval2024)

 [Data](https://github.com/semantic-textual-relatedness/Semantic_Relatedness_SemEval2024)

 [Follow us on Twitter](https://twitter.com/SemRel2024)

 [Join Task Slack Channel](https://join.slack.com/t/semrelsemeval2024/shared_invite/zt-2446ppar5-62koodIDFC9bCRMlR0ATkA)

 [Join Google Group](https://groups.google.com/forum/#!forum/semrel-semeval-participants/join)


<!-- <center> -->


<!-- >  [Visit CodaLab competition website](https://codalab.lisn.upsaclay.fr/competitions/7320) -->

<!-- <font size=3> <span style="color: blue;"> AfriSenti dataset is available at task's:[GitHub repo](https://github.com/afrisenti-semeval/afrisent-semeval-2023) </span> </font>
 -->

</center>



## **Task Results**

The shared task has officially ended, and we have released the results. You can access the results at the following links:
    <li><a href="https://docs.google.com/spreadsheets/d/1yn-caxJTjlufmcF1uzAh3aLLQGVVGRsS5MW5ShBWVWQ/edit?usp=sharing" target="_blank">Track A Results</a></li>
        <li><a href="https://docs.google.com/spreadsheets/d/1KGN26MYVlfEOqooq-bzD6EBNnpl-YT5XrY9COKESS-g/edit?usp=sharing" target="_blank">Track B Results</a></li>
        <li><a href="https://docs.google.com/spreadsheets/d/1A4nL2-SrH-DrvGGbuKGyl42VdwFrnXiDdWd6eQJTi5s/edit?usp=sharing" target="_blank">Track C Results</a></li>


---
## **Motivation**

The semantic relatedness of two language units has long been considered fundamental to understanding meaning (<cite>Halliday and Hassan 1976, Miller and Charles 1991</cite>), and automatically determining relatedness has many applications such as evaluating sentence representation methods, question answering, and summarization (<cite>Abdalla et al. 2023</cite>).

Two sentences are considered semantically similar when they have a paraphrasal or entailment relation. On the other hand, relatedness is a much broader concept that accounts for all the commonalities between two sentences: whether they are on the same topic, express the same view, originate from the same time period, one elaborates on (or follows from) the other, etc. For instance, for the following sentence pairs:

<center>

![sentence pairs](pairs_semrel.png)

</center>

Most people will agree that the sentences in pair 1 are more related than the sentences in pair 2. 

Much of past NLP work is on semantic similarity, and largely focused on English. In this shared task, we cover the following languages: [Afrikaans](https://en.wikipedia.org/wiki/Afrikaans), [Algerian Arabic](https://en.wikipedia.org/wiki/Algerian_Arabic), [Amharic](https://en.wikipedia.org/wiki/Amharic), English, [Hausa](https://en.wikipedia.org/wiki/Hausa_language), [Hindi](https://en.wikipedia.org/wiki/Hindi), [Indonesian](https://en.wikipedia.org/wiki/Indonesian_language), [Kinyarwanda](https://en.wikipedia.org/wiki/Kinyarwanda), [Marathi](https://en.wikipedia.org/wiki/Marathi_language), [Morrocan Arabic](https://en.wikipedia.org/wiki/Moroccan_Arabic), [Modern Standard Arabic](https://en.wikipedia.org/wiki/Modern_Standard_Arabic), [Punjabi](https://en.wikipedia.org/wiki/Punjabi_language), [Spanish](https://en.wikipedia.org/wiki/Spanish_language), and [Telugu](https://en.wikipedia.org/wiki/Telugu_language).

## **Task Overview**
<p><strong>Data</strong></p>
 
<p>Each instance in the training, development, and test sets is a sentence pair. The instance is labeled with a score representing the degree of semantic textual relatedness between the two sentences. The scores can range from 0 (maximally unrelated) to 1 (maximally related). These gold label scores have been determined through manual annotation. Specifically, a comparative annotation approach was used to avoid known limitations of traditional rating scale annotation methods. This comparative annotation process (which avoids several biases of traditional rating scales) led to a high reliability of the final relatedness rankings.
Further details about the task, the method of data annotation, how STR is different from semantic textual similarity, applications of semantic textual relatedness, etc. can be found in <a href="https://aclanthology.org/2023.eacl-main.55.pdf">this paper</a>.
</p>

<p><strong> The Semantic Textual Relatedness Shared Task 1</strong></p>
<p>The task consists of predicting semantic textual relatedness (STR) of sentence pairs. Participants will rank sentence pairs by their closeness in meaning (i.e., their degree of semantic relatedness) in the 14 different languages. All sentence pairs will have manually determined relatedness scores between 0 (completely unrelated) and 1 (maximally related). Each team can provide submissions for one, two or all of the tracks shown below:

</p>

<p><strong>Track A: Supervised</strong></p>
<p>Participants are to submit systems that have been trained using the labeled training datasets provided. Participating teams are allowed to use any publicly available datasets (e.g., other relatedness and similarity datasets or datasets in any other languages). However, they must report additional data they used, and ideally report how impactful each resource was on the final results.
</p>


<p><strong>Track B: Unsupervised</strong></p>
<p>Participants are to submit systems that have been developed without the use of any labeled datasets pertaining to semantic relatedness or semantic similarity between units of text more than two words long in any language. The use of unigram or bigram relatedness datasets (from any language) is permitted. 
</p>

<p><strong>Track C: Cross-lingual</strong></p>
<p>Participants are to submit systems that have been developed without the use of any labeled semantic similarity or semantic relatedness datasets in the target language and with the use of labeled dataset(s) from at least one other language.  Note: Using labeled data from another track is mandatory for a submission to this track.
</p>

<p><strong>Deciding which track a submission should go to</strong></p>
 <ul>
	<LI> If a submission uses labeled data in the target language: submit to Track A.</LI>
 <LI> If a submission does not use labeled data in the target language but uses labeled data from another language: submit to Track C. </LI>
 <LI> If a submission does not use labeled data in any language: submit to Track B.</LI>
 </ul>

<p><strong>Note</strong></p>

<p>** Here ‘labeled data’ refers to labeled datasets pertaining to semantic relatedness or semantic similarity between units of text more than two words long. </p>

## **Evaluation**

The official evaluation metric for this task is the Spearman rank correlation coefficient, which captures how well the system-predicted rankings of test instances align with human judgments. You can find the evaluation script for this shared task on our [Github page](https://github.com/semantic-textual-relatedness/Semantic_Relatedness_SemEval2024/blob/main/evaluation_script/evaluation.py).

## **Important Dates**

| Description                  | Deadline                                     |
| ---------------------------- | ---------------------------------------------|
| Training Data Ready          | <s>18 September 2023</s>                     |
| Evaluation Start             | 20 January 2024                              |
| Evaluation End               | 31 January 2024                              |
| System Description Paper Due | 19 February 2024                             |
| Notification to authors      | 1 April 2024                                 |
| Camera ready due             | 22 April 2024                                |
| SemEval workshop 2024        | June 16–21, 2024 (co-located with NAACL2024) |


All deadlines are 23:59 UTC-12 ("anywhere on Earth").

## **Dataset**
The data for this shared task is now available [here](https://github.com/semantic-textual-relatedness/Semantic_Relatedness_SemEval2024#citing-this-work).


## **FAQs**

#### Can I use LLMs for Tracks B and C?

<p>For tasks B and C, the use of pre-trained language models (PLMs) is permitted, as long as they have not been explicitly trained on any form of text similarity data or objective. </p>

<p>Therefore, it is acceptable to use PLMs trained on unlabeled text, whether under a masked objective (such as BERT) or a causal objective (e.g., GPT-2). If the PLM is then further fine-tuned with text similarity data, whether through instruct-tuning (e.g., BLOOMZ), classification, or a similarity objective (like SBERT), then it is not allowed anymore.</p> 

<p>To ensure fairness, the use of an opaque model, where the training data origins are unclear, such as using the ChatGPT, is also prohibited for tasks B and C.</p>

<p>For Track C (cross-lingual), one can use some amount of labeled data from a language other than the target language. I.e., using opaque English models on non-English languages in Track C is fine. </p>

#### Do I have to participate in all languages for a given track?
<p>No you can participate in one or more languages.</p>


#### How will you verify my submitted model?


<p>To be included in the final team rankings of our shared task, it is mandatory for participants to submit a system description paper describing their approaches and methodologies in detail therefore ensuring scientific integrity.</p>



<!-- ## **Communication**

- Join [Task Mailing List](https://groups.google.com/g/afrisenti-semeval)
- Join [Task Slack Channel](https://join.slack.com/t/afrisenti-semeval/shared_invite/zt-1fds98x1u-L3c~bpBI91IWRD80_Fy23Q) to communicate with the organizers.
- Contact Organizers: [afrisenti-semeval-organizers@googlegroups.com](mailto:afrisenti-semeval-organizers@googlegroups.com) -->


## **References**
Shima Asaadi, Saif Mohammad, Svetlana Kiritchenko. 2019. Big BiRD: A Large, Fine-Grained, Bigram Relatedness Dataset for Examining Semantic Composition. Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies.

M. A. K. Halliday and R. Hasan. 1976. Cohesion in English. London: Longman.

George A Miller and Walter G Charles. 1991. Contextual Correlates of Semantic Similarity. Language and Cognitive Processes, 6(1):1–28

Mohamed Abdalla, Krishnapriya Vishnubhotla, and Saif Mohammad. 2023. What Makes Sentences Semantically Related? A Textual Relatedness Dataset and Empirical Study. In Proceedings of the 17th Conference of the European Chapter of the Association for Computational Linguistics, pages 782–796, Dubrovnik, Croatia. Association for Computational Linguistics.

<style>
body {
text-align: justify}
</style>
