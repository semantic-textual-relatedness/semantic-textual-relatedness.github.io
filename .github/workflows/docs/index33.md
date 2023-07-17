## AfriSenti-SemEval: Sentiment Analysis for African Languages

<p>Part of <a href="https://semeval.github.io/SemEval2023/">The 17th International Workshop on Semantic Evaluation</a><strong><br /></strong></p>
<p><strong>Contact organizers:</strong>&nbsp;<a href="mailto:afrisenti-semeval-organizers@googlegroups.com">afrisenti-semeval-organizers@googlegroups.com</a></p>
<p>To communicate with the organizers,&nbsp;<strong>join</strong> the</p>
<ul>
<li><strong>Mailing Group:</strong>&nbsp;<a href="https://groups.google.com/g/afrisenti-semeval">https://groups.google.com/g/afrisenti-semeval</a></li>
<li><strong>Slack Channel: <a href="https://join.slack.com/t/afrisenti-semeval/shared_invite/zt-1l7p31dep-ydnHOzZRGcpBb8dBOu2QAw">AfriSenti</a></strong></li>
</ul>

<p><strong style="color: blue;">Update (05 February):</strong></p>
<ul>
<li>The release of official team rankings is now: on February 7th, 2023.</li>
</ul>
<p><strong style="color: blue;">Update (17 January):</strong></p>
<ul>
<li>The official ranking for the shared task is <span class="pwa-fa">Weighted F1</span></li>
<li>Evaluation starts: January 20th, 2023</li>
<li>Release of dev set gold labels : January 20th, 2023</li>
<li>Evaluation ends: January 31st, 2023</li>
<li>Team registration form submission deadline: February 3rd, 2023 (we will share the form soon, with more details)</li>
<li>System Description Paper deadline: February 20, 2023</li>
<li>Release of official team rankings: February 5th, 2023</li>
<li>Release of test data gold labels: February 10th, 2023</li>
<li>System Description Paper deadline: February 20, 2023</li>
</ul>
<p><strong style="color: blue;">Update (31 October):</strong></p>
<ul>
<li>Xitsonga (ts) is now in Task A</li>
<li>Multilingual (Task B) dataset has been updated to include Xitsonga</li>
</ul>
<p style="color: blue;"><strong>Update (26 October):</strong></p>
<ul>
<li>We released datasets for</li>
<ul>
<li>Task A: Twi - twi</li>
<li>Task C: Xitsonga - ts</li>
</ul>
<li>We updated the final dataset for Task B - Multilingual (consisting of all released datasets for Task A)</li>
</ul>
<p style="color: blue;"><strong>Update (15 October):</strong></p>
<ul>
<li>We released datasets for</li>
<ul>
<li>Task A: Kinyarwanda - kr</li>
<li>Task C: Oromo - or</li>
<li>Task C: Tigrinya - tg</li>
</ul>
</ul>
<p style="color: blue;"><strong>Update (8 October):</strong></p>
<ul>
<li>Due to inquiries, we included a <a href="#learn_the_details-organizers">"How to Participate"</a> tab with step-by-step instructions.</li>
<li>We provide a <a href="https://github.com/afrisenti-semeval/afrisent-semeval-2023">Starter Kit</a> on our GitHub Repo.&nbsp;</li>
<li>We released <a href="https://github.com/afrisenti-semeval/afrisent-semeval-2023/tree/main/sentiment_lexicon">sentiment&nbsp;lexicons</a> for&nbsp;some languages in our GitHub repo.</li>
<li>We now have the best paper award, in addition to the best system prizes.</li>
</ul>
<p style="color: blue;"><strong>Update (4 October):</strong></p>
<ul>
<li>We released an updated dataset (Version 2.0). Disregard the previous version and download the current.</li>
<li>We added Mozambican Portuguese and will soon release other languages after the annotation</li>
</ul>
<hr />
<p style="text-align: justify;" dir="ltr"><strong style="font-size: 1.5em;">Motivation</strong></p>
<p>Due to the widespread use of the Internet and social media platforms, most languages are becoming digitally available. This allows for various artificial intelligence (AI) applications that enable tasks such as sentiment analysis, machine translation and hateful content detection. According to UNESCO (2003), 30% of all living languages, around 2,058, are African languages. However, most of these languages do not have curated datasets for developing such AI applications. Recently, various individual and funded initiatives, such as the Lacuna Fund, have set out to reverse this trend and create such datasets for African languages. However, research is required to determine both the suitability of current natural language processing (NLP) techniques and the development of novel techniques to maximize the applications of such datasets.</p>
<p>There has been a growing interest in sentiment analysis which applies to many domains, including public health, commerce/business, art and literature, social sciences, neuroscience, and psychology (<cite>Mohammad, Saif M, 2022</cite>). Previous shared tasks on sentiment analysis include <cite>Mohammad, Saif M et al., (2018), Nakov et al., (2016), Pontiki et al., Ghosh et al., (2015), (2014), and so on</cite>. However, none of these tasks included African languages. Though <cite> Mohammad, Saif, et al. (2018)</cite> included standard Arabic, we focus on Arabic dialects from African countries: <cite>Algerian Arabic</cite> and <cite>Tunisian Arabizi</cite>. We believe SemEval is the right venue, due to its popularity and widespread acceptance, to carry out shared tasks for African languages to strengthen their further development.</p>
<p>In this shared task, we have covered 17 African languages, <a href="https://en.wikipedia.org/wiki/Hausa_language">Hausa</a>, <a href="https://en.wikipedia.org/wiki/Yoruba_language">Yoruba</a>, <a href="https://en.wikipedia.org/wiki/Igbo_language">Igbo</a>, <a href="https://en.wikipedia.org/wiki/Nigerian_Pidgin">Nigerian </a>Pidgin from Nigeria, <a href="https://en.wikipedia.org/wiki/Amharic, and Oromo">Amharic</a>, <a href="https://en.wikipedia.org/wiki/Tigrinya_language">Tigrinya</a>, and <a href="https://en.wikipedia.org/wiki/Oromo_language">Oromo</a> from Ethiopia, <a href="https://en.wikipedia.org/wiki/Swahili_language">Swahili</a> from Kenya and Tanzania, <a href="https://en.wikipedia.org/wiki/Algerian_Arabic">Algerian Arabic</a> dialect from Algeria, <a href="https://en.wikipedia.org/wiki/Kinyarwanda">Kinyarwanda</a> from Rwanda, <a href="https://en.wikipedia.org/wiki/Twi">Twi</a> from Ghana, <a href="https://www.google.com/search?client=safari&amp;rls=en&amp;q=Mozabique+portuguess&amp;ie=UTF-8&amp;oe=UTF-8">Mozambique Portuguese</a> from Mozambique &nbsp;and <a href="https://en.wikipedia.org/wiki/Moroccan_Arabic">Moroccan Arabic/Darija</a> from Morocco.</p>
<h2 id="task-overview"><strong>Task Overview</strong></h2>
<p>The <strong>AfriSenti-SemEval Shared Task 12</strong> is based on a collection of Twitter datasets in 14 African languages for sentiment classification. It consists of three sub-tasks. Participants can select one or more sub-tasks depending on their preference. In each sub-task also, the participant may wish to participate in any number of languages as so wished.</p>
<blockquote>
<p><strong>Task A: Monolingual Sentiment Classification</strong></p>
</blockquote>
<p>Given training data in a target language, determine the polarity of a tweet in the target language (positive, negative, or neutral). If a tweet conveys both a positive and negative sentiment, whichever is the stronger sentiment should be chosen. This sub-task has 15 tracks:</p>
<p><strong>Note: You are free to select one or more tracks in this sub-task.<br /></strong></p>
<ul>
<li>Track 1: Hausa&nbsp;</li>
<li>Track 2: Yoruba</li>
<li>Track 3: Igbo</li>
<li>Track 4: Nigerian_Pidgin</li>
<li>Track 5: Amharic</li>
<li>Track 6: Algerian Arabic</li>
<li>Track 7: Moroccan Arabic/Darija,</li>
<li>Track 8: Swahili</li>
<li>Track 9: Kinyarwanda</li>
<li>Track 10: Twi</li>
<li>Track 11: Mozambican Portuguese</li>
<li>Track 12: Xitsonga&nbsp;(<strong>Mozambique Dialect</strong>)</li>
<li><span style="text-decoration: line-through;">Track 13: Setswana (data to be released soon)</span></li>
<li><span style="text-decoration: line-through;">Track 14: isiZulu (data to be released soon)</span></li>
<li><span style="text-decoration: line-through;">Track 15: Xitsonga (South-African Dialect, to be released soon)</span></li>
</ul>
<p><strong>Note: Tweets in each language are code-mix. Read our <a href="https://arxiv.org/pdf/2201.08277.pdf">NaijaSenti</a> paper for more information.</strong></p>
<blockquote>
<p><strong>Task B: Multilingual Sentiment Classification</strong></p>
</blockquote>
<p>Given combined training data from Task-A (Track 1 to 12), determine the polarity of a tweet in the target language (positive, negative, or neutral). This sub-task has only one track with 12 languages <strong style="color: blue;">(Hausa, Yoruba, Igbo, Nigerian_Pidgin, Amharic, Algerian Arabic, Moroccan Arabic/Darija, Swahili, Kinyarwanda, Twi, Mozambican Portuguese, and Xitsonga(<strong>Mozambique Dialect</strong>)):</strong></p>
<ul>
<li>Track 16: 12 languages in Task A</li>
</ul>
<blockquote>
<p><strong>Task C: Zero-Shot Sentiment Classification</strong></p>
</blockquote>
<p>Given unlabelled tweets in two African languages (Tigrinya and Oromo), leverage any or all of the available training datasets (in Task:A ) to determine the sentiment of a tweet in the two target languages. This task has two (2) tracks.</p>
<p><strong>Note: You are free to select one or more tracks in this sub-task.</strong></p>
<ul>
<li>Track 17: Zero-Shot on Tigrinya</li>
<li>Track 18: Zero-Shot on Oromo</li>
</ul>


