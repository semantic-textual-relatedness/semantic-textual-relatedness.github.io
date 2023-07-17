<style>
body {
text-align: justify}
</style>


<h2>How To Participate</h2>
<!-- <ol>
<li dir="ltr">
<p>Create an account on Codalab and register for the shared task in the &ldquo;participate&rdquo; tab.</p>
</li>
<li dir="ltr">
<p>Join the task Google group or Slack group. If you have questions, reach out to the task organizers. The organizers will respond as quickly as possible. Also, follow us on Twitter for the latest updates @AfriSenti2023.</p>
</li>
<li dir="ltr">
<p>Participants can form a team (and name the team) with multiple people or a single-person team. If you are a team, you can only make submissions from the team codalab account (so, each team must use one CodaLab account).</p>
</li>
<li dir="ltr">
<p>A participant can be involved in exactly one team (no more). If there are reasons why it makes sense for you to be on more than one team, then email us before the evaluation period begins. In special circumstances, this may be allowed.</p>
</li>
<li dir="ltr">
<p>Update your profile, add a team name (e.g., Lion) and enter the names of team members. To do so, go to "Competition Settings" under Settings. For example, the user "shmuhammad". <img style="vertical-align: middle;" src="https://raw.githubusercontent.com/afrisenti-semeval/afrisent-semeval-2023/main/images/team_name.png" alt="" width="1047" height="566" /></p>
</li>
<li dir="ltr">
<p>Read information about the task on all the competition pages (Evaluation, terms and conditions, submission format, schedule, and Prizes).</p>
</li>
<li dir="ltr">
<p>Competition Phases: The competition has two phases. Development phase (Phase 1) and Test phase (Phase 2).</p>
</li>
<li dir="ltr">
<p>The development phase (Phase 1): At this phase, training data (with gold label) and development data (without gold label) is released. Participants can train and evaluate their model on the train set and dev set (the dataset for this phase is released). Using any additional external data to train a model is allowed (unconstrained). However, If you are using any external data, make sure it is public data or release it immediately after the submission of your system description paper.</p>
</li>
<li dir="ltr">
<p>The test phase (Phase 2): At this phase, test data (without a gold label) will be released. Participants will finally evaluate their developed model on the test data. The test data will be released on January 20 January 2023 and the evaluation ends on January 31 2023.</p>
</li>
<li dir="ltr">
<p>Decide which Sub-task you want to participate in. You may choose one or all (i.e., sub-task A, sub-task B, and sub-task C). In each sub-task also, participants may wish to participate in one or more tracks. Note: To win a competition, you must participate in all tracks in a particular sub-task.</p>
</li>
<li dir="ltr">
<p>Download competition data: The competition dataset contains all the data for the competition. Training, development and test (when released). To download the dataset, go to &ldquo;Participate&rdquo; tab and click &ldquo;Download Datasets&rdquo; as shown below. The data is also available at the competition <a href="https://github.com/afrisenti-semeval/afrisent-semeval-2023">GitHub page</a> <img style="vertical-align: middle;" src="https://raw.githubusercontent.com/afrisenti-semeval/afrisent-semeval-2023/main/images/downloaddata.png" alt="" width="1740" height="408" /></p>
</li>
<li dir="ltr">
<p>Before running your experiments, walk through the Google Colab Notebook to create a baseline experiment and generate the submission file (next step explain how to make a submission). Find more about the Colab Notebook via our <a href="https://github.com/afrisenti-semeval/afrisent-semeval-2023">GitHub page</a>.</p>
</li>
<li dir="ltr">
<p>Make submission of baseline experiments results (optional)</p>
<ul>
<li>Read the "Submission format" tab to see the submission file format.</li>
<li>For example, to submit for Hausa language (ha), your submission file should be (pred_ha.tsv) and zipped (the name of the zipped file can be anything).</li>
<li>Go to the "Participate tab", click "Submit/View Result" and select "Development Task A: Hausa". Click "Submit button", select the zipped file and wait a few moments for the submission to execute. Click the refresh button to check the status</li>
<li>If the submission is successful, you will see "Finished". If unsuccessful, check the error log, fix the format issue (if any) and resubmit the updated zip file</li>
<li>Click "View detailed results" to see your system score (Precision, Recall and Macro-F1).</li>
<li>If you still have issues, then contact the task organizers.</li>
<li><img style="vertical-align: middle;" src="https://raw.githubusercontent.com/afrisenti-semeval/afrisent-semeval-2023/main/images/submission_1.png" alt="" width="1526" height="570" /></li>
</ul>
</li>
<li dir="ltr">
<p>Make a submission on the dev set (Phase 1 or Develpement Phase</p>
<ul>
<li>This phase has already started.</li>
<li>The procedure is similar to the previous step (submission of baseline prediction).&nbsp;</li>
<li>You can make multiple submissions in this phase (as many as 999 submissions).</li>
</ul>
</li>
<li dir="ltr">
<p>Make a submission on the test set (Phase 2 or Evaluation phase)</p>
<ul>
<li>This phase (evaluation period) starts on 10th January, 2023.</li>
<li>Test set without a gold label will be released.</li>
<li>The procedure is similar to that on the dev set. These differences below apply.</li>
<li>The leaderboard will be disabled &nbsp;and you&nbsp;will not be able to see results of your submission on the test seuntil the end of the evaluation period.</li>
<li>You can still see if your submission was successful or resulted in some error.</li>
<li>In case of error, you can view the error log.</li>
<li>The number of submissions allowed per team is restricted to 3. However, only your final valid submission will be your official submission to the competition.</li>
</ul>
</li>
<li>Once the competition is over, we will release the gold labels and you will be able to determine results on various system variants you may have developed. We encourage you to report results on all of your systems (or system variants) in the system-description paper. However, we will ask you to clearly indicate the result of your official submission.</li>
<li>We will make the final submissions of the teams public at some point after the evaluation period.</li>
<li>After the evaluation phase, the best teams in each sub-task will win a prize. Winners are expected to share their approach in the competition to be eligible for the prize. Check "AfriSenti Prize" for more information.</li>
<li>All teams that participated and submitted a result on test data are encouraged to submit a system description paper that describes their submission system. We will provide a mentorship session by<a href="https://ruder.io"> Sebastian Ruder </a>and <a href="https://nedjmaou.github.io">Nedjma Djouhra</a>&nbsp;on how to write a system description paper (we will announce the date).</li>
<li>Task participants will be assigned another team&rsquo;s system description papers for review, using the Open Review. The papers will thus be peer-reviewed.</li>
<li>Attend the SemEval2023 workshop (the location will be announced). If you are a student and submitted a system description paper, you can apply for the <a href="https://buildyourfuture.withgoogle.com/scholarships/google-conference-scholarships">Google Conference Travel Award</a> which provides a maximum of $3,000 in travel support. We will guide you to apply and get the grant.</li>
</ol>
<h2>Walkthrough on How To Participate</h2>
<p dir="ltr"><span> We prepare and record walkthrough videos explaining the competition, how to run the Colab baseline experiments and submission to Codalab. </span></p>
<ul>
<li>How to participate in the shared task.</li>
<li>How to run baseline experiment using Colab we provided.</li>
<li>How to make a submission using the result from the Colab baseline experiment.</li>
</ul>
<h2>Some resources for beginners in sentiment analysis</h2>
<ol>
<li dir="ltr"><a href="https://curiousily.com/posts/sentiment-analysis-with-bert-and-hugging-face-using-pytorch-and-python/">Sentiment Analysis with BERT and Transformers by HugginFace using Pytorch and Python</a> (include Youtube videos)</li>
<li dir="ltr"><a href="https://github.com/bentrevett/pytorch-sentiment-analysis">Tutorials on getting started with Pytorch and Torch text for sentiment analysis</a></li>
<li dir="ltr"><a href="https://github.com/abdulfatir/twitter-sentiment-analysis">Sentiment Analysis on Tweets</a></li>
<li dir="ltr"><a href="https://github.com/laugustyniak/awesome-sentiment-analysis">Awesome sentiment analysis</a></li>
<li dir="ltr"><a href="https://github.com/declare-lab/awesome-sentiment-analysis">Reading list for sentiment awesome sentiment analysis papers</a></li>
<li dir="ltr"><a href="https://paperswithcode.com/task/sentiment-analysis">Progress in sentiment analysis</a> (papers with code)</li>
<li dir="ltr"><a href="%20http:/nlpprogress.com/english/sentiment_analysis.html">SOTA in sentiment analysis(nlp-progress)</a></li>
</ol> -->