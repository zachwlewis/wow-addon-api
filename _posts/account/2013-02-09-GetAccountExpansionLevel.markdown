---
layout: function
title: "GetAccountExpansionLevel"
category: Account
description: Returns the level of expansions enabled for the current account.
returns:
- name: expansionLevel
  type: number
  description: "0 - Classic, 1 - Burning Crusade, 2 - Wrath of the Lich King, 3 - Cataclysm, 4 - Mists of Pandaria"
---

Get the maximum player level, based on available expansions.

    maximum_level = MAX_PLAYER_LEVEL_TABLE[GetAccountExpansionLevel()]