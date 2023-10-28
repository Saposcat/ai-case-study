# Nationwide Children's Hospital  : AI Research and Recommendations

## Table of contents
- [Overview and Origin](#overview-and-origin)
- [Business Activities](#business-activities)
- [Landscape](#landscape)
- [Results](#results)
- [Recommendations](#recommendations)
- [Bibliography](#bibliography)



## Overview and Origin <a name="overview-and-origin"></a>


* Name of company
  * Nationwide Children's Hospital; affiliated with Ohio State University College of Medicine (Wikipedia.org)


* When was the company incorporated?
  * The original children's hospital of Columbus was opened in 1892; it was renamed to Nationwide Children's Hospital upon getting a grant for $50 million from the Nationwide foundation of Nationwide insurance. (Wikipedia.org)


* Who are the founders of the company?
  * The founders of the company were a group of 12 women of whom the website makes no further mention (nationwidechildrens.org). However, another source says, at least, that the women in question were part of a sewing circle (library.osu.edu).


* How did the idea for the company (or project) come about?
  * The women wanted to create a hospital that would give the best care to children regardless of their families ability to pay (nationwidechildrens.org)


* How is the company funded? How much funding have they received?
  * it is a nonprofit organization that is funded by a variety of sources, most of them philanthropic, government related, and grants. (Nationwidechildrens.org)(crunchbase.com)(nationwide.com),(dispatch.com),(abc6onyourside.com)


## Business Activities <a name="business-activities"></a>


* What specific problem is the company or project trying to solve?
  * Being a children's hospital that was founded on the idea that children should be given care even if families cannot afford to pay for it, I would say that Children's health is the main project of the Business. However, the business has grown a lot and has also contributed a lot of research to the field of healthcare by now. (Nationwidechildrens.org)


* Who is the company's intended customer? Is there any information about the market size of this set of customers? 
  * The intended customer would, naturally, be a sick child, but in a manner of speaking, their caretakers are customers too for the experience they have with the hospital will also matter to the reputation of the hospital, as well as its ability to bring money in by means of grants and donations. (Nationwidechildrens.org)


* What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?) 
  * I'm not sure if Nationwide childrens offers any singular solution that none of its competitors offers as I could find no mention of such a thing; actually, one would expect (and hope) that such is the case in the event of technology which makes healthcare easier. What I can say is that Nationwide, in the aggregate, probably has more solutions available than most other competitors in their field as they have poured a lot of money into RND in the AI field and have the resources available to do it.




* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing. you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)
  * As far as the relevant AI space goes, the hospital is focusing on doing research in the NLP space in order to expedite the administrative procedures of hte hospital. A lot of the note taking is templated and does not really require AI, but technology which summarizes phone calls and puts them into a brief text format is being utilized and continuously developed. There are also a lot of methods which are using statistical analysis that does not go into the machine learning field like standard linear models which are easier to get buy-in for than black box models when dealing with certain tasks such as diagnosing patient illnesses. However, there are also initiatives to use image processing in order to determine and rule out ailments of patients. (Sirrani, J.)


## Landscape <a name="landscape"></a>


* What field is the company in?
  * Healthcare


* What have been the major trends and innovations of this field over the last 5 to10 years?
  * Since BERT came out in 2018, NLP really has been the trend at hospital AI projects and a lot of research has gone into it in hospitals in general. Another trend is the rise of cloud computing as a result of all the machine learning and AI technology which is being fielded in this space as most hospitals do not have the resources to have their own array of high performance compute servers running locally. (Sirrani, J.)


* What are the other major companies in this field?
  * If we see the competitors as being other children's Hospitals which are regionally close enough to be considered valid competitors, the biggest competitors would be Cincinnati Childrens, the Mayo Clinic (which has a collaboration with google for AI and machine learning stuff), and Boston Childrens. But they are not merely competitors, but also collaborators on a lot of AI projects. (Sirrani, J.)


## Results <a name="results"></a>


* What has been the business impact of this company so far?
  * Nationwide has, for about 130 years now been providing healthcare to children at affordable prices; that is quite a business impact on its own, but nationwide has also made some breakthroughs within research during its history running as a Children's Hospital as well.


* What are some of the core metrics that companies in this field use to measure success? How is your company performing based on these metrics?
  * A lot of hospitals have to pay penalties if patients return too soon after being discharged, which is a measure of success in treating people, but one can also look toward customer satisfaction and the reduction of administrative workload from the perspective of the AI side of things to determine how successful Nationwide has been. In that respect, Nationwide is still a bit behind the times, but surely catching up and investing a lot of research time into the field. The other way of telling the success of the hospital would be to consider the total amount of grants which it has brought in. That would be especially relevant to anyone who is in research, such as in the field of AI. (Sirrani, J.)


* How is your company performing relative to competitors in the same field?
  * Nationwide Childrens is usually rated somewhere around 9th in the US which puts it into pretty hot competition with Cincinnati Childrens which is usually rated 3rd in the US; Nationwide is, therefore, doing quite well for itself, though there is still quite the chance for improvement. (Sirrani, J.)


## Recommendations <a name="recommendations"></a>


* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)
  * One of the things that the hospital does not yet do well as far as administrative tasks go is that a "chat gpt for physician notes" is not yet fully developed and the use of tools like suki.ai has also not been adopted. Part of the reason for this is that, unlike the tech motto of "move fast and break things", hospitals cannot do this as too many lives are genuinely at stake; moving fast and breaking things is really the opposite of what hospitals are trying to do. Another problem the company faces is within the use of AI imaging technology. Hospital data, on account of its geographic limitations is not necessarily diverse enough to make a model which will predict equally well everywhere, and it could miss certain demographics entirely which would be the cause of much controversy. Collaborations with other Hospitals about data are not unheard of, but merging disparate datasets whith different formats without looking at the information and breaking healthcare privacy guidelines remains a serious challenge. (Sirrani, J.) My recommendation, however, would be to work on finding a way to make a unified dataset, perhaps utilizing AI methods in order to create a method for extracting relevant information from disparate datasets without human eyes being put on it.


* Why do you think that offering this product or service would benefit the company?
  * It would benefit them for the reasons which I have just explained: that it would allow hospitals to have more data available for research; it would benefit not only Nationwide Childrens, but hospitals everywhere.


* What technologies would this additional product or service utilize?
  * It might have to be some sort of unsupervised learning algorithm so as not to have human eyes on the data, however, it seems to me that there would nevertheless have to be some human eyes on the data in order to make sure that the models are working appropriately well which might imply that supervised remains an option also. Maybe the solution would be to have a lot of doctors "invent" fake patient records which seem realistic so that the model could be trained on those records, but that doesn't sound like a particularly good idea when we consider all the liability that unreflective patient records bring. Another method would be to perhaps find a training set of people who willingly volunteer their data for the study, but that probably would also give a biased set of patients as these would be individuals who are likely feeling more desperate in their medical situation.


* Why are these technologies appropriate for your solution? I think the reasons have been explained in the previous paragraph already.
  * AI and ML algorithms should scrape data and put it into a usable format for other machine learning algorithms to utilize without humans having to touch the true data very much. If some workaround to the problem of requiring humans to look at genuine medical data were to be found, I suppose it wouldn't matter so much if the method were supervised or unsupervised, assuming that no misdiagnoses were made from which the labeling of the data could create inaccurate results. I imagine this to be a lesser problem, however.


## Bibliography <a name="bibliography"></a>


* Sirrani, J. (2023, October 26). Personal interview [Data Scientist at Nationwide Children’s Hospital].
* Nationwide Children’s Hospital. (n.d.). History and Milestones. Retrieved October 27, 2023, from https://www.nationwidechildrens.org/about-us/our-story/history-and-milestones
* Nationwide Children’s Hospital. (n.d.). About Us. Retrieved October 27, 2023, from https://www.nationwidechildrens.org/about-us
* Rodgers, J. (2016, September 15). Nationwide Children’s Hospital. Retrieved October 27, 2023, from https://library.osu.edu/site/mhcb/2016/09/15/nationwide-childrens-hospital/
* Nationwide Children’s Hospital. (2023, October 27). In Wikipedia. Retrieved October 27, 2023, from https://en.wikipedia.org/wiki/Nationwide_Children%27s_Hospital
* Nationwide Children’s Hospital. (n.d.). Our Story. Retrieved October 27, 2023, from https://www.nationwidechildrens.org/about-us/our-story
* Nationwide Children’s Hospital. (n.d.). Fast Facts. Retrieved October 27, 2023, from https://www.nationwidechildrens.org/about-us/our-story/fast-facts
* Nationwide Children’s Hospital. (2021, June 16). Strategic Plan: Transforming Health Outcomes for Children Locally and Around the World. Retrieved October 27, 2023, from https://www.nationwidechildrens.org/newsroom/news-releases/2021/06/strategic-plan
* ABC6 News Staff. (2021, June 16). Nationwide Children’s Hospital announces expansion. ABC6OnYourSide.com. Retrieved October 27, 2023, from https://abc6onyourside.com/news/local/nationwide-childrens-hospital-announces-expansion-6-16-2021
* Nationwide Children’s Hospital Research Institute IT Research and Innovation Grant Funding | Crunchbase Company Profile & Funding. (n.d.). Retrieved October 27, 2023, from https://www.crunchbase.com/organization/nationwide-childrens-hospital
* Nationwide Insurance Foundation | Giving | NCH | Nationwide Children’s Hospital Foundation | Columbus Ohio (n.d.). Retrieved October 27, 2023, from https://www.nationwide.com/personal/about-us/giving/nch/
* Weiker, J., & Schladen, M. (2021, June 16). Nationwide Children’s to spend billions on new hospital buildings, programs. The Columbus Dispatch. Retrieved October 27, 2023, from https://www.dispatch.com/story/news/2021/06/16/nationwide-childrens-spend-billions-new-hospital-buildings-programs/7687094002/

