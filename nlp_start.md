<h1 align = "center"> NLP NOTES</h1> 

> ## NLP VS NLU

>>NLP (Natural Language Processing): It understands the text's meaning. 
NLU (Natural Language Understanding): Whole processes such as decisions and actions are taken by it.


| NLP | NLU    |
| ---   | --- |
| From the computer’s point of view, any natural language is a free form text. That means there are no set keywords at set positions when providing an input.|NLU Considered a subtopic of NLP, the main focus of natural language understanding is to make machines:<br>(1) Interpret the natural language <br>(2) Derive meaning <br>(3) Identify contex <br>(4) Draw insights |
|Beyond the unstructured nature, there can also be multiple ways to express something using a natural language. For example, consider these three sentences:<br><br>(1)How is the weather today?<br>(2)Is it going to rain today?<br>(3)Do I need to take my umbrella today?<br><br>All these sentences have the same underlying question, which is to enquire about today’s weather forecast.<br><br> As humans, we can identify such underlying similarities almost effortlessly and respond accordingly. But this is a problem for machines—any algorithm will need the input to be in a set format, and these three sentences vary in their structure and format. And if we decide to code rules for each and every combination of words in any natural language to help a machine understand, then things will get very complicated very quickly. <br><br> This is where NLP enters the picture.<br><br>NLP is a subset of AI tasked with enabling machines to interact using natural languages. The domain of NLP also ensures that machines can:<br><br>(1)Process large amounts of natural language data<br>(2)Derive insights and information<br><br> But before any of this natural language processing can happen, the text needs to be standardized.|For example, in NLU, various ML algorithms are used to identify the sentiment, perform Name Entity Recognition (NER), process semantics, etc. NLU algorithms often operate on text that has already been standardized by text pre-processing steps. <br><br>Going back to our weather enquiry example, it is NLU which enables the machine to understand that those three different questions have the same underlying weather forecast query. After all, different sentences can mean the same thing, and, vice versa, the same words can mean different things depending on how they are used.<br><br> Let’s take another example:<br><br>(1)The banks will be closed for Thanksgiving.<br>(2)The river will overflow the banks during floods.<br><br>A task called word sense disambiguation, which sits under the NLU umbrella, makes sure that the machine is able to understand the two different senses that the word “bank” is used.|

> ## Natural Language vs Formal Language

| Aspect                 | Natural Language        | Formal Language         |
|------------------------|-------------------------|--------------------------|
| Definition             | Language spoken and written by humans in everyday communication | Language with precise syntax and semantics used in technical fields such as mathematics, logic, and computer science |
| Examples               | English, Spanish, Chinese, etc. | Regular expressions, context-free grammars, logic, SQL, etc. |
| Characteristics        | Flexible, ambiguous, context-dependent, variable in structure | Precise, structured, unambiguous, and consistent |
| NLP Tasks              | Sentiment analysis, named entity recognition, machine translation, etc. | Formal languages used in defining rules, grammars, or constraints for NLP tasks |
| Applications           | Text analysis, machine translation, virtual assistants, etc. | Text processing, parsing, knowledge representation, and querying |
| Role in NLP            | The subject of analysis and generation in NLP tasks | Used to create models, rules, and tools for processing natural language |
| Use Cases              | Understand and generate human language | Define syntax, constraints, and processing rules for NLP systems |
| Examples in NLP        | Sentiment analysis of customer reviews, machine translation of news articles | Defining grammars for parsing sentences, writing regular expressions for text extraction |
