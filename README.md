# Cuckoo
Cuckoo sandbox for automatized malware analysis

## Getting Started

First, download cuckoo or copy this repository to get everything you need to get started,
may need to install yara, pcrypto and some other plugins in order to run properly

## Scripts

List of changes made to cuckoo config to set up everything

### Agent

Install the copy of agent.py in order to run cuckoo, via console, in win7

```
ageny.py
```
### Analyzer

In this case only Windows used, modules auxiliary and packages, can customize our own in there


### Conf

Set up for virtualbox and win7, configure reporting, virtualbox, routing to not to allow malware to go outside your network.

### Elasticsearch

Currently not working, no compability with last version of elasticsearch, error indexing.

## To start cuckoo

In path: 

```
./cuckoo
```
Check cuckoo doc to feed malware via
```
./cuckoo pathToMalware or --package
```
If not, use the forward script of RScripts and add all the malware to the same path.


