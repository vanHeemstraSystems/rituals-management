# 300 - Calender Entries

In NotePlan, you can make activities show in the calendar by using specific date tags and formatting. Here are the key methods:

1. Date Tagging
- Use `@due(YYYY-MM-DD)` for specific dates, however a more reliable format is `>YYYY-MM-DD`, but still better is `[[YYYY-MM-DD]]` as it updates the text on the calendar day if changed in the note.
- Example: `@due(2025-01-15)`, better `>2025-01-15`, still better `[[2025-01-15]]`

2. Calendar View Activation
- Click on the calendar icon in NotePlan
- Ensure the date tags are correctly formatted `YYYY-MM-DD`
- Use the calendar specific tag like `@daily` for the daily calendar
- Events and tasks with dates will automatically populate

3. Recommended Date Tagging Strategy

```markdown
# Q1 2025 Program Increment Planning Event

## Preparation Phase
- [ ] Gather performance metrics [[2025-01-05]] #quarterly #tactical @daily
- [ ] Collect team capacity reports [[2025-01-10]] #quarterly #tactical @quarterly

## PI Planning Event
- [ ] Day 1 Morning Session [[2025-01-15]] #quarterly #strategic @quarterly
- [ ] Day 1 Afternoon Session [[2025-01-15]] #quarterly #strategic @quarterly
- [ ] Day 2 Morning Session [[2025-01-16]] #quarterly #tactical @quarterly
- [ ] Day 2 Afternoon Session [[2025-01-16]] #quarterly #tactical @quarterly
```

4. Additional Calendar Integration Tips
- Use consistent date formatting `[[YYYY-MM-DD]]`
- Add time if needed: `[[2025-01-15 09:00]]`
- Tag with recurring event indicators if applicable
