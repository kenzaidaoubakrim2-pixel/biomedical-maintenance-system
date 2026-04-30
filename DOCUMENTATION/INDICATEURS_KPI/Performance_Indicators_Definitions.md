# Performance Indicators (KPI) Definitions - MIAO-MB Model

## Overview
This document provides detailed definitions, formulas, targets, and measurement methods for all KPIs used in MIAO-MB system monitoring.

---

## 1. Preventive Maintenance Completion Rate

### Definition
Percentage of scheduled preventive maintenance tasks that were completed on or before the scheduled date during the reporting period.

### Formula
Preventive Compliance (%) = (Preventive Tasks Completed / Preventive Tasks Scheduled) × 100

### Measurement Method
1. Count all preventive maintenance tasks scheduled for the period
2. Count tasks actually completed by scheduled date
3. Calculate percentage
4. Document in KPI tracking sheet

### Data Sources
- Maintenance schedule
- Intervention reports
- GMAO system records

### Target
**> 95%**

### Acceptable Range
- 95-100% = Excellent
- 90-94% = Good
- 80-89% = Acceptable
- < 80% = Poor (corrective action required)

### Frequency
Monthly calculation, reported to management

### Analysis
- Compare month-to-month trend
- Identify equipment with missed tasks
- Analyze reasons for delays
- Take corrective action if below target

### Root Causes of Variance
- Equipment unavailability
- Resource constraints (technician availability)
- Procedure confusion
- Priority shift to corrective maintenance
- Scheduling conflicts

### Improvement Actions
- Adjust scheduling to equipment usage patterns
- Increase resource allocation
- Improve communication with departments
- Enhance planning

---

## 2. Mean Time To Repair (MTTR)

### Definition
Average time from detection of equipment failure to return of equipment to operational service.

### Formula
MTTR (hours) = Total Repair Time (hours) / Number of Repairs in Period

### Calculation Example
- Repair 1: 4 hours
- Repair 2: 8 hours
- Repair 3: 6 hours
- Total: 18 hours / 3 repairs = **6 hours MTTR**

### Measurement Method
1. Record failure detection date and time
2. Record repair completion date and time
3. Calculate repair duration for each failure
4. Sum all repair hours for period
5. Divide by number of repairs
6. Document in KPI tracking

### Data Sources
- Intervention reports
- Failure logs
- GMAO system
- Maintenance records

### Target
**Minimize** (continuously decreasing trend)
- Baseline: Current average
- Year 1 Target: 10% reduction
- Year 2 Target: 20% reduction

### Acceptable Range
- By equipment type or criticality
- Critical equipment: < 4 hours target
- Essential equipment: < 8 hours target
- Important equipment: < 24 hours acceptable

### Frequency
Monthly calculation and analysis

### Analysis
- Trend analysis (improving/stable/declining)
- Equipment-specific analysis
- Identify repairs taking longest
- Analyze root causes
- Track improvement from corrective actions

### Root Causes of High MTTR
- Spare parts unavailable
- Technician skill gaps
- Complex repair required
- Equipment unavailable for repair
- Diagnostic challenges
- External dependencies (vendor support)

### Improvement Actions
- Stock critical spare parts
- Technician training
- Improve diagnostic tools
- Preventive maintenance (reduce failures)
- Vendor relationship management

---

## 3. Mean Time Between Failures (MTBF)

### Definition
Average operating time between equipment failures.

### Formula
MTBF (hours) = Total Operating Time / Number of Failures in Period



### Calculation Example
- Equipment operating 730 hours/month
- 2 failures occurred
- MTBF = 730 / 2 = **365 hours**

### Measurement Method
1. Track equipment operating hours
2. Count number of failures
3. Divide operating hours by failure count
4. Document trend over time

### Data Sources
- Equipment usage logs
- Failure reports
- GMAO system
- Operating records

### Target
**Maximize** (continuously increasing trend)
- Year 1: Establish baseline
- Year 2: 15% improvement
- Year 3: 30% improvement

### Acceptable Values
- By equipment type
- Critical equipment: MTBF > 500 hours
- Essential equipment: MTBF > 250 hours
- Increasing trend = Good

### Frequency
Monthly calculation, quarterly analysis

### Analysis
- Compare equipment MTBF values
- Identify equipment with low MTBF
- Trend analysis (improving/stable/declining)
- Impact of preventive maintenance changes
- Correlation with maintenance intervals

### Root Causes of Low MTBF
- Inadequate preventive maintenance
- Aggressive usage
- Environmental factors
- Equipment age/wear
- Design defect
- Manufacturing defect

### Improvement Actions
- Increase preventive maintenance frequency
- Review maintenance procedures
- Operator training
- Environmental controls
- Parts upgrades
- Equipment replacement

---

## 4. Equipment Availability

### Definition
Percentage of time critical equipment is available for use during required operation hours.

### Formula

Availability (%) = (Required Hours - Downtime Hours) / Required Hours × 100

