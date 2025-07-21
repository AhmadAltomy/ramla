---
sidebar_position: 2
---

# Project Status Management Guide

Learn how to effectively track and communicate project status across your TODO Hub.

## 🎯 Status Categories Explained

### ❌ Not Started

**Definition**: Task is planned and documented but work hasn't begun  
**When to use**: Initial task creation, waiting for dependencies  
**Team action**: Review priorities, assign resources, set start date

**Example**:

```markdown
- [ ] ❌ **Design user onboarding flow** **Due: Feb 15**
  - **Status**: Waiting for user research completion
  - **Dependencies**: UX research findings
  - **Assigned**: @design-team
```

### 🟡 In Progress

**Definition**: Actively working on the task  
**When to use**: Work has started, progress is being made  
**Team action**: Regular check-ins, unblock obstacles, track progress

**Best Practice**: Include percentage or milestone completion

```markdown
- [ ] 🟡 **Backend API development** **Due: Feb 20** - 65% complete
  - **Current**: User authentication endpoints complete
  - **Next**: Implementing data validation layer
  - **Blockers**: None currently
```

### ✅ Completed

**Definition**: Task is fully finished and meets acceptance criteria  
**When to use**: All work done, tested, and approved  
**Team action**: Archive, celebrate, extract learnings

**Example**:

```markdown
- [x] ✅ **Mobile responsive header** **Completed: Feb 10**
  - **Delivered by**: @sarah-frontend
  - **Tested on**: iOS Safari, Android Chrome
  - **Notes**: Exceeded accessibility standards
```

### ⏸️ Blocked

**Definition**: Cannot proceed due to external dependencies  
**When to use**: Waiting for decisions, resources, or other tasks  
**Team action**: Identify blocker, escalate if needed, find workarounds

**Must Include**:

- What specifically is blocking progress
- Who can unblock it
- Expected resolution timeline
- Alternative approaches if any

```markdown
- [ ] ⏸️ **Payment integration testing** **Due: Feb 25**
  - **Blocked by**: Waiting for sandbox API credentials
  - **Blocker owner**: @vendor-team
  - **Expected resolution**: Feb 18
  - **Workaround**: Using mock data for UI development
```

### 🔄 Review

**Definition**: Work is complete but needs approval or testing  
**When to use**: Ready for QA, stakeholder review, or peer review  
**Team action**: Prioritize reviews, provide feedback, approve or iterate

**Example**:

```markdown
- [ ] 🔄 **Product landing page copy** **Due: Feb 16**
  - **Needs**: Marketing team approval
  - **Reviewer**: @marketing-lead
  - **Review by**: Feb 14
  - **Files**: [Google Doc Link]
```

## 📈 Priority Management System

### 🔴 P0 - Critical

**Characteristics**:

- System outages or security vulnerabilities
- Blocking multiple team members
- Revenue-impacting issues
- Client-facing problems

**Response Time**: Immediate (within hours)  
**Team Impact**: Drop everything else  
**Communication**: Real-time updates to leadership

### 🟠 P1 - High

**Characteristics**:

- Important feature development
- Significant user experience improvements
- Deadline-driven deliverables
- Dependencies for other teams

**Response Time**: Within 24-48 hours  
**Team Impact**: High priority in sprint planning  
**Communication**: Daily progress updates

### 🟡 P2 - Medium

**Characteristics**:

- Nice-to-have features
- Process improvements
- Technical debt reduction
- Non-urgent bug fixes

**Response Time**: Within 1 week  
**Team Impact**: Fits into normal sprint capacity  
**Communication**: Weekly status updates

### 🟢 P3 - Low

**Characteristics**:

- Future enhancements
- Research and exploration
- Minor improvements
- "Someday/maybe" items

**Response Time**: When capacity allows  
**Team Impact**: Filler work between priorities  
**Communication**: Monthly or quarterly reviews

## 🔄 Status Transition Guidelines

### Moving from ❌ to 🟡

**Required**:

- [ ] Resources assigned
- [ ] Dependencies identified and ready
- [ ] Clear acceptance criteria defined
- [ ] Timeline established

### Moving from 🟡 to 🔄

**Required**:

- [ ] Work completed according to specs
- [ ] Self-testing performed
- [ ] Documentation updated
- [ ] Reviewer identified and notified

### Moving from 🔄 to ✅

**Required**:

- [ ] All reviews passed
- [ ] Quality standards met
- [ ] Stakeholder approval received
- [ ] Implementation verified

### Moving to ⏸️ (Blocked)

**Required**:

- [ ] Specific blocker identified
- [ ] Blocker owner contacted
- [ ] Expected resolution timeline
- [ ] Alternative approaches explored

