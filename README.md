# KafkaTextAnalytics
Exploratory Text Analysis on Kafka's various works


My source material consists of select works by Franz Kafka, primarily those that have been translated from German to English (this was a limitation for the sake of interpretability). The collection includes Kafka's major novels - *The Trial*, *The Castle* and *Amerika* - in addition to novellas such as *The Metamorphosis* and *The Judgement*, and a myriad of short stories including *A Country Doctor* and *The Hunger Artist*. The translations used were primarily by Ian Johnston, Edwin and Willa Muir, and Tania and James Stern. I accessed these texts through publically availably literary archives such as Project Gutenberg, as well as other online repositories of classic literature. While an estimated 90% of Kafka's work was lost or destroyed (often by Kafka himself), what remains forms the core of my analysiss on one of my favorite authors of all time.


The internal structure of each document changes based on the type of work. Kafka's novels, such as *The Trial* and *The Castle*, are typically divided into chapters, which are often unnammed or simply numbers using Roman numerals. However, short stories (such as *A Country Doctor*) and novellas typically consist of a continous body of text without chapter breaks. Works like *Meditation* are structured as a collection of short stories and prose pieces, the smallest of which can be a paragraph in length, often more allegorical than narrative in nature. 
Because of this variety, we anticipate that analytical approachs like bag-of-words models face challenges when applied uniformly across the texts. To account for these differences, we may isolate texts by form - for instance, analyzing only the novels or only short stories when structural consistecy is needed. In other scenarions such as sentiment analysis or thematic clustering, it might make more sense to include the entire corpus regardless of structural variation.


