---


---

<h1 id="understanding-nlp--concept---approaches">Understanding NLP : Concept &amp;  Approaches</h1>
<p><img src="https://github.com/riti2043/images-for-articles/blob/main/nlp1.jpeg?raw=true" alt="img upload failed"></p>
<h4 id="what-is-nlp">What is NLP?</h4>
<p><em>Natural language processing</em> (NLP) is a subfield of computer science and artificial intelligence that uses machine learning to enable computers to read, understand and derive meaning from human languages. The objective is to program computers to process and analyze large amounts of natural language data.</p>
<hr>
<h4 id="benefits-of-nlp">Benefits of NLP</h4>
<p>NLP makes it easier for humans to communicate and collaborate with machines, by allowing them to do so in the natural human language they use every day. This offers benefits across many industries and applications like :</p>
<ul>
<li>Chatbots</li>
<li>Text and Image Classification</li>
<li>Automation of repetitive tasks</li>
<li>Speech Recognition</li>
<li>Sentiment Analysis</li>
<li>Content generation</li>
<li>Named Entity Recognition</li>
<li>Information retrieval</li>
</ul>
<hr>
<h4 id="nlp-approaches">NLP Approaches</h4>
<p>Before a computer can process language, it must first analyze its structure and meaning. This is done through <strong>computational linguistics</strong>, which uses data science to break down language into its core components. When a computer “reads” a sentence, it performs two main types of analysis to figure out what it means:</p>
<ol>
<li>
<p><strong>Syntactical Analysis</strong><br>
This is about the <strong>structure</strong> and <strong>grammar</strong> of a sentence. It looks at how words are arranged and their relationships to each other. For a computer, this is like making sure a sentence follows a set of rules, such as identifying the subject and the verb. This process is called <strong>parsing</strong>.</p>
</li>
<li>
<p><strong>Semantical Analysis</strong><br>
This is about the <strong>meaning</strong> of the words. It takes the output from the syntactical analysis and tries to interpret the words’ actual meaning within the context of the sentence. This helps the computer understand nuances, like if the word “bank” refers to a financial institution or the side of a river.</p>
</li>
</ol>
<p>Basically, syntactical analysis ensures the sentence is grammatically correct, and semantical analysis ensures it makes sense.<br>
<img src="https://github.com/riti2043/images-for-articles/blob/main/Machine-Learning-Approaches-1.jpg?raw=true" alt=""></p>
<p>The methods used to build NLP systems have evolved dramatically over time, reflecting major advances in technology and our understanding of language. We can broadly categorize the approaches to NLP into three distinct eras, each with its own set of techniques and limitations.</p>
<ol>
<li><strong>Rule Based Approach:</strong><br>
The rule-based approach is one of the oldest natural language processing approaches, where predefined linguistic rules are represented to analyze and process textual data. This method is effective for specific domains where linguistic rules are well-defined. The given textual data will be used to extract specific patterns, and structures and to perform tasks such as text summarization, chatbots, text classification and so on by applying a particular set of rules but this is labour-intensive to create and maintain rules for large and diverse datasets and have limited adaptability to new or evolving language patterns.</li>
</ol>
<h4 id="steps-in-rule-based-approach-in-nlp">Steps in Rule-based approach in NLP:</h4>
<ol>
<li><strong>Rule Creation:</strong>  Based on the desired tasks, domain-specific linguistic rules are created such as grammar rules, syntax patterns, semantic rules or regular expressions.</li>
<li><strong>Rule Application:</strong> The predefined rules are applied to the inputted data to capture matched patterns.</li>
<li><strong>Rule Processing:</strong>  The text data is processed in accordance with the results of the matched rules to extract information, make decisions or other tasks.</li>
<li><strong>Rule refinement:</strong>  The created rules are iteratively refined by repetitive processing to improve accuracy and performance. Based on previous feedback, the rules are modified and updated when needed.<br>
<img src="https://github.com/riti2043/images-for-articles/blob/main/Rule-based-nlp.jpg?raw=true" alt="img failed to load"></li>
</ol>
<p>2.<strong>Machine Learning Approach</strong>:</p>
<p>The machine learning approach uses statistical models to learn underlying patterns from data and make predictions or classifications without explicit programming. It automatically extracts, classifies and labels elements of text and voice data and then assigns a statistical likelihood to each possible meaning of those elements. This approach can handle large amounts of data and capture underlying relationships between words or phrases and it can learn from the diverse datasets and adapt to different language patterns, making them versatile for various NLP tasks.</p>
<p>However, the performance will heavily rely on the quality and quantity of the training data and may not capture complex relationships with basic and traditional models.<br>
<img src="https://github.com/riti2043/images-for-articles/blob/main/a8pvvie3kye81.webp?raw=true" alt=""></p>
<p>3.<strong>Deep learning NLP</strong></p>
<p>Recently, deep learning models have become the dominant mode of NLP, by using huge volumes of raw, unstructured data both text and voice to become ever more accurate. Deep learning can be viewed as a further evolution of statistical NLP, with the difference that it uses neural network models. There are several subcategories of models:</p>
<ul>
<li>
<p><strong>Sequence-to-Sequence models</strong>: Based on recurrent neural networks (RNN), they have mostly been used for machine translation by converting a phrase from one domain (such as the German language) into the phrase of another domain (such as English).</p>
</li>
<li>
<p><strong>Transformer models</strong> : They use tokenization of language (the position of each token words or subwords) and self-attention (capturing dependencies and relationships) to calculate the relation of different language parts to one another. Transformer models  can be efficiently trained by using self-supervised learning on massive text databases.</p>
</li>
<li>
<p><strong>Autoregressive models</strong>: This type of transformer model is trained specifically to predict the next word in a sequence, which represents a huge leap forward in the ability to generate text. Examples of autoregressive LLMs include GPT, Claude etc</p>
</li>
<li>
<p><strong>Foundation models</strong>: Prebuilt and curated foundation models can speed the launching of an NLP effort and boost trust in its operation. They support NLP tasks including content generation and insight extraction. Additionally, they facilitate retrieval-augmented generation, a framework for improving the quality of response by linking the model to external sources of knowledge. The models also perform named entity recognition which involves identifying and extracting key information in a text.</p>
</li>
</ul>
<p>This progression from simple, hand-coded rules to complex neural networks is a testament to the ongoing challenge and innovation in teaching machines to understand and interact with human language.</p>

