Using the files `apsr_article_coding_template` and `ajps_article_coding_template`, please code the topic and type of each article. Replace `template` with your initials and save the file to Box.

### What do I look for?
Find out the research field (topic) and type of each article. We want to investigate differences across fields and whether an article could have made data available. This is important because if the type of articles submitted to a journal change because of the data sharing requirement, our analysis method may be a bit suspect.

### How do I classify an article into a research field?
There are five research fields (topics)

+ `political_theory`
+ `comparative_politics`
+ `international_relations`
+ `american_government_and_politics`
+ `political_methodology`

Use the classification from [What is Political Science?](https://www.polisci.washington.edu/what-political-science) to classify each article into one of above research fields using the `article_field` column.

You can start by looking at an article's abstract. If the abstract alone is not sufficient to classify the article, read through the article's introduction.

If you have trouble finding the correct research field for an article after above steps, leave `article_field` empty.

If an article falls into multiple categories, pick the primary and secondary category. Do not assign a secondary category unless an article really does cover two topics.

Classifying articles may be difficult. Read the list above. Also, from Wesleyan:
> Political Theory is a distinct field within the discipline of political science. Political theorists tend to focus more on theoretical claims rather than empirical claims about the nature of the politics. Normative political theory is concerned with questions about such concepts as justice, equality, and rights. Historical political theory engages political philosophers from the past (e.g. Thucyides and Plato) to the present (e.g. Wendy Brown and Seyla Benahabib), and may focus on how particular philosophers engaged political problems that continue to be relevant today. While the focus has traditionally been on Western traditions, that is beginning to change in this field.

So don't call everything `political_theory`--real theory will often go hand in hand with `no_data` and feature famous philosophers you may know: Marx, Locke, Mills, Rawls, etc. A paper on say, the courts in the US and UK would be American and Comparative.


### How do I classify an article into a data type?
There are four data types

+ `no_data`: The article does not use any data (e.g. pure theory)
+ `simulations`: Article has data, but it is simulated, i.e. generated by a computer and not from the real world (e.g. methodology or econometrics articles).
+ `experimental`: The article uses experimental data from laboratory or field experiments conducted by researchers (i.e. randomized experiments, not *natural* experiments)
+ `observational`: The article uses observational data (e.g. from surveys, publicly available datasets, own collection)

### What about non-articles? (e.g. front matter)
Please put `skip` for both topic and type for lines in the spreadsheet that aren't really articles, such as front matter and some letters from the editor.

### Tip
`Ctrl/⌘ + Click` on the article title to open the article. You do not need to press `Ctrl/⌘`, if you uncheck `Ctrl-click required to follow hyperlinks`, which you can find in `LibreOffice` -> `Preferences` -> `Security` -> `Options`.