<h2 id="dataset-examples"><strong>Dataset Examples</strong></h2>
<p>The dataset involves tweets labelled with three sentiment classes (positive, negative, neutral) in 14 African languages. Each tweet is annotated by three annotators following the annotation guidelines in (<cite>Mohammad, Saif M, 2016</cite>). We use a form of a majority vote to determine the sentiment of the tweet. See more in our paper (<cite>Muhammad et al., 2022</cite>, <cite>Yimam et al., 2020</cite>). Below is a sample dataset for the 4 Nigerian languages (Muhammad et al., 2022):</p>
<p>&nbsp;</p>
<p><img src="https://raw.githubusercontent.com/afrisenti-semeval/afrisent-semeval-2023/main/images/languages.jpeg" alt="Dataset Example" /></p>
<p>The datasets are available on the <span style="text-decoration: underline;"><strong><em>Participate</em></strong></span> tab<a href="../7320#participate" target="_parent">.</a></p>
<p>&nbsp;</p>
<h2 id="why-participate">Starter Kit?</h2>
<p>We provide a <a href="https://github.com/afrisenti-semeval/afrisent-semeval-2023">Starter Ki</a>t on our GitHub Repo that can be used to crearte a baseline system.</p>
<h2 id="why-participate">Why Participate?</h2>
<ul>
<li>Promote NLP research involving African languages,</li>
<li>Opportunity to write a system-description paper that describes their system, resources used, results, and analysis.</li>
<li>Stand a chance to win an award.</li>
<li>Opportunity to network with renowned experts in the AI and NLP community.</li>
</ul>
<p><span style="font-size: 10px;"><strong style="font-size: 1.5em;">Resources on Paper Submission</strong></span></p>
<ul>
<li><a href="https://semeval.github.io/paper-requirements.html">Paper Submission Requirements</a></li>
<li><a href="https://semeval.github.io/system-paper-template.html">Guidelines for Writing Papers</a></li>
<li><a href="https://github.com/acl-org/acl-style-files">Paper Style Files</a></li>
<li>Paper Submission Site (TBD)</li>
</ul>
<h2 id="communication"><strong style="font-size: 1.5em;">Previous Shared Tasks</strong></h2>
<ul>
<li>Shared tasks in English:&nbsp;<a href="https://alt.qcri.org/semeval2017/task4/">SemEval-2017</a>,&nbsp;<a href="https://alt.qcri.org/semeval2016/task4/">SemEval-2016</a>,&nbsp;<a href="https://alt.qcri.org/semeval2015/task10/">SemEval-2015</a>,&nbsp;<a href="https://alt.qcri.org/semeval2014/task9/">SemEval-2014</a>,&nbsp;<a href="https://aclanthology.org/S13-2052/">SemEval-2013</a>.</li>
<li>Shared tasks in Spanish:&nbsp;<a href="http://www.sepln.org/workshops/tass/2017/">TASS-2017</a>,&nbsp;<a href="http://www.sepln.org/workshops/tass/2016/tass2016.php">TASS-2016</a>,&nbsp;<a href="http://www.sepln.org/workshops/tass/2015/tass2015.php">TASS-2015</a>,&nbsp;<a href="http://www.sepln.org/workshops/tass/2014/tass2014.php">TASS-2014</a>,&nbsp;<a href="https://competitions.codalab.org/competitions/17751#learn_the_details-overview">TASS-2013</a>,&nbsp;<a href="http://www.sepln.org/workshops/tass/2012/tasks.php">TASS-2012</a>.</li>
</ul>