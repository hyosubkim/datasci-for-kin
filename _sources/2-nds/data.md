# Data

“**Data**” are, ultimately, information. If we measure something, and it's always the same, then there is no information. Difference is the heart of information. But, differences can be meaningful in some way (signal), or meaningless, such as variation due to random factors (noise). Information are those differences that mean something — that make a difference. Meaning can be derived in many ways, such as through visualizations (graphing), statistical analysis, or making predictions about future data. These are all ways of identifying systematic patterns in data.

```{Note}
You may have noticed in the first sentence of the previous paragraph, I wrote  "data *are*"; I consider data to be a mass noun, like "sand", and not a count noun, like "sandwich". The singular of data is **datum**, which would be the smallest single unit of data. But we don't use that word much.
```

For the purposes of this class we assume that the data are collected in some way (measured), and stored digitally in files, typically as numbers or characters (words, sentences, etc.) — remembering that even digital media like movies or sounds are, ultimately, files composed of numbers. Data should be, however, more than just a bunch of numbers. Ultimately, data science is about identifying meaningful patterns in data. This informs our definition of "data" — data are sets of measurements *from which we aim to extract meaning*. As such, we assume that the data have been collected in such a way that meaning can be derived from them.

In doing data science, we focus less on the process of acquiring the data, and more on what we do after it's collected. That said, it is *critically important* to understand what your data are — which includes *what* was being measured, and *how* it was measured. Often we might also care about *why* the data were measured, but not necessarily; increasingly, researchers are making data sets openly available (e.g., through public repositories such as [OSF.org](https://osf.org)) not only for purposes of transparency, but with the expectation that other researchers might be able to use the data in ways other than originally intended, to generate new insights.  

Our approaches to working with data will necessarily be different, according to our understanding of what was measured, the underlying physiological properties, and our goals — the meaning we are trying to derive from the data. At the same time, all of these are ultimately measurements stored in files on a computer, and data science is about learning the core skills that allow you to work with any of these types of data and try to find meaning in them.

One final thought on the definition of data: since data are a combination of signal and noise, data may need various kinds of preparation or "cleaning" to strip away noise and more easily identify systematic patterns. When some people first encounter such practices, they raise questions about the validity of such practices, or whether they are "cooking" the data — manipulating it to generate the results the researcher desires. There is a huge, and fundamental, difference between manipulating data to generate a specific, predicted result, and cleaning data to minimize noise and optimize finding the signal. Approaches to data cleaning should be systematic, well-reasoned, and accurately reported. In data science, data cleaning procedures are typically well-understood and supported by the peer-reviewed scientific literature. In contrast, manipulating the data to achieve specific ends typically involves dishonest practices such as arbitrarily removing or adding data to create a data set that generates specific results (often without reporting how or why the data were thus manipulated). Dishonest practices are not accepted in the scientific community, and people caught manipulating their data are typically publicly discredited (or at least privately discredited, within social networks), and subsequently find it hard to obtain work or the respect of their peers.


---
This section was adapted from Aaron J. Newman's [Data Science for Psychology and Neuroscience - in Python](https://neuraldatascience.io/intro.html).