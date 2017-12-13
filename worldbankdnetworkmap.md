# World Bank - Network Map

The data set was parsed by splitting the original text into paragraphs. After parsing the data set successfully, term extraction was conducted to get a list of 100 terms from the data set. The list generated has “noun phrases” as the grammatical criteria. Finally, the network map was obtained using the Network Mapping script of Cortext. 

![af]({{ site.url }}/paradigmsofglobalization/assets/images/almost_full.PNG)

The map obtained is ranging over the period 1946-2012. There are a total of 9 clusters that have been generated in the map.  Broadly, the clusters are about these general themes – Loans, Developing Countries, Developed Countries, Poverty Reduction, Agriculture and health, World Bank Committee, Stock and Finance, IBRD and IDA.

![tags]({{ site.url }}/paradigmsofglobalization/assets/images/complete_with_tags.PNG)

In our analysis, we focused on the biggest cluster out of the 9, which is the Blue cluster called Developing Countries. As expected the cluster is overlapping with the Red Cluster (Poverty Reduction). We can see that the blue cluster is very evidently consisting of terms which fall under the ambit of “developing countries” – terms like – industrial countries, Latin America, South Asia and at the same time terms like – terms of trade, balance of payments, GDP growth, which reflect the indicators that these countries are judged by. We see a lot of links between the red and the blue cluster, a lot of which are through the term low-income countries, suggesting that the this node is a major link between the two clusters. 

![wb4]({{ site.url }}/paradigmsofglobalization/assets/images/4.PNG)

In figure above, we can see that low income countries connects East Asia, Latin America, developing countries, GDP growth, South Asia etc to debt relief, civil society, poor people, poverty reduction etc. The node World Bank has a direct edge to Developing countries which is suggestive of the fact that the World Bank does lay focus on the developing countries and their issues. The node South Asia has connections to poor people, Low-income countries, poverty reduction in the red cluster which again tells us something about the area of focus of World Bank when it comes to South Asia.

The Blue cluster is also linked significantly to the orange cluster which is named Agriculture and Health. In Figure below, we notice edges from agriculture production to population growth, South Asia, etc which suggests how the developing countries are connected to agricultural production (which south asia, India, Pakistan, Sri Lanka etc actually are).

![wb3]({{ site.url }}/paradigmsofglobalization/assets/images/3.PNG)

It is interesting to note that the edge between Health Care and Federal Republic of Germany is the only link between the cluster named Developed Countries and Agriculture and Health. 

 ![wb1]({{ site.url }}/paradigmsofglobalization/assets/images/1.PNG)

It is also to be noted that the cluster “Loans” is connected to developing countries through a single node, that is, Exchange Rates (See Figure below). 

![wb2]({{ site.url }}/paradigmsofglobalization/assets/images/2.PNG)

This is an important link as it might be telling us about the terms of the loans and other financial help that is extended to developing countries by the World Bank. It seems that the terms of these loans are dependent upon the balance of payments of the countries, which is quite logical in the real world since the lenders do always ensure the re-payment capacities of the borrowers.  The node Exchange Rates is connected to Interest Rates, credit risk, risk management etc which indeed point to the fact that the country’s exchange rate indirectly help in determining the terms of the financial help that is extended. 

The network Map produced is highly insightful if one wants to understand the subtle links between the focus of the World Bank. It is interesting to see how some the nodes are small, but they do serve as connectors. The analysis of a corpus becomes much more interesting when we run a network mapping script. Network mapping is an essential tool if one wants to discover linkages and dig deeper into the corpus. 


