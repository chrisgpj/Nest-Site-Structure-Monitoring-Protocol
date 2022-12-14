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
## Nest-Site Structure Layer
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

## The Use of Nest-Site Structures and Breeding Success
This layer is combined with the Nest-Site Structure Layer in the physical record-keeping, but it is a separate layer in its own right in the data.

**Use of Nest-Site Structure and Breeding Success**<br>
This variable is organised by the check-period, which is usually monthly or twice-monthly. The next piece of information is the species, if use is noted; then comes detail of the use, including breeding activity; and then the date of observation. The date of observation may be multiple; this helps to link conclusions to the survey layer. Multiple entries may be made for a check-period if a change in activity is recorded.

[Compatibility with other schemes is still being clarified.]

Syntax:<br>
_Period: Species: Activity, dates._

Example:
> Early Nov: RB Lori: Occupied, P. Incubation, 13/11/22, 15/11/22 ["P." stands for "Probable" and is a standard approach in this protocol]
> Late Nov: RB Lori: Nestlings, 17/11/22
> Early Dec: RB Lori: Nestlings, x3, 10/12/22
> Late Dec: RB Lori: Successful Fledlglings, x2, 20/12/22, 21/12/22

The 'Activity' uses standard language that tries to be concise. With birds the language is for breeding; with other animals, fewer observations are easily made in this regard, so I am still working on that. The following is for birds
- Occupying: Animal seen in Nest-Site Structure
- Pair Attend: A pair is attending the hollow. This is usually linked to breeding activity.
- Nest Building: Animal seen building a nest in the structure, or gathering material and entering structure.
- Family Attend: specify with xNUMBER to indicate the number of individuals of each identifiable sex and age. This may indicate recently successful breeding.
- P. Incubation: The stage of breeding where the female is sitting on eggs or very young nestlings and being fed by the male.
- Nestlings: Nestling present and being fed by parents (indicate number with xNUMBER).
- Fledglings: Young birds that have come into plumage (indicate number with xNUMBER).
- Successful Fledglings: Fledglings that are flying about and can be considered juveniles (indicate number with xNUMBER).

It is perfectly fine to make various notes outside of thing language. One might do so in order to clarify or provide reasoning for some number. It is simply encouraged that such notes act as a _supplement_ to the core language and numbers.


---
## Survey Layer

### Preliminary Notes

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

### Survey Type Definition<br>
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

### Actual Observation Meta-Data

Now that the survey type has been established, you make observations within that:
- **Structure ID**
- **Activity**: Refer to appendix for all signs of activity, including wear and other indirect signs. If there is no activity, then write the phrase 'No activity'.
- **Confirmation Note**: If the observations made lead to confirmation of the site being used, then write in square brackets '[Confirm Use]' or '[Not Confirmed]'. This is discussed alongside the signs of activity in the appendix.
- **Survey type if nested inside a survey**: For instance, a walk-through may involve some focus on a particular nest-site:
    *BigCreek.+Elbow1-H: Watch, 7.10 pm - 7.20 pm: No Activity.

---
## Schedule Layer

This layer is abstract because its time dimension is longer than the actual survey efforts. The survey effort it describes is the frequency and consistency of effort across long time periods, such as a season.

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
## Appendix A: Structure Layer: Nest-Site Measurements and Characteristics: data for Tree Hollows

These variables are the characteristics and measurements for tree-hollows.

[I have been thinking about the problem of measurements changing due to the occupant. I am uncomfortable about this, because how does one assess an unused hollow? I may have to think about some things being more general, and others dependent on use.]

### Hollow Size
The Hollow size refers to the _largest_ entrance.

If the surveyor is not sure, prefix the note with a question mark in square brackets.

The categories are:
- Small = 
- medium =
- large = 
- huge = 

[These are under review]

If possible, surveyors are encouraged to measure to 1 cm resolution. Even having a few nest-sites with more detailed measurements around the place would help people gain a sense of reference.

For an accurate measure, two models of entrance size are required. One is needed for roughly circular openings. These can be modelled by the shortest widths (the constraining distance), and then the width perpendicular to this; if the entrance is round you can't go wrong. The second model is needed for fissure-like entrances. The smallest width is not constraining for these, so instead one takes the widest part of the fissure and draws an imaginary ovular entrance over it. The shortest width of that imaginary entrance is the constraining width; the second measurement is the length of the entire fissure. This is how I would go about it but I haven't checked other methods for a while

