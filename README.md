# TVHeadend-Astra-19.2E

A Collection of Channels and Muxes for Astra 19.2E Satellite TV

__Work in Progress__

## Branch Structure

There is a single Branches for each:

| Branch			| Info					|
| -----------------	| ---------------------	|
| documentation		| Readme and such		|
| channels/tags		| Tags set in Channels	|
| muxes				| Muxes scanned by TVH	|

Branches containing channels are composed like this:

__channels/country-code/type/quality/list-type__

| branch-part	| values 				| meaning					|
| -------------	| --------------------- | -------------------------	|
| country-code	| en de fr ...			| main country or language	|
| type			| free or paid			| free or paid service		|
| quality		| sd or hd				| hd is 720p and higher		|
| list type		| compact others full	| optional for large lists	|

These branches go directly into the main branch

Exsamples:

- channels/de/free/hd/compact
- channels/en/paid/sd/others
- channels/fr/paid/hd/full

Each of these Branches go into a similar named release branch.

## Contribution

1. Choose the correct Branch
2. If you add a new Channel, make sure the Channel name is mentioned in commit text.
