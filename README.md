# Hooman

The attribution fairness system mainly for indie dev projects


## Premises

Every hooman hour spent on a project is equaly valued.

The company has to be allowed to make progress.

Transparency is the key.


## The Rules

### Project Proposal

The system is a per-project agreement.

Any team member can pitch a project before all other members. 

A project gets selected to go in development based on various factors such as how many team members are interested in working on it, what are company directions, market response, etc. 

Team member who presented the project becomes the project's producer, unless he/she decides to appoint someone else interested in the role.

Producer should get the team together.

Producer can only be company employee. If the producer leaves the company at any point in time, the company shall appoint a new producer (or shelve the project).

The company's share in total project's income has to be already determined and proposed at that point. (eg. 5%)


### Development Sprint (SCRUM Terminology)

Per each sprint producer gathers the team members needed for that phase of development and tasks which need to be done. This may or may not include appointing a project manager as a team memeber.

Team members can be internal (company employees), external contracted (payed for the work by the company), or external participating (not payed but investing their work into the project).

Sprints should be two or three weeks long.

Internal and contracted team members who join for the sprint are then assigned by the company to that project exclusively and their expense is considered company investment.

At the end of the sprint (after Sprint Review) all members vote on relative member contribution for the sprint and the Attribution Formula is solved. This excludes contracted external members.


### Attribution Formula

__p__ - attribution vector for the sprint (one component for each team member participating in the sprint)
__A__ - votes matrix (each column is a vote vector cast by one team member, vote vector components sum up to one)

__p__ = __A__ * __p__


The formula is obviously recursive and needs to be solved iteratively. Attributions are then normalized so that their sum equals one and scaled by the number of work days in the Sprint. 

Attribution values are stored in plain text format (eg. csv) and stored in p2p repository (eg. git) accessible to all team members.


### Revenue Shares Before Return Of Investment (ROI)

The company is assigned share of revenue with respect to percentage agreed to at the begining of the project (eg. 5%).

External participating developers are assigned credits for their share of revenue.

The rest of the revenue is considered as Return of Investment for the company's expenses until the investment is payed off.


### Revenue Shares After ROI

The company is assigned share of revenue with respect to percentage agreed to at the begining of the project (eg. 5%).

External participating developers are assigned credits for their share of revenue.

Internal developers are assigned their respective share of the revenue.


### Revenue Payment

External prticipating developers are payed off according to agreement or contract made between the company and the developer.

Internal developers get their share payed off as part of biannual gross salary correction to the closest possible approximation / projection for the period, so that the credit balance at the next salary correction is as close to zero as possible. The revenue projection / estimation used must be the same used for all internal developers.

If an internal developer should decide to leave the company, the remaining share from that point on shall be payed off as to an external participating developer.

All members of the project shall at any point in time be granted the access to all information regarding attribution, credits assigned, revenue, and expenses of the project.


