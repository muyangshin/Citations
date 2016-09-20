# What should I look for?
References to the data or code used in the article.

# What is a reference?
A reference has 3 dimensions:

1. *What* is referenced? It must be one of the following.
+ data
+ code
+ files = data + code

2. *How much* is referenced?
If referenced data or code is for the entire article, it is a *full* reference. Sometimes the reference is only for part of the data, e.g. only for a single variable, or the code. We call this *partial* reference.

3. *How* is it referenced?
+ link: The reference provides a URL
+ name: The reference mentions the name of a dataset, an institution or website without providing a URL

# How do I classify the matches?
If a match is not a reference to the data or code used in the article, it is irrelevant. We code this as `0`.

If a match is a reference, classify it along the 3 dimension mentioned above using underscores `_` as separators. If a reference is partial, add `partial`. Some examples:

+ `data_full_link`: Reference provides a URL to *all* of the data used in the article
+ `data_partial_link`: Reference provides a URL to parts of the data, e.g. certain variables, used in the article
+ `data_partial_name`: Reference mentions the name where parts of the data can be found, e.g. some variables are provided by an institution
+ `code_partial_link`: Reference provides a URL to some of the code used in the article, e.g. reference for code used in simulation, but no reference for code used in analysis
+ `files_full_name`: Reference mentions a location where both, data and code, can be found, e.g. the author's website

# Tip
For faster data entry, you can label irrelevant matches using a key close to your 'enter' key, and replace that character with `0` later one.