# 300 - Calender Entries

In NotePlan, you can make activities show in the calendar by using specific date tags and formatting. Here are the key methods:

1. Date Tagging
- Use `@due(YYYY-MM-DD)` for specific dates, however a more reliable format is `>(YYY-MM-DD)`
- Example: `@due(2025-01-15)`, better `>(2025-01-15)`

2. Calendar View Activation
- Click on the calendar icon in NotePlan
- Ensure the date tags are correctly formatted
- Events and tasks with dates will automatically populate

3. Recommended Date Tagging Strategy

```markdown
# Q1 2025 Program Increment Planning Event

## Preparation Phase @due(2025-01-01) #quarterly #tactical
- [ ] Gather performance metrics @due(2025-01-05)
- [ ] Collect team capacity reports @due(2025-01-10)

## PI Planning Event @due(2025-01-15)
- [ ] Day 1 Morning Session @due(2025-01-15)
- [ ] Day 1 Afternoon Session @due(2025-01-15)
- [ ] Day 2 Morning Session @due(2025-01-16)
- [ ] Day 2 Afternoon Session @due(2025-01-16)
```

4. Additional Calendar Integration Tips
- Use consistent date formatting
- Add time if needed: `@due(2025-01-15 09:00)`
- Tag with recurring event indicators if applicable