## 📊 Progress Tracking Methods

### 1. Completion Percentage

Use for large tasks that can be broken down:

```markdown
🟡 Database migration - 40% complete

- ✅ Schema design (100%)
- 🟡 Data transformation scripts (60%)
- ❌ Testing and validation (0%)
- ❌ Production deployment (0%)
```

### 2. Milestone Tracking

Use for projects with clear phases:

```markdown
🟡 E-commerce checkout flow

- ✅ Milestone 1: Cart functionality
- 🟡 Milestone 2: Payment integration (In Progress)
- ❌ Milestone 3: Order confirmation
- ❌ Milestone 4: Testing and optimization
```

### 3. Story Points Velocity

Use for development teams with established velocity:

```markdown
Sprint 3 Progress: 28/32 story points completed (87.5%)

- ✅ User registration (8 points)
- ✅ Password reset (5 points)
- 🟡 Profile management (8 points) - 75% done
- 🔄 Email notifications (5 points) - In review
- ❌ Social login (6 points) - Next sprint
```

## 🚨 Escalation Procedures

### When to Escalate

- **Red flags**: Task blocked for >2 days with no resolution plan
- **Scope creep**: Requirements significantly changing mid-task
- **Resource conflicts**: Multiple P0/P1 items competing for same person
- **Timeline risks**: Clear indicators deadline will be missed

### Escalation Levels

#### Level 1: Team Lead

- **Triggers**: Local blockers, resource conflicts within team
- **Response time**: Same day
- **Authority**: Reprioritize team tasks, reallocate resources

#### Level 2: Project Manager

- **Triggers**: Cross-team dependencies, timeline risks
- **Response time**: Within 24 hours
- **Authority**: Adjust project scope, negotiate deadlines

#### Level 3: Department Head

- **Triggers**: Budget impacts, strategic changes needed
- **Response time**: Within 48 hours
- **Authority**: Resource allocation, scope changes

### Escalation Communication Template

```markdown
**ESCALATION NEEDED**

**Task**: [Task name and link]
**Current Status**: [Status with details]
**Issue**: [Specific problem requiring escalation]
**Impact**: [What happens if not resolved]
**Requested Action**: [What you need from escalation level]
**Urgency**: [P0/P1/P2/P3 with reasoning]
**Context**: [Additional background if needed]
```

## 📈 Team Communication Patterns

### Daily Standups (5-10 minutes)

**Format for each person**:

1. **Yesterday**: What tasks moved status?
2. **Today**: What am I working on?
3. **Blockers**: Any ⏸️ items needing help?

### Weekly Status Reviews (15-30 minutes)

**Team discussion**:

- Review ⏸️ blocked items and resolution plans
- Assess progress toward sprint/milestone goals
- Identify risks and mitigation strategies
- Celebrate ✅ completions and team wins

### Sprint Retrospectives (30-60 minutes)

**Analyze patterns**:

- Which types of tasks consistently get ⏸️ blocked?
- Are our time estimates accurate?
- What's working well in our status management?
- How can we improve our process?

## 🎯 Status Dashboard Ideas

### Team Overview Dashboard

```markdown
## Team Status Overview (Week of Feb 12-16)

**Overall Progress**: 73% of sprint commitments on track

### By Status

- ❌ Not Started: 8 tasks
- 🟡 In Progress: 12 tasks
- 🔄 In Review: 4 tasks
- ⏸️ Blocked: 2 tasks
- ✅ Completed: 15 tasks

### Urgent Attention Needed

- 🔴 **Payment gateway integration** - Blocked 3 days
- 🟠 **Mobile testing** - Behind schedule, needs resources
```

### Individual Status Summary

```markdown
## Sarah's Weekly Status

**Completed This Week**:

- ✅ User profile API endpoints
- ✅ Password validation logic
- ✅ Code review for authentication module

**In Progress**:

- 🟡 Email verification system (60% complete)
- 🔄 Security audit documentation (waiting for review)

**Coming Up Next Week**:

- ❌ Social login integration
- ❌ Two-factor authentication
```

---

## 🎯 Quick Reference

### Status Change Checklist

When updating any task status, ask:

- [ ] Is the new status accurate and justified?
- [ ] Are dependencies and blockers clearly identified?
- [ ] Does the team need to know about this change?
- [ ] Is additional information or context needed?
- [ ] Should timeline or priority be adjusted?

### Communication Best Practices

- **Update status within 24 hours** of any change
- **Include context** not just status symbols
- **Tag relevant team members** when status affects them
- **Use clear, specific language** in status descriptions
- **Celebrate completions** to maintain team morale

Remember: Good status management isn't about perfect tracking—it's about enabling better team communication and decision-making! 🚀
