# Meta-data

## Introduction
This document
- Introduces the main components of the recording system for the protocol, and
-  outlines what each variable means and the way it should be filled out if it were hypothetically on a data-sheet in front of you — or at least it tries to make a start on this task.

It does not yet discuss the reasoning or prioritisation of variables.

The basis for the protocol is drafted in an essay called ``Broad Thoughts and Principles''.

The meta-data was written in October 2022, and I am adding to it in November 2022 as I run field-trials.

I have been writing the meta-data with a focus on the information and concepts, rather than getting to a set data-sheet. In fact, it is my goal that this protocol can be entirely knowledge-based rather than infrastructure-based. What I mean is that, given a good knowledge of the concepts, one could do a good job at surveying with nothing but a blank notebook. Data-sheets could definitely help with more detailed recording, but I feel that the crux of what I am tying to achieve is in how the information ties together, rather than in any one variable.

The meta-data is extremely incomplete. The first things I added were those I considered to be priority variables. One definition of these is ``the things that cannot be easily reconstructed if not recorded fairly soon''. It is notable that these do not include variables like nest-box material, or tree-hollow height. Instead, I believe the foundations are in being able to identify each nest-site properly, and knowing when it is time to check on it for occupancy. The approach is that good observation is the foundation upon which complex information is built. So, to progress, we must first be clear when and how things are observed. I hope that more sophisticated measurements can be built on the foundations here.

Throughout this document, when I say 'nest-site', I usually mean 'nest-site structure'. When I say 'structure' I may be referring the nest-site structures, or to meta-structures such as trees.

Things in square brackets are comments from me to you.

~ Chris

## Main Components of the Protocol
This protocol has a few different recording layers. For example, surveys of bird activity are a different layer to the characteristics of a tree-hollow. The layers came about from contemplating the different spatial and temporal scales of observations. Tree-hollows are fairly stable over time, with some structures being used by different species over the years. Bird activity, however, is more dynamic and changes from moment-to-moment, meaning that observations are only accurate for a small time-frame. Splitting up recording into layers helps in navigating the characteristics of different observations. I have chosen this approach because I want the protocol to be flexible and modular. The layers can be thought of as the titles to pages that one might keep in notebook.

In this section, each layer is discussed with extreme brevity, and the way they are connected is discussed. In the next section, some variables in each layer are specified. Where there are many options for recording, you may be directed to an appendix.

### Nest-Site Structure
- Records information about individual nest-site structures
- Includes data on the nest-site itself, the record keeping history, and the use of the nest-site in each recording period.
- Each record of nest-site contains some base-line information, but can be extended to include records of use, as well as more detailed measurement. If there is lots of use, the record may become very long, and need to be linked across pages.
- The structure is only defined as a new one when some significant event takes place, such as a change in the branch order or a hollow.

### Meta-Structures and Proto-Structures
- This layer pertains to the structures that the individual nest-sites are nested within. An example is a tree.
- It allows observations on a structure that has several nest sites. For instance, a fire might affect a tree, and it may be best to record that information for the tree if none of the nest-sites appear directly altered.
- Proto-structures can also be noted here (although there is no reason why some might not be in the nest-site structure layer, as well). An example of a proto-structure is a tree that has been infected with fungus.

### Sites
- This layer pertain to a more general location. It allows observations on habitat, such as fire, to be recorded.
- It is also an important concept for recording some types of activity that cannot be traced to a particular nest-site. An example is an abundance of possums at night in a park.

### Survey
- This layer is for recording observations of fauna in real-time. It contains surveys specified in time, place, and methodology. The observations within each survey reference a nest-site structure, a meta-structure, or a site.
- Surveys are the basis for all understanding of nest-site use. They are the evidence upon which the knowledge of occupancy or breeding activity is founded. Therefore, this layer exists to give observations the emphasis that they use. This is in contrast to entering conclusions about occupancy into the data straight away.

### Schedule
- The schedule is an are abstract layers that help to consider survey quality in the long-term.
- The index contains a list of the structures within each site, and a list of survey efforts. 
- There may be some degree of cross-referencing in the layers themselves, depending on how they are being kept.

---
## Structure Layer
**Nest-site Structure Name**<br>
This is variable identifies nest-sites in a structured way that encourages customised names, but reduces the chance of double-up, and allows nest-sites to be grouped by location.

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
- Numbers are not necessary but they are useful and there is no reason not to use them aside from personal preference for descriptive names.

A surveyor may choose to record the site at the top of their survey-notes, and then one need only write: <br>
_— +NestSiteName_

