
<p style="text-align: justify;" dir="ltr"><strong style="font-size: 1.5em;">Motivation</strong></p>
<p>Due to the widespread use of the Internet and social media platforms, most languages are becoming digitally available. This allows for various artificial intelligence (AI) applications that enable tasks such as sentiment analysis, machine translation and hateful content detection. According to UNESCO (2003), 30% of all living languages, around 2,058, are African languages. However, most of these languages do not have curated datasets for developing such AI applications. Recently, various individual and funded initiatives, such as the Lacuna Fund, have set out to reverse
    this trend and create such datasets for African languages. However, research is required to determine both the suitability of current natural language processing (NLP) techniques and the development of novel techniques to maximize the applications of such datasets.</p>
    <p>There has been a growing interest in sentiment analysis which applies to many domains, including public health, commerce/business, art and literature, social sciences, neuroscience,
    and psychology (<cite>Mohammad, Saif M, 2022</cite>). Previous shared tasks on sentiment analysis include <cite>Mohammad, Saif M et al., (2018), Nakov et al., (2016), Pontiki et al., Ghosh et al., (2015), (2014), and so on </cite> . However, none of these tasks included African languages. Though <cite> Mohammad, Saif, et al. (2018)</cite> included standard Arabic, we focus on Arabic dialects from African countries: <cite>Algerian Arabic</cite> and <cite>Tunisian Arabizi</cite>. We believe SemEval is the right venue, due to its popularity and widespread acceptance, to carry out shared tasks for African languages to strengthen their further development. </p>
    <p>In this shared task, we have covered 16 African languages, <a href="https://en.wikipedia.org/wiki/Hausa_language">Hausa</a>, <a href="https://en.wikipedia.org/wiki/Yoruba_language">Yoruba</a>, <a href="https://en.wikipedia.org/wiki/Igbo_language">Igbo</a>, <a href="https://en.wikipedia.org/wiki/Nigerian_Pidgin">Nigerian Pigdin</a> from Nigeria, <a href="https://en.wikipedia.org/wiki/Amharic, and Oromo">Amharic</a>, <a href="https://en.wikipedia.org/wiki/Tigrinya_language">Tigrinya</a> and <a href="https://en.wikipedia.org/wiki/Oromo_language">Oromo</a> from Ethiopia, <a href="https://en.wikipedia.org/wiki/Swahili_language">Swahili</a> from Kenya and Tanzania,  <a href="https://en.wikipedia.org/wiki/Algerian_Arabic">Algerian Arabic</a> dialect from Algeria, <a href="https://en.wikipedia.org/wiki/Kinyarwanda">Kinyarwanda</a> from Rwanda, <a href="https://en.wikipedia.org/wiki/Twi">Twi</a> from Ghana, <a href="https://www.google.com/search?client=safari&amp;rls=en&amp;q=Mozabique+portuguess&amp;ie=UTF-8&amp;oe=UTF-8">Mozambique Portuguese</a> from Mozambique and <a href="https://en.wikipedia.org/wiki/Zulu_language">isiZulu</a>, <a href="https://en.wikipedia.org/wiki/Tswana_language">Setswana</a>, <a href="https://en.wikipedia.org/wiki/Tsonga_language">Xitsonga</a> from South Africa and <a href="https://en.wikipedia.org/wiki/Moroccan_Arabic">Moroccan Arabic/Darija</a> from Morocco.</p>
