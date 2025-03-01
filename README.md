## Background

Here I juxtapose the reigns of a subset of Roman emperors against the (literal) arc of their lives.

Some things to note:

* The analysis here is superficial and I have not performed the kind of thorough consultation of primary sources necessary to formulate solid conclusions regarding manner of death. I am not a historian nor otherwise trained in historical methods. Dates in the original dataset are also largely estimates, and so I therefore gladly invite corrections to these data where necessary.

* Dates here are sourced from a dataset compiled by others here. Note in particular that the absolute values of BCE dates are decreased by 1 to conform to the ISO 8601 standard.
  - Thanks to zonination for creating this dataset.
  - Note: I did manually make some corrections to names in the final visualization.
 
* Invididuals are presented in the order in which they first rose to office, **not** the order in which they died.

* While I did rely on the aforementioned dataset for dates, I chose to review a different source for information on the deaths of emperors. I principally reviewed De Imperatoribus Romanis, a peer-reviewed encyclopedia of Roman rulers which I judged to be suitable for this project and which I noted as being used for a statistical analysis in a recent scholarly publication. It is recognized, however, that the writings there are generally decades old and may not reflect the most current scholarly consensus. Again, I invite corrections.

  - Thanks to Christian Körner, Christopher J. Fuhrmann, David Wend, David Woods, Dennis Quinn, Garrett G. Fagan, Geoffrey Nathan, Hans A. Pohlsander, Herbert W. Benario, John Donahue, Michael DiMaio, Jr., Michael L. Meckler, Noel Lenski, Phoebe B. Peacock, R. Scott Moore, Ralph W. Mathisen, Richard D. Weigel, Robert Frakes, Robin McMahon, Thomas Banchich, Walter E. Roberts, and William Leadbetter for their contributions to De Imperatoribus Romanis which I reviewed in annotating probable manner of death.

* I mapped the descriptions of emperors deaths in De Imperatoribus Romanis to the same death classification scheme used in the original dataset's repository, as it seemed to reasonably capture the meaningful context of all emperors' deaths in the broad manner necessary for this visualization.

* Finally, thanks to David Bacci for showcasing the [Coronation Arc chart](https://github.com/PBI-David/Deneb-Showcase/blob/main/Coronation%20Arc%20Chart/Thumbnail.png) marking the coronation of Charles III of the United Kingdom. I was immediately struck by the elegance of that visualization and I am grateful for the availability of his Vega specifications which inspired this project.

#### Please see emperors.ipynb for methodological details.

#### Update 2025-03-01 (Changes not yet pushed to repo)
I posted the first iteration of this graphic to Reddit [here](https://www.reddit.com/r/dataisbeautiful/comments/1iw1qce/oc_visualizing_the_lifetimes_and_reigns_of_a/) and received very useful feedback. Here are some notes on changes made and thoughts related to specific feedback: 

* Changed the icon for Nerva's death to *natural causes* instead of *assassination*. I did have the corect manner of death recorded for Nerva, but placed the wrong icon when adding the iconography. Thanks to the user who spotted this.

* I received some feedback suggesting that one or more emperors may be in the wrong order because, for example, the graphic presents L. Verus after Marcus Aurelius despite Aurelius outliving Verus. It should be noted, however, that the graphic is not ordered by date of death, but rather date of ascension to the office of emperor. To help reduce confusion, I have added a note to that effect to this repository's ReadMe. However, in the case of Aurelius and Verus in particular, it appears that they both assumed office on the same day; given that Verus died before Aurelius, here I agree that it is a good idea to display him prior to Aurelius. 

* It was suggested to add some indication of co-emperorship for clarity. I in principle think this is a good idea but think it may clutter the graphic a little more than I would like at present and so I'm holding off on implementing that for now. I will think longer on how I could accomplish that elegantly, as distinguishing co-emperorship adds another informative layer to an otherwise clean graphic that should be handled thoughtfully.

* It was noted that 'captivity' is not really a manner of death. This was something I kept from the original dataset specifically for Valerian, as I initially thought that the context of his death in captivity would be important to present, despite the proximate cause of death being unclear. However, I agree that doing this causes unnecessary confusion, and so I have amended Valerian's manner of death to be 'unknown'. This has the benefit of removing an item from the legend which only applied to one individual, which to me does improve the elegance of the graphic.

![Roman Emperors, 27 BCE - 395 CE](emperors.png)