[the above needs consultation]

### Height of Hollow

Measured to 0.5 m resolution. Height pertains to the entrance of the hollow (recall that entrance is the largest entrance).

This variable could be affected by multiple entrances — but the main question is what to do when an occupant is using an entrance that is not the largest one.

The height is given for the lowest entrance of each size class, but only when the smaller entrance is below a bigger one. If there were many entrances, but the biggest one was the lowest, then only that entrance height would be needed.

### Number of entrances

Number of entrances for each size class is given. If many, use >3.

### Draughtiness

This reflects the openings in the hollow that do not feasibly act as entrances. It is either Not significant, Moderate, or Severe. This pertains to the structure of the whole of the branch that appears to be where the hollow is located. Most hollows that people observe are 'Not significant'.

### Dead or alive.

This pertains to the whole of the branch that appears to be where the hollow is located. If the branch is alive: Alive, if the branch is dead: Dead, if the branch is partly dead, then go by the condition at one metre down from the largest hollow entrance.

### Branch Order

This pertains to the branch that contains the entrance to the hollow.
- 0 = ground-level opening to trunk, lignotuber, or unspecified cavity created by tree
- 1 = The primary trunk
- 2 = secondary branch
- etc.

This variable is informed by split trunks in the tree varaibles

### Trim (hollow)

[?]

## Appendix B: Structure Layer: Nest-Site Measurements and Characteristics: data for Trees

Some variables in this appendix are informed by some ideas about mallee trees and the diversity of other tree-forms, and their significance for tree hollow ontogeny. These ideas have been written about elsewhere.

### Species

To most detailed taxonomic level possible.

### Height of Tree

Measured to 0.5 m resolution; 1 m resolution above 3 m

### Diameter at Breast Height

Estimated to 0.1 m resolution. If the trunks are split (see below), measure the largest one.

### Trunk split

This refers to the height above the ground at which the primary trunk splits into secondary branches.

- Mallee = mallee habit
- Very Low = <0.5 m
- Low = <1.5 m
- High = >1.5 m

### Split Trunk Significance

A Yes/No answer to the question: Are any of the trunks of similar size to the largess trunk?

### Trunk Sheer

A Yes/No answer to the question: has a major trunk or a major secondary branch collapsed or sheered off the tree?

### Form

- 1: Live Tree
- 2: Live Tree with stag effect. This can be through die-back of the canopy, or through branch-drop which depletes the canopy coverage to the point where the tree looks stagged.
- 3: Dead
- 4: Advanced Dead Structure[4]

See photos.

### Continuous Vegetation

Do the tree canopies seem connected enough for a ring-tail possum to move continuously to the tree? Yes/No.

If one has to stretch the imagination, err to `No'.

### Trim (tree)

[?]

### Fire damage and epicormic growth

Write whichever apply, separated by commas. `Scar' overrides 'Scorched'.

- Scar: There is a fire scar OR there is internal charcoal
- Scorched: there evidence of past burning
- Epicormic: The tree seems to be resprouting epicormically, or has done recently enough that this is still detectable.

---
## Notes
[1] I prefer lattitude and longitude outside of scientific survey teams, because on many occasions where Eastings and Northings have been used, there have been translation issues. I have even had to deal with botched GPS data because of the conversion between these two, and that mistake originated from within an institution.

Private locations do not need to be disclosed, and these may need to use some other identifying name scheme as well.

[2] At no point anywhere in the protocol can the date be written in numbers and include the month before the day.

[3] The ability to records observations about tree hollow ontogeny is one of my goals for this protocol.

[4] I have transferred the complexity seen in the work on the form in _Eucalyptus regnans_ to describing the mallee habits. This is more appropriate for South Australia. However, it will be seen that the system here still matches the 'groups' of tree forms used in that work; it is just that some of the finer resolution is lost. I am adamant that 'scrags' can be described, and that is why I have included the 'Advanced Dead Structure'. For the importance of Scrags, see the Broad Thoughts and Principles notes.