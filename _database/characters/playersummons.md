---
title: playersummons
type: characterdb
category: P
layout: single_markdown
---

# playersummons
This table contains the relation between players and pets to be allowed to summon.

## Structure

Field                   | Type        | Default | Comment
----------------------- | ----------- | ------- | -------
[ownerguid](#ownerguid) | int(11)     | 0       |        
[entry](#entry)         | int(11)     | 0       |        
[name](#name)           | varchar(64) |         |        

### ownerguid

The character guid of the pet owner from characters table.

### entry

The creature entry ID from creature_properties table.

### name

The pet name (generated by core/created by player).