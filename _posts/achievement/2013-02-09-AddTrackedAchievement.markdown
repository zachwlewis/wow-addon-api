---
layout: function
title: "AddTrackedAchievement"
category: Achievement
description: Marks an achievement for tracking.
arguments:
- name: achievementId
  type: number
  description: ID of the achievement to mark for tracking.
events:
- TRACKED_ACHIEVEMENT_UPDATE
---

- Up to `WATCHFRAME_MAXACHIEVEMENTS` may be displayed by the FrameXML tracker at a time.