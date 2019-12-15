# Hooman

Humane attribution and fairness system

(primarily for indie dev projects)


## Principles

Every hooman hour spent on a project must be equaly valued.

The company has to be allowed to make progress and/to accomodate infrastructure.

Transparency is the key.


## The Rules

### Project Proposal

The system is a per-project agreement.

Any team member can pitch a project. 

A project gets selected to go into development phase based on various factors such as how many team members are interested in working on it, the company policy, market response, etc. 

Team member who presented the project becomes the project's producer, unless he/she decides to appoint someone else interested in the role.

Producer must get the team together.

The company's share in total project's revenue has to be already determined and proposed at that point. (eg. 5%)

Note: The company needs to have legal ownership of the project to be able to provide all resources needed for production and to protect the shares of all shareholders.


### Development Sprint (SCRUM Terminology)

Sprints should be two or three weeks long.

Each sprint the producer gathers team members needed for that phase of development, i.e. for the tasks that need to be done. This may or may not include appointing a project manager as a team memeber.

Team members can be internal (company employees), external contracted (payed for the work by the company), or external participating (not payed by the company but rather investing their own work into the project).

Internal and contracted team members who join for the sprint are then assigned by the company to that project exclusively and their gross expense is considered a company investment.

At the end of the sprint (after Sprint Review) all members vote on relative member contribution for the sprint and the Attribution Formula is solved. This excludes contracted external members.


Note #1: All assignments must have the consent of the company obviously.

Note #2: This process continues into maintenance and production so the relative developer attributions are expected to fall. (call center example; develop smarter)


### Attribution Formula

__p__ - attribution vector for the sprint (one component for each team member participating in the sprint)
__A__ - votes matrix (each column is a vote vector cast by one team member, vote vector components sum up to one)

__p__ = __A__ * __p__


The formula is obviously recursive and needs to be solved iteratively. Attributions are then normalized so that their sum equals one and are scaled by the number of work days in the Sprint. 

Attribution values are stored as plain text (eg. csv) in a p2p repository (eg. git) which is made accessible to all team members.


### Revenue Shares

The company is assigned a share of revenue with respect to percentage agreed to at the begining of the project (eg. 5%).

External participating developers are assigned credits for their share of revenue.


### Revenue Shares Before ROI (Return of Investment) per Developer

Respective share of revenue for each internal developer is assigned to the company until the company has been compensated for the developer.


### Revenue Shares After ROI per Developer

Internal developers are assigned their respective share of the revenue after the ROI.

All shares are calculated daily to accomodate changing attribution as a response to maintenance or active development.


### Revenue Payment Method

External prticipating developers are payed off according to agreement or contract made between the company and the developer (weekly or monthly via any lawful mean agreed).

Internal developers get their share payed off as part of biannual gross salary correction to the closest possible approximation / projection for the period, so that the credit balance at the next salary correction is as close to zero as possible. The revenue projection / estimation used must be the same used for all internal developers.

If an internal developer should decide to leave the company, the remaining share from that point on shall be payed off as to an external participating developer.

All members of the project shall at any point in time be granted the access to all information regarding attribution, credits assigned, revenue, and expenses of the project.

Payments shall be made according to any applicable law and in gross value before any taxes apply.