<h2 id="task-overview"><strong>Task Overview</strong></h2>
<p>The <strong>AfriSenti-SemEval Shared Task 12</strong> is based on a collection of Twitter datasets in 16 African languages for sentiment classification. It consists of three sub-tasks. Participants can select one or more tasks depending on their preference.</p>
<blockquote>
<p><strong>Task A: Monolingual Sentiment Classification</strong></p>
<p>Given training data in a target language, determine the polarity of a tweet in the target language (positive, negative, or neutral). If a tweet 
For messages conveying both a positive and negative sentiment, whichever is the stronger sentiment should be chosen. This sub-task has 13 tracks:</p>
</blockquote>
<ul>
<li>Track 1: Hausa</li>
<li>Track 2: Yoruba</li>
<li>Track 3: Igbo</li>
<li>Track 4: Nigerian_Pidgin</li>
<li>Track 5: Amharic</li>
<li>Track 6: Algerian Arabic</li>
<li>Track 7: Moroccan Arabic/Darija,</li>
<li>Track 8: Swahili </li>
<li>Track 9: Kinyarwanda <strong>(<em>data to be released soon</em>)</strong></li>
<li>Track 10: Twi <strong>(<em>data to be released soon</em>)</strong></li>
<li>Track 11: Mozambican Portuguese <strong>(<em>data to be released soon</em>)</strong></li>
<li>Track 12: Setswana <strong>(<em>data to be released soon</em>)</strong></li>
<li>Track 13: isiZulu <strong>(<em>data to be released soon</em>)</strong></li>
</ul>
<blockquote>
<p><strong>Task B: Multilingual Sentiment Classification</strong></p>
</blockquote>
<p>Given a combined training data from 10 African languages, determine the polarity of a tweet in the target language (positive, negative, or neutral). This sub-task has only one track (13 languages):</p>
<ul>
<li>Track 14: All languages in Task A</li>
</ul>
<blockquote>
<p><strong>Task C: Zero-Shot Sentiment Classification</strong></p>
</blockquote>
<p>Given unlabeled tweets in three African languages (Tigrinya, Xitsonga and Oromo), leverage any or all of the available training datasets in Subtasks 1 and 2 to determine the sentiment of a tweet in the three target languages is positive, negative, or neutral. This task has three (3) tracks. This task starts on the 1st of October, 2022.</p>
<ul>
<li>Track 15: Zero-Shot on Tigrinya <strong>(<em>dev and test sets to be released</em>)</strong></li>
<li>Track 16: Zero-Shot on Xitsonga <strong>(<em>dev and test sets to be released</em>)</strong></li>
<li>Track 17: Zero-Shot on Oromo <strong>(<em>dev and test sets to be released</em>)</strong></li>
</ul>
<h2 id="dataset-examples"><strong>Dataset Examples</strong></h2>
<p>The dataset involves tweets labeled with three sentiment classes (positive, negative, neutral) in 14 African languages. Each tweet is annotated by three annotators following the annotation guidelines in (<cite>Mohammad, Saif M, 2016</cite>). We use a form of majority vote to determine the sentiment of the tweet. See more in our paper (<cite>Muhammad et al., 2022</cite>, <cite>Yimam et al., 2020</cite>). Below is a sample dataset for the 4 Nigerian languges (Muhammad et al., 2022):</p>
<p><img alt="Dataset Example" src="https://raw.githubusercontent.com/afrisenti-semeval/afrisent-semeval-2023/main/dataset.png" /></p>
<p>The datasets are available <a href="https://codalab.lisn.upsaclay.fr/competitions/7304#participate">on the competition website.</a></p>
<h2 id="why-participate">Why Participate ?</h2>
<ul>
<li>Promote NLP research involving African languages,</li>
<li>Opportunity to write a system-description paper that describes their system, resources used, results, and analysis.</li>
<li>Stand a chance to win award.</li>
<li>Opportunity to network with renowned experts in the AI and NLP community.</li>
</ul>
<h2><strong>Resources on Paper Submission</strong></h2>
<ul>
    <li><a href="https://semeval.github.io/paper-requirements.html">Paper Submission Requirements</a></li>
    <li><a href="https://semeval.github.io/system-paper-template.html">Guidelines for Writing Papers</a></li>
    <li><a href="https://github.com/acl-org/acl-style-files">Paper Style Files</a></li>
    <li>Paper Submission Site (TBD)</li>
</ul>
<h2 id="communication"><strong style="font-size: 1.5em;">Previous Shared Tasks</strong></h2>
<ol>
<li>Shared tasks in English:<a href="https://alt.qcri.org/semeval2017/task4/">SemEval-2017</a>,<a href="https://alt.qcri.org/semeval2016/task4/">SemEval-2016</a>,<a href="https://alt.qcri.org/semeval2015/task10/">SemEval-2015</a>,<a href="https://alt.qcri.org/semeval2014/task9/">SemEval-2014</a>,<a href="https://aclanthology.org/S13-2052/">SemEval-2013</a></li>
<li>Shared tasks in Spanish <a href="http://www.sepln.org/workshops/tass/2017/">TASS-2017</a>,<a href="http://www.sepln.org/workshops/tass/2016/tass2016.php">TASS-2016</a>,<a href="http://www.sepln.org/workshops/tass/2015/tass2015.php">TASS-2015</a>,<a href="http://www.sepln.org/workshops/tass/2014/tass2014.php">TASS-2014</a>,<a href="https://competitions.codalab.org/competitions/17751#learn_the_details-overview">TASS-2013</a>,<a href="http://www.sepln.org/workshops/tass/2012/tasks.php">TASS-2012</a>.</li>
</ol>