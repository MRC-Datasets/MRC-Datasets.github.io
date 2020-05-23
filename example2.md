---
layout: page
title: Metrics
permalink: /Metrics/
---

<style>
	
    .table2 table {
        width:100%;
        margin:15px 0;
        border:0;
    }
    .table2 th {
        background-color:#00A5FF;
        color:#FFFFFF
    }
    .table2,.table2 th,.table2 td {
        font-size:0.95em;
        text-align:center;
        padding:4px;
        border-collapse:collapse;
    }
    .table2 th,.table2 td {
        border: 1px solid #2087fe;
        border-width:1px 0 1px 0;
        border:2px inset #ffffff;
    }
    .table2 tr {
        border: 1px solid #ffffff;
    }
    .table2 tr:nth-child(odd){
        background-color:#aae1fe;
    }
    .table2 tr:nth-child(even){
        background-color:#ffffff;
    }
</style>

<h1 class="color1">{{ "Metrics, Leaderboards and Baseline" | escape }}</h1>
<table class=table2>
    <tr>
        <th>Year</th>
        <th>Datasets</th>
        <th>Metric 1</th>
        <th>Metric 2</th>
        <th>Metric 3</th>
        <th>Metric 4</th>
        <th>Leaderboard</th>
        <th>Baseline</th>
    </tr>
    <tr>
        <td>2013</td>
        <td>MCTest  mc500</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://mattr1.github.io/mctest/results.html');">Leaderboard</button></td>
        <td><button onclick="window.open('https://mattr1.github.io/mctest/results.html');">Baseline</button></td>
    </tr>
    <tr>
        <td>2013</td>
        <td>MCTest  mc160</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://mattr1.github.io/mctest/results.html');">Leaderboard</button></td>
        <td><button onclick="window.open('https://mattr1.github.io/mctest/results.html');">Baseline</button></td>
    </tr>
    <tr>
        <td>2015</td>
        <td>Daily Mail</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://github.com/danqi/rc-cnn-dailymail');">Baseline</button></td>
    </tr>
    <tr>
        <td>2015</td>
        <td>CNN</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://github.com/danqi/rc-cnn-dailymail');">Baseline</button></td>
    </tr>
    <tr>
        <td>2015</td>
        <td>CuratedTREC</td>
        <td>Exact Match</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://trec.nist.gov/results.html');">Leaderboard</button></td>
        <td><button onclick="window.open('https://github.com/facebookresearch/DrQA');">Baseline</button></td>
    </tr>
    <tr>
        <td>2015</td>
        <td>WikiQA</td>
        <td>Precision</td>
        <td>Recall</td>
        <td>F1</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2016</td>
        <td>WikiMovies</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://github.com/facebook/bAbI-tasks');">Baseline</button></td>
    </tr>
    <tr>
        <td>2016</td>
        <td>SQuAD1.1</td>
        <td>F1</td>
        <td>Exact Match</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://rajpurkar.github.io/SQuAD-explorer/');">Leaderboard</button></td>
        <td><button onclick="window.open('https://rajpurkar.github.io/SQuAD-explorer/');">Baseline</button></td>
    </tr>
    <tr>
        <td>2016</td>
        <td>Who-did-What</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://tticnlp.github.io/who_did_what/leaderBoard.html');">Leaderboard</button></td>
        <td><button onclick="window.open('https://tticnlp.github.io/who_did_what/leaderBoard.html');">Baseline</button></td>
    </tr>
    <tr>
        <td>2016</td>
        <td>MS MARCO</td>
        <td>Rouge-L</td>
        <td>BLEU-1</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('http://www.msmarco.org/leaders.aspx');">Leaderboard</button></td>
        <td><button onclick="window.open('https://github.com/microsoft/MSMARCO-Question-Answering');">Baseline</button></td>
    </tr>
    <tr>
        <td>2016</td>
        <td>NewsQA</td>
        <td>Exact Match</td>
        <td>F1</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2016</td>
        <td>LAMBADA</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://github.com/brain-research/wip-lambada-lm');">Baseline</button></td>
    </tr>
    <tr>
        <td>2016</td>
        <td>WikiReading</td>
        <td>Mean F1</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://github.com/google-research-datasets/wiki-reading');">Baseline</button></td>
    </tr>
    <tr>
        <td>2016</td>
        <td>Facebook CBT</td>
        <td>Accuracy on Named Entities</td>
        <td>Accuracy on Common Nouns</td> 
        <td>Accuracy on Verbs</td>
        <td>Accuracy on Prepositions</td> 
        <td>N/A</td>
        <td><button onclick="window.open('https://github.com/facebook/bAbI-tasks');">Baseline</button></td>
    </tr>
    <tr>
        <td>2016</td>
        <td>BookTest</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2016</td>
        <td>Google MC-AFP</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2016</td>
        <td>MovieQA</td>
        <td>Accuracy of Video Clips</td>
        <td>Accuracy of Plots and Subtitles</td>
        <td></td>
        <td>N/A</td>
        <td><button onclick="window.open('http://movieqa.cs.toronto.edu/leaderboard/');">Leaderboard</button></td>
        <td><button onclick="window.open('https://github.com/makarandtapaswi/MovieQA_CVPR2016/');">Baseline</button></td>
    </tr>
    <tr>
        <td>2017</td>
        <td>TriviaQA(Web)</td>
        <td>Exact Match</td>
        <td>F1</td>
        <td>Verified-EM</td>
        <td>Verified-F1</td>
        <td><button onclick="window.open('https://competitions.codalab.org/competitions/17208');">Leaderboard</button></td>
        <td><button onclick="window.open('https://github.com/mandarjoshi90/triviaqa');">Baseline</button></td>
    </tr>
    <tr>
        <td>2017</td>
        <td>TriviaQA (Wiki)</td>
        <td>Exact Match</td>
        <td>F1</td>
        <td>Verified-EM</td>
        <td>Verified-F1</td>
        <td><button onclick="window.open('https://competitions.codalab.org/competitions/17208');">Leaderboard</button></td>
        <td><button onclick="window.open('https://github.com/mandarjoshi90/triviaqa');">Baseline</button></td>
    </tr>
    <tr>
        <td>2017</td>
        <td>RACE</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('http://www.qizhexie.com/data/RACE_leaderboard');">Leaderboard</button></td>
        <td><button onclick="window.open('https://github.com/qizhex/RACE_AR_baselines');">Baseline</button></td>
    </tr>
    <tr>
        <td>2017</td>
        <td>Quasar-S</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://github.com/bdhingra/ga-reader');">Baseline</button></td>
    </tr>
    <tr>
        <td>2017</td>
        <td>Quasar-T</td>
        <td>Exact Match</td>
        <td>F1</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://github.com/bdhingra/ga-reader');">Baseline</button></td>
    </tr>
    <tr>
        <td>2017</td>
        <td>SearchQA</td>
        <td>F1 score (for n-gram)(Single word or Multi-word)</td>
        <td>Unigram(Single word) Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2017</td>
        <td>NarrativeQA</td>
        <td>ROUGE-L</td>
        <td>BLEU-1</td>
        <td>BLEU-4</td>
        <td>Meteor</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://github.com/deepmind/narrativeqa');">Baseline</button></td>
    </tr>
    <tr>
        <td>2017</td>
        <td>SciQ</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2017</td>
        <td>Qangaroo(MedHop)</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('http://qangaroo.cs.ucl.ac.uk/leaderboard.html');">Leaderboard</button></td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2017</td>
        <td>Qangaroo(WikiHop)</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('http://qangaroo.cs.ucl.ac.uk/leaderboard.html');">Leaderboard</button></td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2017</td>
        <td>TQA</td>
        <td>Accuracy of All</td>
        <td>Accuracy of Diagram</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('http://vuchallenge.org/tqa.html');">Leaderboard</button></td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2017</td>
        <td>COMICS</td>
        <td>Accuracy of Text Cloze</td>
        <td>Accuracy of Visual Cloze</td>
        <td>Accuracy of Coherence</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://github.com/miyyer/comics');">Baseline</button></td>
    </tr>			
   <tr>
        <td>2018</td>
        <td>QuAC</td>
        <td>F1</td>
        <td>HEQ-Q</td>
        <td>HEQ-D</td>
        <td>N/A</td>
        <td><button onclick="window.open('http://quac.ai/');">Leaderboard</button></td>
        <td><button onclick="window.open('https://github.com/allenai/allennlp');">Baseline</button></td>
    </tr>
    <tr>
        <td>2018</td>
        <td>CoQA</td>
        <td>F1 overall</td>
        <td>F1 out-of-domain overall</td>
        <td>F1 in-domain overall</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://stanfordnlp.github.io/coqa/');">Leaderboard</button></td>
        <td><button onclick="window.open('https://github.com/stanfordnlp/coqa-baselines');">Baseline</button></td>
    </tr>
    <tr>
        <td>2018</td>
        <td>SQuAD2.0</td>
        <td>F1</td>
        <td>EM</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://rajpurkar.github.io/SQuAD-explorer/');">Leaderboard</button></td>
        <td><button onclick="window.open('https://rajpurkar.github.io/SQuAD-explorer/');">Baseline</button></td>
    </tr>
    <tr>
        <td>2018</td>
        <td>HotpotQA(Distractor Setting)</td>
        <td>EM of Answer</td>
        <td>F1 of Answer</td>
        <td>EM of  Supportings</td>
        <td>F1 of  Supportings</td>
        <td><button onclick="window.open('https://hotpotqa.github.io/');">Leaderboard</button></td>
        <td><button onclick="window.open('https://github.com/hotpotqa/hotpot');">Baseline</button></td>
    </tr>
    <tr>
        <td>2018</td>
        <td>HotpotQA(Fullwiki Setting)</td>
        <td>EM of Answer</td>
        <td>F1 of Answer</td>
        <td>EM of  Supportings</td>
        <td>F1 of  Supportings</td>
        <td><button onclick="window.open('https://hotpotqa.github.io/');">Leaderboard</button></td>
        <td><button onclick="window.open('https://github.com/hotpotqa/hotpot');">Baseline</button></td>
    </tr>
    <tr>
        <td>2018</td>
        <td>DuoRC-Self</td>
        <td>Accuracy</td>
        <td>F1</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://duorc.github.io');">Leaderboard</button></td>
        <td><button onclick="window.open('https://duorc.github.io');">Baseline</button></td>
    </tr>
    <tr>
        <td>2018</td>
        <td>DuoRC-Paraphrase</td>
        <td>Accuracy</td>
        <td>F1</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://duorc.github.io');">Leaderboard</button></td>
        <td><button onclick="window.open('https://duorc.github.io');">Baseline</button></td>
    </tr>
    <tr>
        <td>2018</td>
        <td>CLOTH</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('http://www.qizhexie.com/data/CLOTH_leaderboard');">Leaderboard</button></td>
        <td><button onclick="window.open('https://github.com/qizhex/Large-scale-Cloze-Test-Dataset-Created-by-Teachers');">Baseline</button></td>
    </tr>
    <tr>
        <td>2018</td>
        <td>ReCoRD</td>
        <td>Exact Match</td>
        <td>F1</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://sheng-z.github.io/ReCoRD-explorer/');">Leaderboard</button></td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2018</td>
        <td>CliCR</td>
        <td>Exact Match</td>
        <td>F1</td>
        <td>BLEU-2</td>
        <td>BLEU-4</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://github.com/clips/clicr');">Baseline</button></td>
    </tr>					
    <tr>
        <td>2018</td>
        <td>ReviewQA</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2018</td>
        <td>ARC-Challenge Set</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://leaderboard.allenai.org/arc');">Leaderboard</button></td>
        <td><button onclick="window.open('http://data.allenai.org/arc/arc-baselines/');">Baseline</button></td>
    </tr>
    <tr>
        <td>2018</td>
        <td>ARC-Easy Set</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://leaderboard.allenai.org/arc');">Leaderboard</button></td>
        <td><button onclick="window.open('http://data.allenai.org/arc/arc-baselines/');">Baseline</button></td>
    </tr> 
    <tr>
        <td>2018</td>
        <td>OpenBookQA</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://leaderboard.allenai.org/open_book_qa/');">Leaderboard</button></td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2018</td>
        <td>SciTail</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://leaderboard.allenai.org/scitail/submissions/public');">Leaderboard</button></td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2018</td>
        <td>MultiRC</td>
        <td>F1m</td>
        <td>Exact Match</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://cogcomp.seas.upenn.edu/multirc/');">Leaderboard</button></td>
        <td><button onclick="window.open('https://cogcomp.seas.upenn.edu/multirc/');">Baseline</button></td>
    </tr>
    <tr>
        <td>2018</td>
        <td>RecipeQA</td>
        <td>Accuracy of Textual Cloze</td>
        <td>Accuracy of Visual Cloze</td>
        <td>Accuracy of Visual Ordering</td>
        <td>Accuracy of Visual Coherence</td>
        <td><button onclick="window.open('https://hucvl.github.io/recipeqa/');">Leaderboard</button></td>
        <td>N/A</td>
    </tr>	
    <tr>
        <td>2018</td>
        <td>PaperQA-Title(Park etc 2018)</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2018</td>
        <td>PaperQA-Last Sentence(Park etc 2018)</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2018</td>
        <td>PaperQA(Yining Hong etc 2018)</td>
        <td>F1</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2018</td>
        <td>MCScript</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://competitions.codalab.org/competitions/17184');">Leaderboard</button></td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2018</td>
        <td>ProPara</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://leaderboard.allenai.org/propara/submissions/public');">Leaderboard</button></td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2019</td>
        <td>Natrual Question(Short answer)</td>
        <td>Precision</td>
        <td>Recall</td>
        <td>F1</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://ai.google.com/research/NaturalQuestions/leaderboard');">Leaderboard</button></td>
        <td><button onclick="window.open('https://github.com/google-research-datasets/natural-questions');">Baseline</button></td>
    </tr>
   <tr>
        <td>2019</td>
        <td>Natrual Question(Long answer)</td>
        <td>Precision</td>
        <td>Recall</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://ai.google.com/research/NaturalQuestions/leaderboard');">Leaderboard</button></td>
        <td><button onclick="window.open('https://github.com/google-research-datasets/natural-questions');">Baseline</button></td>
    </tr>
    <tr>
        <td>2019</td>
        <td>DREAM</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://dataset.org/dream/');">Leaderboard</button></td>
        <td><button onclick="window.open('https://github.com/nlpdata/dream');">Baseline</button></td>
    </tr>
    <tr>
        <td>2019</td>
        <td>ShARC</td>
        <td>Micro Accuracy</td>
        <td>Macro Accuracy</td>
        <td>BLEU-1</td>
        <td>BLEU-4</td>
        <td><button onclick="window.open('https://sharc-data.github.io/leaderboard.html');">Leaderboard</button></td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>2019</td>
        <td>CommonSenseQA</td>
        <td>Accuracy</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://www.tau-nlp.org/csqa-leaderboard');">Leaderboard</button></td>
        <td><button onclick="window.open('https://github.com/jonathanherzig/commonsenseqa');">Baseline</button></td>
    </tr>
    <tr>
        <td>2019</td>
        <td>DROP</td>
        <td>EM</td>
        <td>F1</td>
        <td>N/A</td>
        <td>N/A</td>
        <td><button onclick="window.open('https://leaderboard.allenai.org/drop/submissions/public');">Leaderboard</button></td>
        <td><button onclick="window.open('https://allennlp.org/drop');">Baseline</button></td>
    </tr>
										 
										 
										 
												 
												 
</table>
<br />