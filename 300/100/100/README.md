# 100 - Levels

To be able to set different levels (e.g. Strategic, Tactial, Operational) in NotePlan follow these steps:

## 100 - Create the Base Note

1. Open [NotePlan](https://app.noteplan.co/). **Note**: Use ```Apple ID Sign In``` (**not** ```Email Sign In```), so it gets synchronized across devices.

2. Click "New Note"

3. Title the note: "Annual Ritual Tracking 2025". **Note**: Replace ```2025``` by the year that is relevant.

Links:
- Instead of using `@due(2025-01-15)`, or `>2025-01-15`, it is prefered to use `[[2025-01-15]]` as it will update the text on that date if the text in the note is changed as well as creating a backlink.
- It is recommended to link to dates at task level (e.g. ```Gather performance metrics```) rather than at list level (e.g. ```Preparation Phase```).
- As well as linking to Calender entries, using the `[[A Name of a Note]]` you can equally link to other Notes.
- Should you want to link to a URL, you can use Markdown syntax like so; `This is a link to [google](google.com).`

## 200 - Basic Structure

**Note**: Replace ```2025``` below by the year that is relevant.

```markdown
# Annual Ritual Tracking 2025

## Vision Statement
- [x] Capture the overarching purpose and direction for the year

## Strategic Objectives
### #strategic Annual Goals
- [ ] Primary objective 1
- [ ] Primary objective 2
- [ ] Primary objective 3

## Quarterly Tactical Framework
### Q1 #tactical Focus
- [ ] Key result area 1
- [ ] Key result area 2

### Q2 #tactical Focus
- [ ] Key result area 1
- [ ] Key result area 2

### Q3 #tactical Focus
- [ ] Key result area 1
- [ ] Key result area 2

### Q4 #tactical Focus
- [ ] Key result area 1
- [ ] Key result area 2

## Operational Tracking
### Monthly #operational Checkpoints
- [ ] January review [[2025-01-31]]
- [ ] February review [[2025-02-29]]
- [ ] March review [[2025-03-31]]
...

## Progress Dashboard
- Total Strategic Goals: 0/3
- Total Tactical Objectives: 0/8
- Total Operational Tasks: 0/36

## Reflection Sections
### Quarterly Reflections
- Q1 Reflection [[2025-04-01]]
- Q2 Reflection [[2025-07-01]]
- Q3 Reflection [[2025-10-01]]
- Q4 Reflection [[2025-01-01]]

## Key Performance Indicators (KPIs)
- Indicator 1: 
- Indicator 2: 
- Indicator 3: 

## Notes and Insights
- Space for ongoing observations
- Links to detailed notes
```

## 300 - Linking Strategy

- Use double square brackets `[[]]` to link to:
  - Detailed quarterly plans
  - Specific project notes
  - Reflection documents

- Date notations have slightly different purposes:

1. `[[2025-01-15]]`
- Creates a two-way link to a calendar day
- Updates text across linked notes
- Visible in calendar
- Primary method for calendar integration

2. `>2025-01-15`
- Marks a task or event's date
- Often used for recurring events
- Helps with scheduling and filtering
- Can be used with calendar tags like `@daily`, `@weekly`

3. `@due(2025-01-15)`
- Primarily a task management feature
- Sets a deadline or due date for a task
- Does not necessarily link to calendar
- Useful for tracking task completion deadlines
- Can be used alongside calendar links

Example:
```markdown
- [ ] Submit quarterly report [[2025-01-15]] @due(2025-01-15) >2025-01-15 @quarterly
```

This comprehensive approach combines:
- Calendar linking
- Deadline tracking
- Scheduling
- Calendar tag

Calender Entries:
- If you have linked an item of a Note to a date in a Calendar, the Calendar view will show the item in a grey box. Clicking anywhere within the grey box from the Calendar view will bring you back to the Note it references.
- If you click on a checkbox within a grey box in a Calender view, the checkbox item will be marked as ticked without the need to go bak to the Note it is part of.

## 400 - Tagging Approach

- Add relevant tags:
  - `#annual`
  - `#strategic`
  - `#tactical`
  - `#operational`

## 500 - Maintenance Tips

- Review and update monthly
- Check off completed items
- Add new insights as they emerge
