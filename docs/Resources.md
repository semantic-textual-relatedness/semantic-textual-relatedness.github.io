## Resources and FAQs
### Resources

We provide some useful information about SemEval shared task. 

1. [SemEval 2024 Shared Tasks](https://semeval.github.io/SemEval2024/tasks)
   
2. [Frequently Asked Questions about SemEval](https://semeval.github.io/faq.html)

3. [Paper Submission Requirements](https://semeval.github.io/paper-requirements.html)

4. [Guidelines for Writing Papers](https://semeval.github.io/system-paper-template.html)

5. [Paper style files](https://github.com/acl-org/acl-style-files)

6. Paper submission site (TBD)


### FAQs
#### Can I use LLMs for Tracks B and C?

<p>For tasks B and C, the use of pre-trained language models (PLMs) is permitted, as long as they have not been explicitly trained on any form of text similarity data or objective. </p>

<p>Therefore, it is acceptable to use PLMs trained on unlabeled text, whether under a masked objective (such as BERT) or a causal objective (e.g., GPT-2). If the PLM is then further fine-tuned with text similarity data, whether through instruct-tuning (e.g., BLOOMZ), classification, or a similarity objective (like SBERT), then it is not allowed anymore.</p> 

<p>To ensure fairness, the use of an opaque model, where the training data origins are unclear, such as using the ChatGPT, is also prohibited for tasks B and C.</p>

<p>For Track C (cross-lingual), one can use some amount of labeled data from a language other than the target language. I.e., using opaque English models on non-English languages in Track C is fine. </p>

#### Do I have to participate in all languages for a given track?
<p>No you can participate in one or more languages.</p>


#### How will you verify my submitted model?


<p>To be included in the final team rankings of our shared task, it is mandatory for participants to submit a system description paper describing their approaches and methodologies in detail therefore ensuring scientific integrity.</p>