### Calculation Example
- Required operation: 720 hours/month
- Downtime: 14 hours (preventive 6 hrs + corrective 8 hrs)
- Availability = (720 - 14) / 720 × 100 = **98.1%**

### Measurement Method
1. Define required operation hours per equipment
2. Track all downtime (preventive + corrective)
3. Calculate available hours
4. Calculate percentage
5. Track separately by equipment

### Data Sources
- Maintenance schedule
- Failure logs
- Intervention reports
- Equipment usage logs

### Target
**> 98% for Critical Equipment**
**> 95% for Essential Equipment**
**> 90% for Important Equipment**

### Acceptable Range
- > 98% = Excellent
- 95-98% = Good
- 90-94% = Acceptable
- < 90% = Poor (action required)

### Frequency
Monthly by equipment, reported to management

### Analysis
- Equipment-specific analysis
- Trend by month/quarter
- Identify equipment below target
- Analyze downtime causes (preventive vs. corrective)
- Calculate impact on operations

### Components of Downtime
**Planned Downtime (Preventive):**
- Regular preventive maintenance
- Calibration and testing
- Planned equipment replacement

**Unplanned Downtime (Corrective):**
- Equipment failure
- Emergency repair
- Safety issues

### Root Causes of Low Availability
- Frequent equipment failures (low MTBF)
- Long repair times (high MTTR)
- Excessive preventive maintenance
- Scheduling conflicts
- Resource constraints

### Improvement Actions
- Improve MTBF (preventive maintenance)
- Reduce MTTR (efficiency)
- Optimize preventive schedule
- Add backup equipment
- Better resource planning

---

## 5. Recurrence Rate (Repeat Failure Rate)

### Definition
Percentage of failures that are repeated failures (same equipment, same or similar failure mode within 30 days).

### Formula
Recurrence Rate (%) = (Repeated Failures / Total Failures) × 100


### Calculation Example
- Total failures in month: 10
- Failures that recurred within 30 days: 1
- Recurrence Rate = 1/10 × 100 = **10%**

### Measurement Method
1. Classify each failure as "new" or "repeat"
2. Repeat = Same equipment, same failure within 30 days
3. Count recurring failures
4. Calculate percentage
5. Identify which equipment has repeats

### Data Sources
- Failure history
- Root cause analysis results
- CAPA tracking
- Maintenance records

### Target
**< 10%**

### Acceptable Range
- < 5% = Excellent
- 5-10% = Good
- 10-15% = Acceptable (investigate)
- > 15% = Poor (immediate action)

### Frequency
Monthly analysis, trending

### Analysis
- Equipment-specific recurrence rates
- Trend analysis
- Root cause analysis of repeated failures
- CAPA effectiveness review
- Corrective action verification

### Root Causes of High Recurrence
- Inadequate root cause analysis
- Ineffective corrective actions
- Incomplete repairs
- Design defect not addressed
- Similar failure mode in related parts
- Poor CAPA execution

### Improvement Actions
- Enhance root cause analysis
- Verify CAPA effectiveness
- Improve repair procedures
- Consider parts upgrade or replacement
- Operator training
- Design review if applicable

---

## 6. Document Compliance Rate

### Definition
Percentage of maintenance activities with complete, accurate, and properly documented intervention reports.

### Formula
Document Compliance (%) = (Compliant Records / Audited Records) × 100


### Measurement Method
1. Sample maintenance records (minimum 20 per period)
2. Audit for completeness and accuracy
3. Check all required fields filled
4. Verify dates, times, technician, parts
5. Assess clarity and legibility
6. Calculate compliance percentage

### Data Sources
- Intervention reports
- Maintenance records
- GMAO system
- Audit sampling

### Target
**> 95%**

### Acceptable Range
- > 95% = Excellent
- 90-95% = Good
- 80-89% = Acceptable (training recommended)
- < 80% = Poor (corrective action required)

### Frequency
Monthly sampling and analysis

### Analysis
- Identify common omissions or errors
- Technician-specific analysis
- Trend over time
- Equipment-specific issues
- Form clarity assessment

### Root Causes of Non-Compliance
- Unclear form design
- Technician rushing
- Technician training gaps
- Lack of accountability
- GMAO system issues
- Form accessibility

### Improvement Actions
- Form simplification
- Technician training/retraining
- Accountability measures
- GMAO system fixes
- Form accessibility improvement
- Templates and guidance

---

## 7. CAPA Closure Rate

### Definition
Percentage of open corrective and preventive actions that are formally closed after effectiveness verification within target timelines.

### Formula

### Measurement Method
1. Sample maintenance records (minimum 20 per period)
2. Audit for completeness and accuracy
3. Check all required fields filled
4. Verify dates, times, technician, parts
5. Assess clarity and legibility
6. Calculate compliance percentage

### Data Sources
- Intervention reports
- Maintenance records
- GMAO system
- Audit sampling

### Target
**> 95%**

