# Search Optimization on Etsy

![](etsy_logo.png)

Etsy, a platform where crafters sell their handmade goods, provides an interesting investigation into how online retailers use search optimization to enhance the user experience. Unlike, other e-commerce sites however, Etsy is a two-sided marketplace, meaning that buyers are searching for interesting and unique goods while sellers are using the platform Etsy provides to reach more buyers. The general idea behind search optimization is to take mass amounts of low-level data and draw high-level conclusions that aim to uncover customers thoughts about why they came to the Etsy site, what style products they like, if they buy product X, do they also want product Y that is related, etc. Knowing the answers to these questions by observing data is a powerful tool to create a more personalized search experience in a remote setting.

High-level knowledge is obtained from recording almost every click from website users. The clicks simply mean nothing by themselves, but when tracked from every customer, patterns can be discovered and used to make an algorithm that rank search results. According to Etsy, “Search engines like to show results that are relevant and interesting, but gauging "interestingness" is a bit tricky for a computer” (“Shop”). One metric Etsy uses as an algorithm input is a listing quality score. Every time a customer clicks on, favorites, or purchases an item, it improves the products quality score. Items with higher scores are more “interesting” and have a potential to appear higher on the search results. The sellers themselves also input attributes or keywords, which allows Etsy to take these descriptions and match them to the customers search as well as data on consumers’ actions from the listing quality to create a blend of search results. For example, if a customer searches for a “crochet hat” patterns might reveal they want a written pattern versus when they search “winter hat” the pattern shows they want a finished good. The patterns are the voice that talks to the algorithm to say what customers like and they style product they are after so the search can be ranked appropriately. 

Researchers at Cornell university did a project on search optimization for two sided marketplaces and found that a linear composition of various metrics was best. While their model is not the exact algorithm Etsy uses, it is a proposed model for businesses with models like Etsy. They combined the metrics such as Normalized Discounted Cumulative Gain, a relevance metric of “between a goldset list of documents and the permutation return” (Stanton) and Expected Reciprocal Rank, or how they expect users will engage with the rankings, Weighted Importance Ranking, the Gini Index, which considers perfect income equality compared to the actual wealth distribution of subpopulations, into a final Fitness Function. 

Due to the optimized results being a manipulated version of an organic search, there are some ethical considerations as to which party is being hurt, either the buyer or the seller, when search results are changed because errors do occur. If a customer searches for an outdoor pillow, pillows with fabrics not specifically designed for outdoor use can appear if a pattern was discovered from previous customers. This is detrimental for sellers as well, because if customers mistakenly purchase a product that does not accurately fit their needs, it reflects poorly on the seller’s business. Despite mistakes happening, optimization models aim to help however. The machine learning can save time for buyers, and time has a great value associated with it. Data scientists are always searching for ways of improving the algorithm the learn more about their customers in order to help. 

![](seo.jpg)

# Works Cited

Cameron, Jeanine. “This Data Scientist for Etsy Finds Art In Programming.” Career Contessa, Career Contessa, 25 Jan. 2018, www.careercontessa.com/interviews/diane-hu-data-scientist-etsy/. 

“How Etsy Search Works.” Etsy Help Center, help.etsy.com/hc/en-us/articles/115015745428-How-Etsy-Search-Works?segment=selling. 

“Shop Improvement and Search Engine Optimization (SEO).” Etsy Help Center, help.etsy.com/hc/en-us/articles/115015663987-Shop-Improvement-and-Search-Engine-Optimization-SEO-?segment=selling. 

Stanton, Andrew, et al. “Revenue, Relevance, Arbitrage and More: Joint Optimization Framework for Search Experiences in Two-Sided Marketplaces.” Cornell University, 15 May 2019, arxiv.org/abs/1905.06452. 
