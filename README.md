## An evaluation on the Viability of a Public Biking System in Logan City Utah

# Dataset
https://www.kaggle.com/datasets/sebastianquirarte/over-9-years-of-real-public-bike-use-data-mibici

# Introduction
The concept of publicly available non-emissive transportation, such as scooters or
bicycles, is not a brand-new concept in civic life. The benefits of such a program existing in a
city include social mobility, reduced carbon emissions into the city’s atmosphere, as well as
reduced road traffic. However, the viability of such solutions within the US has seen only
dubious success; many privately-held services such as Lime scooters have experienced failure
due to a lack of maintenance, failure to mesh with culture in the US, vandalism, and other cost
overhead that is often not accounted for in electric charging costs or user error. These scooters
are a common sight in Logan, UT, but often remain left in the same spot for days or weeks until
moved, and it is usually unclear how they are charged or operated to a layperson, even if they
wanted to use or move it.
An alternative solution has been in practice within the metro area of Guadalajara; the city
government has established over 350 stations where subscribed users can ride a bicycle from
any station to another. Stations are rather densely-packed, with the typical station 2-3 blocks
from others in each direction. Regular users can quickly learn the most convenient stations for
their daily tasks, which could result in increased ease of use and, ultimately, more success as
an emissions-reduction program.

# Goals
Project Description and Motivation:
- Evaluate the viability of government-sponsored public bicycle rentals in metro areas like
Logan or SLC
- Find the most common trip uses for rented bicycles
- Learn about the demographics of rentals and trips within Guadalajara
- Find total yearly cost estimate for government to run
- Find demographics to target (should bikes be on campus first?)
- Are there noticeable differences between densely vs sparsely spaced stations?
- Has bike use increased since implementation in 2014?
- Do bike rush hours work similarly to cars? How do they work and when will rush hours
occur.
- Estimate annual savings for a given demographic (ie., students at USU) for a similar
program in place of their current mode of transportation.
- Which civic features (schools, shopping, worksites) result in increased bicycle use?

# Timeline
Schedule (current april 8th)
Week 1:
- April 12th presentation
- Dataset cleaning and correlations (find other datasets to compare? Logan and SLC
data?)
- Scatter the plots
- Demographics research
Week 2:
- Predictive models (mostly to show what things can be predicted)
- Find useful trends within the demographics research
Week 3:
- April 27th final report due
- Make pretty graphs
- Report findings

# Division of Labor
Division of Responsibilities:
Benson:
- Evaluate the estimated annual cost of program maintenance in Guadalajara, Logan or
SLC.
- Estimate a similar program’s success (usage frequency) in Logan.
- Find expected emissions reductions through use of this program in both Guadalajara
and Logan.
Jensen:
- Find a USU student’s estimated annual cost saving by using a bike-share program in
place of their current mode of transportation.
- Find usage trends within the program used in Guadalajara; who uses the program the
most, and when.
Nathan:
- Research which features of a city (schools, shopping, worksites, busy roads, etc.)
influence bicycle traffic.

# Anticipated Problems
More data in general would be helpful:
- We could also find a dataset of a similar city to Logan or SLC as well as some outside
the US.
- We may need to resort to manual data collection (surveys) for some aspects of this
project, such as finding potential cost savings for USU students.
No maintenance and cost data:
- Viability of these services is heavily based on cost, we could find at least one dataset
that includes maintenance data.
- We could find bike data to find normal maintenance requirements for bikes with different
rental costs.
Location as a prediction target is not easy to handle:
- One option is to target the station code; this results in hundreds of target classes. With
millions of entries available this should not be a problem, except for processing time.
- Another option is to target coordinate location, (X,Y). The problem is that we don’t know
how to handle a tuple as a target.