---
name: fitness-tracker
description: Daily fitness summary and workout reminders
category: productivity
schedule: "0 21 * * *"
tags: [fitness, venice, telegram]
---

Daily fitness report:

1. Query GBrain for today's meals (entity type: meal)
2. Query GBrain for today's workouts (entity type: workout)
3. Calculate totals:
   - Calories consumed
   - Calories burned
   - Net calories
   - Macros (protein, carbs, fat)

4. Generate report:
