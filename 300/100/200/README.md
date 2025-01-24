# 200 - Program Increment Planning Events (PIPE)s

To be able to set plan following the Scaled Agile (SAfe) methodology in NotePlan follow these steps:

## 100 - Create the Base Note

1. Open [NotePlan](https://app.noteplan.co/). **Note**: Use ```Apple ID Sign In``` (**not** ```Email Sign In```), so it gets synchronized across devices.

2. Click "New Note"

3. Title the note: "2025 PI Planning Tracker". **Note**: Replace ```2025``` by the year that is relevant. See how we make use of the tagging introduced earlier, to distinguish when an activity is taking place (e.g. ```Quarterly```) and at which level (e.g. ```Strategic```).

Tags:
- `#annual` for the overall yearly plan
- `#quarterly` for quarterly-specific activities
- `#strategic` for high-level planning and vision
- `#tactical` for intermediate-term objectives
- `#operational` for day-to-day execution tasks

Links:
- Instead of using `@due(2025-01-15)`, or `>2025-01-15`, it is prefered to use `[[2025-01-15]]` as it will update the text on that date if the text in the note is changed as well as creating a backlink. Best of all though is to use each and everyone of them together to benefit from all features: `[[2025-01-15]] @due(2025-01-15) >2025-01-15 @quarterly`.
- It is recommended to link to dates at task level (e.g. ```Gather performance metrics```) rather than at list level (e.g. ```Preparation Phase```).

Date notations have slightly different purposes:

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

## 200 - Basic Structure

**Note**: Replace ```2025``` below by the year that is relevant.

```markdown
# 2025 PI Planning Tracker #annual #strategic #agile #safe

## Program Increment (PI) Planning Schedule
- [ ] Q1 PI Planning Event [[2025-01-15]] @due(2025-01-15) >2025-01-15 @quarterly #quarterly #strategic
- [ ] Q2 PI Planning Event [[2025-04-15]] @due(2025-04-15) >2025-04-15 @quarterly #quarterly #strategic
- [ ] Q3 PI Planning Event [[2025-07-15]] @due(2025-07-15) >2025-07-15 @quarterly #quarterly #strategic
- [ ] Q4 PI Planning Event [[2025-10-15]] @due(2025-10-15) >2025-10-15 @quarterly #quarterly #strategic

## Q1 PI Planning Event Agenda #quarterly #tactical
### Pre-Planning Preparation #operational
- [ ] Review organizational strategic objectives
- [ ] Collect team capacity and velocity data
- [ ] Prepare program backlog

### PI Planning Day 1 #tactical
1. Business Context #operational
- [ ] Executive briefing
- [ ] Current business objectives
- [ ] Market and customer insights

2. Architecture and Roadmap Presentation #strategic
- [ ] Technical constraints
- [ ] System architecture overview
- [ ] Upcoming technological considerations

3. Team Breakout Sessions #tactical #operational
- [ ] Capacity planning
- [ ] Initial feature decomposition
- [ ] Dependency identification

### PI Planning Day 2 #tactical
1. Program Board Development #strategic
- [ ] Cross-team synchronization
- [ ] Dependency management
- [ ] Commitment to PI objectives

2. Management Review and Confidence Vote #tactical
- [ ] Team presentations
- [ ] Risk management
- [ ] Confidence voting

### Post-Planning Activities #operational
- [ ] Finalize PI objectives
- [ ] Update program backlog
- [ ] Communicate PI plan to stakeholders

## Quarterly Tracking #quarterly #tactical
### Q1 PI Objectives #strategic
- [ ] Objective 1 
- [ ] Objective 2
- [ ] Objective 3

### Dependency Tracking #operational
- [ ] External dependencies
- [ ] Internal team dependencies

## Metrics and Retrospective #quarterly #tactical
- [ ] Planned Velocity
- [ ] Actual Velocity
- [ ] Program Predictability
- [ ] Business Value Delivered

## Reflection Notes #strategic
- Space for insights, challenges, and improvements
```

## 300 - Quarterly Program Increment Planning Event (PIPE)

**First Quarter: January - March**

```markdown
# Q1 2025 Program Increment Planning Event (PIPE) #quarterly #strategic

## Preparation Phase
- [ ] Gather previous PI performance metrics [[2025-01-01]] @due(2025-01-15) >2025-01-15 @quarterly #tactical #operational
- [ ] Collect team capacity reports [[2025-01-01]] @due(2025-01-15) >2025-01-15 @quarterly #tactical #operational
- [ ] Review organizational strategic objectives [[2025-01-01]] @due(2025-01-15) >2025-01-15 @quarterly #tactical #operational
- [ ] Compile program backlog [[2025-01-01]] @due(2025-01-15) >2025-01-15 @quarterly #tactical #operational
- [ ] Identify key stakeholders [[2025-01-01]] @due(2025-01-15) >2025-01-15 @quarterly #tactical #operational

## PI Planning Event Agenda #quarterly #strategic

### Day 1: Strategic Alignment
#### Morning Session
- [ ] Executive Vision Presentation [[2025-01-15]] @due(2025-01-15) >2025-01-15
- [ ] Current Business Objectives Review
- [ ] Market and Customer Insights
- [ ] Technical Architecture Briefing

#### Afternoon Session
- [ ] Team Capacity Planning
- [ ] Initial Feature Decomposition
- [ ] Dependency Mapping Workshop

### Day 2: Execution Planning
#### Morning Session
- [ ] Cross-Team Synchronization
- [ ] Program Board Development
- [ ] Risk Identification and Mitigation

#### Afternoon Session
- [ ] Confidence Voting
- [ ] PI Objectives Finalization
- [ ] Communication Plan Development

## Post-Event Deliverables #operational
- [ ] Finalized PI Objectives Document
- [ ] Updated Program Backlog
- [ ] Dependency Tracking Sheet
- [ ] Communication Plan

## Metrics Tracking #tactical
- [ ] Planned Velocity
- [ ] Team Capacity
- [ ] Identified Risks
- [ ] Strategic Alignment Score

## Reflection and Continuous Improvement #strategic
- [ ] Key Insights
- [ ] Improvement Opportunities
- [ ] Lessons Learned
```

**Second Quarter: April - June**

```markdown
# Q2 2025 Program Increment Planning Event (PIPE) #quarterly #strategic

## Preparation Phase
- [ ] Gather previous PI performance metrics [[2025-04-01]] @due(2025-04-15) >2025-04-15 @quarterly #tactical #operational
- [ ] Collect team capacity reports [[2025-04-01]] @due(2025-04-15) >2025-04-15 @quarterly #tactical #operational
- [ ] Review organizational strategic objectives [[2025-04-01]] @due(2025-04-15) >2025-04-15 @quarterly #tactical #operational
- [ ] Compile program backlog [[2025-04-01]] @due(2025-04-15) >2025-04-15 @quarterly #tactical #operational
- [ ] Identify key stakeholders [[2025-04-01]] @due(2025-04-15) >2025-04-15 @quarterly #tactical #operational

## PI Planning Event Agenda #quarterly #strategic

### Day 1: Strategic Alignment
#### Morning Session
- [ ] Executive Vision Presentation [[2025-04-15]] @due(2025-04-15) >2025-04-15
- [ ] Current Business Objectives Review
- [ ] Market and Customer Insights
- [ ] Technical Architecture Briefing

#### Afternoon Session
- [ ] Team Capacity Planning
- [ ] Initial Feature Decomposition
- [ ] Dependency Mapping Workshop

### Day 2: Execution Planning
#### Morning Session
- [ ] Cross-Team Synchronization
- [ ] Program Board Development
- [ ] Risk Identification and Mitigation

#### Afternoon Session
- [ ] Confidence Voting
- [ ] PI Objectives Finalization
- [ ] Communication Plan Development

## Post-Event Deliverables #operational
- [ ] Finalized PI Objectives Document
- [ ] Updated Program Backlog
- [ ] Dependency Tracking Sheet
- [ ] Communication Plan

## Metrics Tracking #tactical
- [ ] Planned Velocity
- [ ] Team Capacity
- [ ] Identified Risks
- [ ] Strategic Alignment Score

## Reflection and Continuous Improvement #strategic
- [ ] Key Insights
- [ ] Improvement Opportunities
- [ ] Lessons Learned
```

**Third Quarter: July - August**

```markdown
# Q3 2025 Program Increment Planning Event (PIPE) #quarterly #strategic

## Preparation Phase
- [ ] Gather previous PI performance metrics [[2025-07-01]] @due(2025-07-15) >2025-07-15 @quarterly #tactical #operational
- [ ] Collect team capacity reports [[2025-07-01]] @due(2025-07-15) >2025-07-15 @quarterly #tactical #operational
- [ ] Review organizational strategic objectives [[2025-07-01]] @due(2025-07-15) >2025-07-15 @quarterly #tactical #operational
- [ ] Compile program backlog [[2025-07-01]] @due(2025-07-15) >2025-07-15 @quarterly #tactical #operational
- [ ] Identify key stakeholders [[2025-07-01]] @due(2025-07-15) >2025-07-15 @quarterly #tactical #operational

## PI Planning Event Agenda #quarterly #strategic

### Day 1: Strategic Alignment
#### Morning Session
- [ ] Executive Vision Presentation [[2025-07-15]] @due(2025-07-15) >2025-07-15
- [ ] Current Business Objectives Review
- [ ] Market and Customer Insights
- [ ] Technical Architecture Briefing

#### Afternoon Session
- [ ] Team Capacity Planning
- [ ] Initial Feature Decomposition
- [ ] Dependency Mapping Workshop

### Day 2: Execution Planning
#### Morning Session
- [ ] Cross-Team Synchronization
- [ ] Program Board Development
- [ ] Risk Identification and Mitigation

#### Afternoon Session
- [ ] Confidence Voting
- [ ] PI Objectives Finalization
- [ ] Communication Plan Development

## Post-Event Deliverables #operational
- [ ] Finalized PI Objectives Document
- [ ] Updated Program Backlog
- [ ] Dependency Tracking Sheet
- [ ] Communication Plan

## Metrics Tracking #tactical
- [ ] Planned Velocity
- [ ] Team Capacity
- [ ] Identified Risks
- [ ] Strategic Alignment Score

## Reflection and Continuous Improvement #strategic
- [ ] Key Insights
- [ ] Improvement Opportunities
- [ ] Lessons Learned
```

**Fourth Quarter: October - December**

```markdown
# Q4 2025 Program Increment Planning Event (PIPE) #quarterly #strategic

## Preparation Phase
- [ ] Gather previous PI performance metrics [[2025-10-01]] @due(2025-10-15) >2025-10-15 @quarterly #tactical #operational
- [ ] Collect team capacity reports [[2025-10-01]] @due(2025-10-15) >2025-10-15 @quarterly #tactical #operational
- [ ] Review organizational strategic objectives [[2025-10-01]] @due(2025-10-15) >2025-10-15 @quarterly #tactical #operational
- [ ] Compile program backlog [[2025-10-01]] @due(2025-10-15) >2025-10-15 @quarterly #tactical #operational
- [ ] Identify key stakeholders [[2025-10-01]] @due(2025-10-15) >2025-10-15 @quarterly #tactical #operational

## PI Planning Event Agenda #quarterly #strategic

### Day 1: Strategic Alignment
#### Morning Session
- [ ] Executive Vision Presentation [[2025-10-15]] @due(2025-10-15) >2025-10-15
- [ ] Current Business Objectives Review
- [ ] Market and Customer Insights
- [ ] Technical Architecture Briefing

#### Afternoon Session
- [ ] Team Capacity Planning
- [ ] Initial Feature Decomposition
- [ ] Dependency Mapping Workshop

### Day 2: Execution Planning
#### Morning Session
- [ ] Cross-Team Synchronization
- [ ] Program Board Development
- [ ] Risk Identification and Mitigation

#### Afternoon Session
- [ ] Confidence Voting
- [ ] PI Objectives Finalization
- [ ] Communication Plan Development

## Post-Event Deliverables #operational
- [ ] Finalized PI Objectives Document
- [ ] Updated Program Backlog
- [ ] Dependency Tracking Sheet
- [ ] Communication Plan

## Metrics Tracking #tactical
- [ ] Planned Velocity
- [ ] Team Capacity
- [ ] Identified Risks
- [ ] Strategic Alignment Score

## Reflection and Continuous Improvement #strategic
- [ ] Key Insights
- [ ] Improvement Opportunities
- [ ] Lessons Learned
```