Nest-Site Types:
- TH = Tree Hollow
- NB = Nest-Box
- AS = Artificial Structures that are not nest-boxes
- GF = Geological Feature
- BW = Burrow. [It can also mean0` Barrow Wight'. Please see the notes of Barrow Wights.]

A Type can also be appended to the meta-structure at any point that is appropriate:
- T = Tree
- AS = Artificial Structure
- GF = Geological Feature
- E = Earth

Some features, such as burrows, are not nest-site structures of interest in the same way that tree-hollows are, but they are included in the context of some species using these different kinds of structure.

Site Name:
- Often a property name. In this case it is usually nested within post-code
- If the site is a large reserve, then the post-code may come afterwards. This indicates that the site may span multiple post-codes, and that the post code is given only to eliminate confusion with other locations of the same name. Recall that the idea is to prevent replicas of `addresses' and to be descriptive — there is actually a bit of room to work within that.
- A secondary site name may be introduced if it is felt useful E.g. `NorthEast'. The asterisk and the plus-sign exist to clarify when the name is referring to a specific structure, allowing people to communicate accurately without needing a data-field on their sheet.

**Location**<br>
- GPS (Global Positioning System) coordinates — Latitude and Longitude [1] to _six decimal places_. The coordinate system needs clarification. What-three-words may be used as an add-on but not a replacement. If coordinates are unavailable, two things are necessary: a written description to find location, and either a photo or sufficient sketch (see 'Identity' variable).

**Identity / ID Image**<br>
- Identifying photos of nest-site structure, with surrounding context so that similar structures can be distinguished from each other, and the nest-site can be found easily in the environment.
- Other photos at discretion. This also relates to condition and signs of wear.
- The Identity photo (which may also be called the 'ID Image') is preferably taken from the north, because this way the sun is never in front of the camera in the southern-hemisphere.
- If photos are unavailable, a sufficient description and sketch must be included. The test for sufficiency is replicability: people familiar with the protocol but otherwise naive to the nest-sites must be able to find them.

**Date of First Observation**<br>
- Given to the day. [2]

This is the entry-point of the observations into the protocol. The default is that this is the point where observations are being made with the guidance of the protocol. Past observations are outlined in the 'Observation History' variable. In the case where one is sure that the observations constitute a clear knowledge of occupancy, these may be entered into the protocol, with appropriate explanatory notes in the 'Observation History' variable.

**Observation History**<br>
[Incomplete: but see 'Date of First Observation' variable]

**Date of Installation**<br>
- The date that the structure came into existence in its current form and locale. 
- Given to whatever accuracy is possible.

[This variable may be assimilated into 'Structure History']
 
[The mechanism for deciding when a structure 'comes into existence' is partly explored in the essay called 'Broad Thoughts and Principles'. However, this will eventually be discussed in all the required detail in its own appendix.]

**Structure History**<br>
- Link to past structures
- Record of any interesting fixes, minor improvements, down-time, etc.

**Nest-Site Measurements and Characteristics**<br>
This is a group of variables, the makeup of which is determined by what type of structure the nest-site is. The list of variables to cover each possible structure is so large that I am giving it in an appendix. 

---
## Survey Layer

Surveying is where the valuable observations are, informing us about the ecological interactions involving the nest-sites. In many ways, the protocol is just a framework for making sure that observations are organised and can be leveraged as much as possible.

Even though occupancy and breeding activity are things that one might be most interested in, such variables can be abstract. I have written elsewhere on the idea that something like occupation is a _summary_ of observations. Without emphasising the importance of the observations, the confidence of all the other information in the protocol is undermined.

Everything should be tied back to observations, if possible. It seems likely that there will be a data-sheet for a nest-site, and that this will involve occupancy and breeding status, and possibly things like wear; but I want to make sure that such information is empowered by the ability to simply record observations. The way observations came about is also of paramount importance, and relates strongly to the immense task of presence/absence surveying. An observation-powered system like the Australian nest record scheme is good because it gets you to note what you see and then summarise things like breeding success. But when doing a presence/absence survey, there is another layer. The effort invested has to be noted as well, or else we are left with the possibility of a huge bias towards _conspicuously_ occupied nest-sites, and even risk not being able to retell absence of occupation at all. The way observations are over the long-term is also important. Without checking on nest-sites at a certain frequency, important parts of breeding activity may be lost.

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

## Survey Type Definition<br>
Each survey has a few basic bits of infortmation, such as site, data, and time. The following are some ideas for the types of surveys:
- **Walk-through**: A minimal survey effort based on being present more than anything else. List nest-sites observed.
- **Watch**: A concerted effort to watch one or more nest-sites or structures (which are listed) for a little longer. Start and end time noted. May be nested within other survey types. Best done at dusk or dawn.
- [I suspect that the 20 min per 2 hectare method is best expressed as a watch. So, a guideline for that type of survey is that watches are at least 20 mins long.]
- **Duck/Dawn-watch**: A specific variation of a 'watch', where nest-sites are surveyed for at least 40 mins, either just before dark or just after dawn.
- **Area survey**: > 90 mins spent in an area. There would be guidelines to how large an area can be tackled. Best done after dawn or before dusk.
- **Opportunistic**: This is when a discovery comes to you, and you are not even doing enough of a survey to call it a walk-through.
- **Familiarity**: This is when you are so familiar with a site that it is impossible to keep track of every single observation. A common example is sparrows under an eve. You might record major breeding events, but otherwise not over-do it.

Something to note is that a small survey like a walk-through is not a bad thing at all. It is the bigger-picture that counts. If one did a walk-through every second day just before dusk, they would probably gain more information on the site than any other method! Also, some areas may only need a short survey. For instance, if one has a pole-mounted camera, then they may not need much survey-time. I suggest that a 'nest-site check type' can be added to each observation. This way, records will quickly show exactly how rigorously each nest-site was observed.

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
>— — — Dusk watch — — — 23/10, 7.30 pm - 8.10 pm
>- 5055.HazelwoodPark.*TallPossum.~~+TallPossum~~
>   - +MicroBatSpout1-H       Micro-bat emerged.  [this is a new chance discovery: that is the watch was changed from the holllow to the whole tree]
>   - +TallPossum-H   Possum with joey on back emerged. Joey now 1/2 length of mother.

### Actual Survey Meta-Data

The way surveys are being coordinated is discussed above. However, one needs to know what to write on a blank piece of paper. These variables are the ones you write:

- **Survey Type** <br>
This is the survey type as outlined above. Observations are nested in survey type.
- **Date**
- **Start Time and End Time**
- **Location**

### Actual ObservatioN Meta-Data

Now that the survey type has been established, you make observations within that:
- **Structure ID**
- **Activity**: Refer to appendix for all signs of activity, including wear and other indirect signs. If there is no activity, then write the phrase 'No activity'.
- **Confirmation Note**: If the observations made lead to confirmation of the site being used, then write in square brackets '[Confirm Use]' or '[Not Confirmed]'. This is discussed alongside the signs of activity in the appendix.
- **Survey type if nested inside a survey**: For instance, a walk-through may involve some focus on a particular nest-site:
    *BigCreek.+Elbow1-H: Watch, 7.10 pm - 7.20 pm: No Activity.

---
### Schedule Layer

This layer is discussed above, too. It is abstract because its time dimension is longer than the actual survey efforts. The survey effort it describes is the frequency and consistency of effort across long time periods, such as a season.

Each survey effort results in a type of check on a nest-site and the date. If the goal is to survey a certain hollow monthly, then the Long term layer might look something like this:

>- 5066.HazelwoodPark — Survey Monthly through main breeding (Aug-Dec)
Aug: Y , Sep: Y , Oct: Y , Nov: &emsp; , Dec:&emsp;
>
>- 5066.HazelwoodPark — 
>   -  +ThinRG-H      Aug: Y , Sep: Y , Oct: Y , Nov: &emsp; , Dec:&emsp;
>   -  *BigCreek.+Elbow1-H       Aug: Y , Sep: Y , Oct: Y , Nov: &emsp; , Dec:&emsp;
>   -  +TallPossum-H      Aug: Y , Sep: Y , Oct: Y , Nov: &emsp; , Dec:&emsp;
>    -  +MicroBatSpout1-H      N/A —  Oct: Y , Nov: &emsp; , Dec:&emsp;

This sort of thing is very rigorous, and I am still exploring how the best way to coordinate these long-term efforts are. The question is: what tools are necessary to make it run smoothly? I am used to cross-indexing notes by hand, but others might find it awkward.

---
## Appendix A: Structure Layer data for Tree Hollows

These variables are the characteristics and measurements for tree-hollows.

### Hollow Size
If the surveyor is not sure, prefix the note with a question mark in square brackets.
- Small = 
- medium =
- large = 
- huge = 
  
### Height


---
## Notes
[1] I prefer lattitude and longitude outside of scientific survey teams, because on many occasions where Eastings and Northings have been used, there have been translation issues. I have even had to deal with botched GPS data because of the conversion between these two, and that mistake originated from within an institution.

[2] At no point anywhere in the protocol can the date be written in numbers and include the month before the day.

[3] The ability to place auxiliary notes that pertain to tree-hollows in the protocol is one of my goals.