# Meta-data

## Table of Contents
- [Meta-data](#meta-data)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Some Background Reading for this Document](#some-background-reading-for-this-document)
  - [Priority Variables](#priority-variables)
    - [Structure Layer](#structure-layer)
    - [Survey Layer](#survey-layer)
      - [Actual Survey Meta-Data](#actual-survey-meta-data)
  - [**nest-site or Structure Type**](#nest-site-or-structure-type)
    - [Survey Layer: Long Term](#survey-layer-long-term)
  - [Notes](#notes)

## Introduction
This document outlines what each variable means and the way it should be filled out if it were hypothetically on a data-sheet in front of you — or at least it tries to make a start on this task.

This document was begin in October 2022 and is likely to be constantly updated for quite some time.

---
## Some Background Reading for this Document
The meta-data was written in October 2022, and I am adding to it in November 2022 as I run field-trials.

I have been writing the meta-data with a focus on the information and concepts, rather than getting to a set data-sheet. In fact, it is my goal that this protocol can be entirely knowledge-based rather than infrastructure-based. What I mean is that, given a good knowledge of the concepts, one could do a good job at surveying with nothing but a blank notebook. Data-sheets could definitely help with more detailed recording, but I feel that the crux of what I am tying to achieve is in how the information ties together, rather than in any one variable.

The concept of layers is used in the data-structure of this protocol. Do not worry if mention of that does not make sense on its own: the idea of layers in this protocol needs to be written and explained at some point, not to mentioned trailed and reviewed.

The meta-data is extremely incomplete. The first section ('Priority Variables') is the things that I thought might be important to get squared up first. It is notable that these do not include variables like nest-box material, or tree-hollow height. Instead, I believe the foundations are in being able to identify each nest-site properly, and knowing when it is time to check on it for occupancy. I hope that more sophisticated measurements can be built on the foundations here.

Things in square brackets are comments from me to you.

~ Chris

---
## Priority Variables
The guiding question behind this section is "What cannot be easily reconstructed if it is not recorded fairly soon?" An example is the date of installation. That is easy to remember if it was yesterday, but harder if it was three weeks ago and during a holiday period. Another is identity: you saw a lorikeet here four weeks ago, but which of these ten identical boxes was it in? One can usually remember something like that, but it is bad practice to leave it unrecorded. Contrastingly, the height of a nest-box is stable, unless an action is taken to change it, or it falls down: such changes are a much more distinct event than the passage of time.

~ Chris

---
### Structure Layer
**Nest-site Structure Name**<br>
This is recommended because it helps to organise and enhance the other variables.

Syntax:<br>
_Postcode.Site.*TreeName.+NestSiteName-Type_

- Postcode and site may be interchangeable, if the site is a large reserve.
- TreeName is not always needed. It is actually the name for any structure that might contain multiple nest-sites. Therefore, it could be a tree, or something like a building. This is prefixed by an asterisk.
- NestSiteName is the name for the nest site. This is prefixed by a plus-sign, and appended by the Type of the structure.
- The Type is a code that indicates the type of the structure. 'TH' mean hollow, 'NB' means nest-box, and 'AS' means artificial structure, including buildings; and there will be other codes. 
- The NestSiteName should be unique: the Type does not serve to make it unique - that is only to add some clarity
- TreeName should also aim to be unique.
- It seems likely that if people are working independently, there will be double-up on NestSiteName. This is the reason why I initially thought of this address-like naming system. So, while one should try to keep names unique, the only really critical point is that there are no two identical 'addresses'.
- For all of these names, I use Camel Case. This is where all words start with a capital, and there are no spaces. Therefore, 'Blue Gum Track' becomes 'BlueGumTrack', or if you choose to use abbreviations in a name you might say 'BGTrack'.
- Numbers are not necessary but they are useful and there is no reason not to use them aside from personal preference for memorable, descriptive names.

A surveyor may choose to record the site at the top of their survey-notes, and then one need only write: <br>
_— +NestSiteName_

**Location**<br>
- GPS (Global Positioning System) coordinates — Latitude and Longitude [1] to _six decimal places_. The coordiante system needs clarification. What-three-words may be used as an add-on but not a replacement. If coordinates are unavailable, two things are necessary: a written description to find location, and either a photo or sufficient sketch (see 'Identity' variable).

**Identity**<br>
- Identifying photos of nest-site structure, with surrounding context so that similar strucutres can be distinguished from each other, and the nest-site can be found easily in the environemtn.
- Other photos at discretion. This also relates to condition and signs of wear.
- If photos are unavailable, a sufficient description and sketch must be included. The test for sufficiency is replicability: people familair with the protocol but otherwise niave to the nest-sites must be able to find them.

**Date of First Observation**<br>
- Given to the day. [2]

This is the entry-point of the observations into the protocol. The default is that this is the point where observations are done in the context of the protocol. Past observations are outlined, with reference to past observations, in the 'Observation History' variable. In the case where one is sure that the observations constitute a clear knowledge of occupancy, these may be entered into the protocol, with appropriate explanatory notes in the 'Observation History' variable.

**Observation History**<br>
[Incomplete: but see 'Date of First Observation' variable]

**Date of Installation**<br>
- The date that the structure came into existence in it's current form and locale. 
- Given to whatever accuracy is possible.
- This variable may be assimilated into 'Structure History'
 
[The mechanism for deciding when a strucutre 'comes into existence' is partly explored in the essay called 'Broad Thoughts and Principles'. However, this will eventually be discussed in all the required detail in it's own appendix.]

**Structre History**<br>
- Link to past strucutres
- Record of any interesting fixes, minor improvements, donwn-time, etc.

---
### Survey Layer

Surveying is where the valuable observations are, informing us about the ecological interactions involving the nest-sites. In many ways, the protocol is just a framework for making sure that observations are organised and can be leveraged as much as possible.

Even though occupancy and breeding activity are things that one might be most interested in, such variables can be abstract. I have written elsewhere on the idea that something like occupation is a _summary_ of observations. Without emphasising the importance of the observations, the confidence of all the other information in the protocol is undermined.

Everything should be tied back to observations, if possible. It seems likely that there will be a data-sheet for a nest-site, and that this will involve occupancy and breeding status, and possibly things like wear; but I want to make sure that such information is empowered by the ability to simply record observations. The way observations came about is also of paramount importance, and relates strongly to the immense task of presence/absence surveying. An observation-powered system like the Australian nest record scheme is good because it gets you to note what you see and then summarise things like breeding success. But when doing a presence/absence survey, there is another layer. The effort invested has to be noted as well, or else we are left with the possibility of a huge bias towards _consipicuosly_ occupied nest-sites, and even risk not being able to retell absence of occupation at all. The way observations are over the long-term is also important. Without checking on nest-sites at a certain frequency, important parts of the breeding season may be lost.

I want to propose some elements for this protocol that, hopefully, will inoculate the survey efforts with the rigour I seek. 

Firstly, I suggest that surveys are done in a way where observations are systematic, embrace presence/absence data, and are not confined to any sort of summary notes about occupation. For example, if I am doing a walk-through survey, I should do the following:
- Note that the survey is a walk-through survey,
- Note the date, and start and end time,
- note each structure that I am able to observe,
- Even if I know a hollow to be occupied, I should still write 'no activity' if I do not see any,
- If I do not check some nest-sites, I should note that there are un-checked sites at the location or area, thus indicating that only the ones I have actually written down were part of my walk-through,
- I should place observations under the appropriate structure (that is, tree or nest-site), but I may also make observations that are more general, such as the presence of interesting birds or competition in the environment; such things can help guide my efforts, but might be missed if I focus _soley_ on satisfying a pre-set data criteria for occupancy or breeding for specific nest-sites.

Secondly, I suggest that there is a mechanism for coordinating a monitoring schedule. This could take the form of a list of locations or field-sites or post-code groups, and the observation status of each on for each month in the calendar year. There can be a similar list for nest sites within each area, with a check-box for each month. So, coming up to a partly-free weekend, one might do something like this:
- Check their own records for each field-site they are interested in, thus seeing which ones have not been done this month,
- Cross-check the online repository to see if anyone else has done them (even if they have, one might still choose to go out, either improving on method, or simply increasing resolution),
- Once at the location (or before), once can look at the list of nest-sites and see which ones have not been done this month — these are the ones that need to be checked
- One can then conduct a survey.
- At the end, they can add information about occupancy status and so on to the data for the nest-sites.
- They can then tick the nest-sites that have been checked. Some might need more work — it can be harder to do natural hollows than nest-boxes, for instance (that said, if a procedure has been followed, it is best to not second guess that! And any concerns can be shared among the community.)
- Interesting signs of use can be noted and posted on the repository, creating a flag for the next surveyor.

In suggesting the above, I am trying to create a sort of 'research-grade' status (C.f. iNaturalist) for each nest-site for each time-period. I am wary that it will suffer from too much complexity, or fall into the trap being too demanding. So, I am eager for new ideas, and especially suggestions for how people can be empowered to share amongst the community which places that need more attention.

**Survey Type Definition**<br>
Each survey has a few basic bits of infortmation, such as site, data, and time. The following are some ideas for the types of surveys:
- **Walk-through**: A minimal survey effort based on being present more than anything else. List nest-sites observed.
- **Watch**: A concerted effort to watch one or more nest-sites or structures (which are listed) for a little longer. Start and end time noted. May be nested within other survey types. Best done at dusk or dawn.
- **Duck/Dawn-watch**: A specific variation of a 'watch', where nest-sites are surveyed for at least 40 mins, either just before dark or just after dawn.
- **Area survey**: > 90 mins spent in an area. There would be guidelines to how large an area can be tackled. Best done after dawn or before dusk.
- **Opportunistic**: This is when a discovery comes to you, and you are not even doing enough of a survey to call it a walk-through.
- **Familiarity**: This is when you are so familiar with a site that it is impossible to keep track of every single observation. A common example is sparrows under an eve. You might record major breeding events, but otherwise not over-do it.

Something to note is that a walk-through is not a bad thing at all. It is the bigger-picture that counts. If one did a walk-through every second day just before dusk, they would probably gain more information on the site than any other method! Also, some areas may only need a short survey. For instance, if one has a pole-mounted camera, then they may not need much survey-time. I therefore suggest that a 'nest-site check type' can be added to each observation. This way, records will qucikly show exactly how rigorously each nest-site was observed.

These surveys entail a presence/absence approach, and this is why the structures have to be listed in some way. However, it is also a part of the protocol that one can use their natural history skills to hone survey priorities. Therefore, there needs to be a way of recording site-walk surveys without listing structures, but instead focusing on bird-life and opportunistic observations.

Example:

>— — — Long — — — — — 23/10, 7.30 am — _
>- 5066.HazelwoodPark — 
>   -  +ThinRG-H &emsp; Lorikeet: pair attend nest; Fledgling Down.
>   -  *BigCreek.+Elbow1-H &emsp; No signs. [this tree name is given because Elbow is a common desciptive name]
>   -  +TallPossum-H &emsp; No signs [of fresh fur around entrance]
>   -  Yellow Tail fly-over; no signs of descent
>   -  Large fungus still present at BranchDrop Tree, IMG_2734  [here the surveyor has done something novel, and added a tree that is not a hollow at all, but a _proto structure_ ][3]
>
><br>
>
>— — — Dusk Check — — — 23/10, 7.30 pm - 8.10 pm
>- 5055.HazelwoodPark.*TallPossum.~~+TallPossum~~
>   - +MicroBatSpout1-H       Micro-bat emerged.  [this is a new chance discovery: that is the watch was changed from the holllow to the whole tree]
>   - +TallPossum-H   Possum with joey on back emerged. Joey now 1/2 length of mother.

#### Actual Survey Meta-Data

The way surveys are being coordinated is discussed above. However, one needs to know what to write on a blank piece of paper. These variable are the ones you write.

**Survey Type** <br>
This is the survey type as outlined above. Observations are nested in survey type.

****

**nest-site or Structure Type**
---
### Survey Layer: Long Term

This layer is iscussed above, too. It is abstract because its time dimension is longer than the actual survey efforts. The survey effort it describes is the frequency and consistency of effort across long time periods, such as a season.

Each survey effort results in a type of check on a nest-site and the date. If the goal is to survey a certain hollow monthly, then the Long term layer might look something like this:

>- 5066.HazelwoodPark — Survey Monthly through main breeding (Aug-Dec)
Aug: Y , Sep: Y , Oct: Y , Nov: &emsp; , Dec:&emsp;
>
>- 5066.HazelwoodPark — 
>   -  +ThinRG-H      Aug: Y , Sep: Y , Oct: Y , Nov: &emsp; , Dec:&emsp;
>   -  *BigCreek.+Elbow1-H       Aug: Y , Sep: Y , Oct: Y , Nov: &emsp; , Dec:&emsp;
>   -  +TallPossum-H      Aug: Y , Sep: Y , Oct: Y , Nov: &emsp; , Dec:&emsp;
>    -  +MicroBatSpout1-H      N/A —  Oct: Y , Nov: &emsp; , Dec:&emsp;

This sort of thing is very rigorous and I am still exploring how the best way to coordinate these long-term efforts are. The question is: what tools are necessary to make it run smoothly? I am used to cross-indexing notes by hand but other might find it awkward.

---

---
## Notes
[1] I prefer lattitude and longitude outside of scientific survey teams, because on many occassions where Eastings and Northings have been used there have been translation issues. I have even had to deal with botched gps data because of the conversion betwen these two, and that mistake originated from within an institution.

[2] At no point anywhere in the protocol can the date be written in numbers and include the month before the day.

[3] The ability to place auxillary notes that pertain to tree-hollows in the protocol is one of my goals.