### Acceptable Range
- > 95% = Excellent
- 90-95% = Good
- 80-89% = Acceptable (training recommended)
- < 80% = Poor (corrective action required)

### Frequency
Monthly sampling and analysis

### Analysis
- Identify common omissions or errors
- Technician-specific analysis
- Trend over time
- Equipment-specific issues
- Form clarity assessment

### Root Causes of Non-Compliance
- Unclear form design
- Technician rushing
- Technician training gaps
- Lack of accountability
- GMAO system issues
- Form accessibility

### Improvement Actions
- Form simplification
- Technician training/retraining
- Accountability measures
- GMAO system fixes
- Form accessibility improvement
- Templates and guidance

---

## 7. CAPA Closure Rate

### Definition
Percentage of open corrective and preventive actions that are formally closed after effectiveness verification within target timelines.

### Formula
CAPA Closure Rate (%) = (CAPA Closed On-Time / Total CAPA) × 100


### Measurement Method
1. Track all open CAPA actions
2. Identify target closure date for each
3. Verify closure date vs. target
4. Count on-time closures
5. Calculate percentage
6. Separate by type (Minor/Major/Critical)

### Data Sources
- CAPA register
- Effectiveness verification records
- Management review minutes

### Target
**> 90% on-time closure**

### Acceptable Range
- > 90% = Excellent
- 85-90% = Good
- 80-85% = Acceptable (need improvement)
- < 80% = Poor (action required)

### Frequency
Monthly tracking, reported to management

### Analysis
- Trend over time
- Type-specific analysis (Major vs. Minor)
- Age of open CAPA
- Root cause of delays
- Effectiveness verification status

### Root Causes of Late Closure
- Root cause analysis delayed
- Corrective action implementation delayed
- Effectiveness verification not performed
- Verification showed ineffectiveness
- Resource constraints
- Organizational changes

### Improvement Actions
- Faster root cause analysis
- Realistic timeline setting
- Dedicated resources
- Weekly status monitoring
- Escalation procedures
- Effectiveness verification emphasis

---

## 8. Customer Satisfaction Score

### Definition
Overall satisfaction of equipment users with maintenance service quality.

### Formula
Satisfaction Score = (Sum of Response Scores / Number of Responses / Maximum Score) × 100


### Measurement Method
1. Annual satisfaction survey
2. Questions rated on scale of 1-5
3. Calculate average score
4. Convert to percentage
5. Track trend year-over-year

### Survey Questions
- Service quality: 1-5
- Technician competence: 1-5
- Response time: 1-5
- Communication: 1-5
- Equipment uptime: 1-5
- Overall satisfaction: 1-5

### Data Sources
- Annual customer survey
- Complaint logs
- Service feedback
- User interviews

### Target
**> 85%**

### Acceptable Range
- > 85% = Excellent
- 75-85% = Good
- 65-75% = Acceptable (improvement needed)
- < 65% = Poor (corrective action)

### Frequency
Annual survey, quarterly complaint tracking

### Analysis
- Score by category
- Score by department
- Trend year-over-year
- Complaint analysis
- Suggestion analysis

### Root Causes of Low Satisfaction
- Slow response time
- Equipment unavailability
- Technician competence
- Communication issues
- Equipment failures
- User expectations

### Improvement Actions
- Response time improvement
- Technician training
- Communication enhancement
- Preventive maintenance
- User training
- Expectation management

---

## Summary KPI Dashboard

| KPI | Formula | Target | Frequency | Owner |
|-----|---------|--------|-----------|-------|
| Preventive Compliance | Completed/Planned × 100 | > 95% | Monthly | Maintenance Supervisor |
| MTTR | Total hours / Failures | Minimize | Monthly | Quality Manager |
| MTBF | Operating hours / Failures | Maximize | Monthly | Quality Manager |
| Availability | (Hours - Downtime) / Hours × 100 | > 98% critical | Monthly | Maintenance Director |
| Recurrence Rate | Repeats / Total × 100 | < 10% | Monthly | Quality Manager |
| Document Compliance | Compliant / Audited × 100 | > 95% | Monthly | Quality Manager |
| CAPA Closure | Closed on-time / Total × 100 | > 90% | Monthly | Quality Manager |
| Satisfaction | Survey average / Max × 100 | > 85% | Quarterly | Quality Manager |

---

## KPI Monitoring and Reporting

### Monthly KPI Report Contents
- Performance data for each KPI
- Comparison to target
- Trend analysis
- Variance explanations
- Corrective actions taken
- Forecasting for next period

### Quarterly Management Review
- KPI trends over 3 months
- Seasonal patterns
- Improvement initiatives impact
- Resource adequacy
- Strategic alignment

### Annual Assessment
- Year-over-year comparison
- Target achievement
- Lessons learned
- Baseline revision
- Objectives for next year

### Escalation Rules
- If KPI < 80% of target for 2 months: Yellow alert
- If KPI < 70% of target or trend declining: Red alert
- Escalate to management for action planning
  
