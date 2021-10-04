# 7D Work Problem Model™

## Introduction

In the 21st century, work is still a miserable experience despite all the technological advances. Gallup reports that
only around one-fifth of today's global workforce is
engaged [[1]](https://github.com/kirkofypsi/7DWorkProblemModel/blob/main/README.md#references) and that employee
engagement has not significantly improved over the last decade. As job satisfaction strongly correlates with mental
health, dissatisfaction with work may partially explain the recent rise of psychological issues among working
adults. __The Institute for a Better Workplace__ believes the engagement issue must be addressed as it might have severe
economical and societal implications and such a dysfunctional work system cannot be maintained in a long term.

We believe that the decrease in work satisfaction largely stems from the fact that modern companies can deploy their
marketing departments to create favorable but largely untrue images of themselves. This in turn prevents the public
from realizing the weaknesses of organizations and creates the opportunity for companies to ignore bad practices negatively
impacting their employees' well-being. Our aim is to tear down the walls erected by companies and to provide a neutral point of 
view of the work world. To lay the groundwork for that we created an exhaustive catalog of the most common work
problems. We are introducing it to objectively compare different companies' work climates and to offer
a uniform, digestible, and easy-to-understand view of what is happening
at different work places.

## Catalogue of work problems

Work-related health risks have long been studied by scientists. Initially, those studies were almost completely
limited to physical work hazards but in recent decades, the focus has shifted towards mental and social factors and
how they affect workers' well-being. In scientific literature, they are usually referred to as *psychosocial stressors* or
*hazards*. We decided to use a simpler term – __work problem__ as we want to also shed light on work organizational
that prevent employees from achieving self-actualization and satisfaction from work, even if they are not
negatively affecting employees' mental health. Therefore, for us, the term __work problem__ represents any source of employees'
frustration, stress, or dissatisfaction in the workplace.

Unfortunately, there is an absence in the scientific literature of a reference taxonomy cataloging all factors leading
to dissatisfaction in the workplace, even if we limit ourselves only to psychosocial stressors and physical hazards.
Numerous attempts were made, most notably the ones described
in [[2],[3]](https://github.com/kirkofypsi/7DWorkProblemModel/blob/main/README.md#references) comprising 53 and 44
categories, respectively. Notwithstanding, in our opinion, they fail to cover all relevant dissatisfaction factors and were not
derived from analysis of really large datasets of employees opinions (1M+).

Given that absence, the __Institute for a Better Workplace__ decided to create its own taxonomy, which we believe to be the
most exhaustive one (currently comprising 130 categories) and the only one that has been tested on a large dataset of
employees' opinions. The taxonomy was derived from more than __1.5 million opinions__ about workplace experiences
reported by the employees of __389 global organizations__ and its creation was possible thanks to the support of machine
learning and NLP techniques that allowed us to discover hidden relationships between the contents of employees' reports.
1.5 million opinions is the equivalent of 200 average-sized books, so it is not surprising that traditional, manual
approaches to building taxonomies could not be applied in this case.

## 7D Work Problem Model™

The resulting taxonomy, called the __7D Work Problem Model™__, recognizes at the most granular level 130 different work
problems which suffice to classify more than 75% of our dataset of employees' opinions. One option that we rejected
was to build a taxonomy by grouping work problems into categories representing super-problems. We decided instead to
cluster work problems around __work satisfaction factors__ that are most negatively affected by them. For example, an
occurrence of a work problem "No freedom to speak one's mind" negatively impacts the aspect of
working at a company that supports the open-minded exchange of ideas. We call this satisfaction factor "Openness" and thus
the aforementioned problem is assigned to it along with the two other problems "Lack of transparency" and "Aversion
to risk or changes". Finally, work satisfaction factors were subsequently grouped into __work satisfaction dimensions__
representing crucial concepts from the areas of management and systems organization.

*Summary of 7D Work Problem Model™ taxonomy levels*

| Level (from the top)  |      Level name      |  Description  | Size |
|-----------------------|---------------------:|--------------:|-----:| 
|  1|  __Work satisfaction dimension__ |  high-level components of work satisfaction in the organization representing crucial concepts from the areas of management and systems organization | 7 |
|  2|  __Work satisfaction factor__   | low-level components of work satisfaction in the organization; work problems negatively affect work satisfaction factors | 39 |
|  3| __Work problem__ | any source of frustration, stress, or dissatisfaction for the employees in their workplace | 130 |

*An exempt from the 7D Work Problem Model™ structure:*

* __Opportunities__  &nbsp; &nbsp; &nbsp;  <-- *Work satisfaction dimension*
    * __Career growth__  &nbsp; &nbsp; &nbsp; <-- *Work satisfaction factor*
        * Poor career growth &nbsp; &nbsp; &nbsp; <-- *Work problem*
        * Difficulties in internal transfers &nbsp; &nbsp; &nbsp; <-- *Work problem*
        * Undefined career paths &nbsp; &nbsp; &nbsp; <-- *Work problem*
        * Outsiders favored over insiders &nbsp; &nbsp; &nbsp; <-- *Work problem*

The __7D Work Problem Model™__ does not represent a static taxonomy. It will be thoroughly reviewed every few  months and 
possibly modified to reflect new developments in research or changes in the world of work.

__The Institute for a Better Workplace__ decided to open-source work problem taxonomy in order to make it available to
researchers and companies interested in the topic. We hope that this taxonomy will be used to improve work
environments and the well-being of employees around the world.

## How can the 7D Work Problem Model™ be used?

The 7D Work Problem Model™ is a tool for conducting research in the field of work satisfaction as it comes with an
automated classifier that can be used to quickly and unbiasedly identify relevant work problems without the need for
expert review or manual tagging. Therefore, given a large enough dataset of employees' opinions
we can use it to:

* analyze work problems' distribution across different functions/locations/departments
* track how the number of work problems changes over time in a specific organization
* measure how satisfied employees from a given organization are comparing to the average for that industry
* compare the satisfaction of employees between different organizations.

Moreover, the analysis of new opinions is done in a matter of minutes and in a way that guarantees to all respondents
both a lack of bias and full anonymity which constitutes a significant improvement over traditional, manual solutions.

In the coming months, the __Institute for a Better Workplace__ will publish numerous reports on work problems in
different organizations. As a teaser of what is to come, we are publishing [here](industry.md) a report on the most
characteristic industry problems. The study was conducted using __1.5M__ opinions of employees from a total number of
__389 global organizations__ across __16 industries__.
<br/>
<br/>

## Explore [ 7D Work Problem Model™](taxonomy.md)

<br/>

## References

[1] https://www.gallup.com/workplace/352949/employee-engagement-holds-steady-first-half-2021.aspx

[2] Jean-Luc Kop, Virginie Althaus, Nadja Formet, Vincent Grosjean, Systematic comparative content analysis of 17
psychosocial work environment questionnaires using a new taxonomy, International Journal of Occupational and
Environmental Health, April 2016

[3]  Hamidrezaa Mokarami, Stefano Toderi, Reclassification of the work-related stress questionnaires scales based on the
work system model: A scoping review and qualitative study, Work, April 2019
