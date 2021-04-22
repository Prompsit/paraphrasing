# Paraphrasing project
##Determining frequent paraphrases for arbitrary expressions... to help machines improve their linguistic capabilities

A TSI-100905-2019-4 project, co-financed by Ministry of Economic Affairs and Digital Transformation from the Government of Spain

<img alt="THD Logo" src="ministerio-tdh-logo.svg" style="margin-bottom: 1rem;" height="75" />

# The problem

Humans are able to understand easily that all of the sentences in the previous animation have the same meaning. However, for machines this is a complicated task and, in fact, one of the biggest limitations currently in human-machine communication. Paraphrasing is the linguistic mechanism we use to express the same message with different structures and words.

A lot of variability is introduced in our language through paraphrasing. The management of this is so complex that it takes a toll on our experience interacting with numerous applications in our day-to-day life. For example, it makes us rewrite over and over our queries in the text field of search engines, and also narrow down our language when we use voice assistants. It also affects many work fields, such as, automatic translation, interaction with chat bots, document classification, etc.

A great deal of effort is invested in order to control this limitation and endeavour to make systems answer to any given input, working on the resilience of systems to language variability. This is achieved through dictionaries, rules, statistic technologies, or neuronal learning. These approaches have to deal with some issues, including context specific ones.

Instead of making a system that is resistant to language flexibility, our approach focuses on learning from this variability. We search for efficient mechanisms to generate said flexibility, ensuring we can recognise and then use it in specific applications.

# Our approach

* Variability in contrast with the rigidity of previous solutions
* From a general approach to more specific solutions
* Multilingual — English, Spanish and Portuguese
* Big Data — high quality data, diverse and numerous
* An heterogeneous solution in three phases: artificial intelligence, statistical techniques and language modelling

# Phases

1. Acquisition and text segmentation: 
    * Detection of phrases likely to be paraphrased
    * Gathering and cleaning of textual resources
    * Implementation of a method of text segmentation in meaningful units
3. Paraphrase generation with diverse techniques
    * Statistic and neuronal automatic translation (advanced encoder-decoder models, transformer, Bert)
    * Synonyms dictionaries and lemmatizers
    * Context vectors, word, phrase and sentence embeddings
    * Language models
    * Further research into other applicable technologies
5. Classification and validation of paraphrases
    * Automatic classification: neural networks, support vector machines, random forest, etc.
    * Human validation

# Results 

1. Corpora
Corpora sized 10 million sentences each and containing high-quality monolingual content have been compiled from online and offline sources
   * Spanish: https://parafrasis.prompsit.com/downloads/corpora/spanish.xz
   * English: https://parafrasis.prompsit.com/downloads/corpora/english.xz
   * Portuguese: https://parafrasis.prompsit.com/downloads/corpora/portuguese.xz
2. Code (coming by the end of 2021)
3. Papers
   * EAMT 2020 paper using the tools to get to high-quality monolingual corpora applied to corpora cleaning and its impact in machine translation


# Acknowledgment 

 This is a TSI-100905-2019-4 project, co-financed by the Ministry of Economic Affairs and Digital Transformation from the Government of Spain. 
