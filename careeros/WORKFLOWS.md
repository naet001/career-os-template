# CareerOS - Workflows

## Overview

This file describes the daily, weekly, and monthly workflows for managing your career using CareerOS. These workflows guide how you interact with the AI agents.

## Daily Workflows

### Morning Routine (15-30 minutes)

**Goal:** Start your day with focus and identify immediate opportunities.

1. **Review Priorities**
   - Check `TARGETS.md` for your current focus areas
   - Review `data/outreach.csv` for pending follow-ups
   - Check `data/jobs.csv` for application deadlines

2. **Quick Research** (5-10 minutes)
   - Ask the **Researcher** agent: "What are 3 new companies or people I should connect with today?"
   - Focus on your high-priority targets from `TARGETS.md`

3. **Follow-up Check** (5 minutes)
   - Ask the **Outreach** agent: "Who do I need to follow up with today?"
   - Review responses from previous outreach in `data/outreach.csv`
   - Send follow-up messages as needed (with approval)

4. **Application Check** (5 minutes)
   - Ask the **Application** agent: "Are there any new job postings I should apply to?"
   - Check for new opportunities matching your targets

5. **Study Session** (10-15 minutes)
   - Ask the **Interview Coach** agent: "What should I study today for interview prep?"
   - Review `data/study.csv` for topics to review
   - Focus on weak areas or upcoming interview topics

### Evening Routine (10-15 minutes)

**Goal:** Wrap up the day and prepare for tomorrow.

1. **Update Records**
   - Add any new connections to `data/people.csv`
   - Update `data/outreach.csv` with today's activities
   - Add new job opportunities to `data/jobs.csv`
   - Save important conversations to `records/messages/`

2. **Review Progress**
   - Check what you accomplished today
   - Note any responses received
   - Update statuses in CSV files

3. **Plan Tomorrow**
   - Identify 1-2 key outreach targets for tomorrow
   - Note any application deadlines
   - Set study goals for tomorrow

## Weekly Workflows

### Monday: Planning & Research

**Focus:** Set weekly goals and conduct deeper research.

1. **Weekly Planning** (15 minutes)
   - Review `TARGETS.md` and set weekly goals
   - Ask the **Manager** agent: "What should I focus on this week?"
   - Define: [X] outreach messages, [X] applications, [X] study sessions

2. **Company Research** (30 minutes)
   - Ask the **Researcher** agent: "Find 10 new companies in [target industry] that are hiring for [target role]"
   - Add promising companies to `data/companies.csv`
   - Research key people at these companies
   - Add relevant contacts to `data/people.csv`

3. **Job Search** (20 minutes)
   - Ask the **Application** agent: "Find new job postings matching my profile"
   - Review and add relevant jobs to `data/jobs.csv`
   - Prioritize based on your targets

### Tuesday & Thursday: Outreach Days

**Focus:** Connect with new people and follow up on existing conversations.

1. **New Outreach** (45 minutes)
   - Ask the **Outreach** agent: "Help me create personalized messages for [X] people from my targets"
   - Select 3-5 high-priority contacts from `data/people.csv`
   - Create personalized, non-generic messages
   - Review and approve each message before sending
   - Record all outreach in `data/outreach.csv`

2. **Follow-up Outreach** (30 minutes)
   - Review `data/outreach.csv` for contacts who haven't responded
   - Ask the **Outreach** agent: "Help me create follow-up messages for these people"
   - Send follow-ups to 3-5 people (space them out)
   - Update status in `data/outreach.csv`

3. **Engagement** (20 minutes)
   - Respond to any messages received
   - Engage with posts from your network
   - Save important conversations to `records/messages/`

### Wednesday: Application Day

**Focus:** Apply to jobs and prepare application materials.

1. **Job Review** (15 minutes)
   - Review `data/jobs.csv` for open positions
   - Ask the **Application** agent: "Which jobs should I apply to this week?"
   - Select 2-3 high-priority jobs

2. **Application Preparation** (60 minutes)
   - For each selected job:
     - Ask the **Application** agent: "Help me tailor my CV/resume for this job"
     - Review the job description carefully
     - Customize your application materials
     - Prepare a tailored cover letter (if needed)
     - Save drafts in `records/jobs/`

3. **Application Submission** (30 minutes)
   - Ask the **Application** agent: "Review my application for [Job Title] at [Company]"
   - Get feedback and make final adjustments
   - **ALWAYS ASK FOR APPROVAL** before submitting
   - Update `data/jobs.csv` with application date and status

### Friday: Learning & Reflection

**Focus:** Improve your skills and reflect on the week.

1. **Interview Prep** (60 minutes)
   - Ask the **Interview Coach** agent: "Create a study plan for me based on my target roles"
   - Review `data/study.csv` for topics to study
   - Focus on:
     - Technical skills for your target roles
     - Behavioral interview questions
     - Company-specific knowledge
   - Add new study topics to `data/study.csv`

2. **Mock Interview** (30 minutes)
   - Ask the **Interview Coach** agent: "Conduct a mock interview for [target role]"
   - Practice answering common questions
   - Get feedback on your responses
   - Identify areas for improvement

3. **Weekly Review** (30 minutes)
   - Review all activities from the week
   - Ask the **Manager** agent: "How did I do this week? What should I improve?"
   - Update all CSV files with current status
   - Note what worked well and what didn't
   - Adjust `TARGETS.md` if needed

4. **Networking** (20 minutes)
   - Connect with 1-2 new people on LinkedIn
   - Engage with your network's content
   - Thank anyone who helped you this week

## Monthly Workflows

### First Monday of the Month: Strategy Review

**Focus:** Evaluate your overall strategy and make adjustments.

1. **Progress Review** (30 minutes)
   - Review all metrics from the past month
   - Ask the **Manager** agent: "How am I doing against my goals?"
   - Compare actual progress to your success metrics in `TARGETS.md`

2. **Target Review** (30 minutes)
   - Review and update `TARGETS.md`
   - Ask the **Researcher** agent: "Are there new industries or roles I should consider?"
   - Add new targets or remove ones that are no longer relevant

3. **Profile Update** (20 minutes)
   - Review and update `PROFILE.md`
   - Add any new skills, projects, or achievements to `PROOF.md`
   - Ensure your information is current and accurate

4. **System Maintenance** (15 minutes)
   - Clean up duplicate entries in CSV files
   - Archive old records
   - Organize `records/` folder
   - Back up your CareerOS folder

### Last Friday of the Month: Deep Dive

**Focus:** Conduct in-depth research and prepare for the next month.

1. **Industry Research** (45 minutes)
   - Pick one target industry from `TARGETS.md`
   - Ask the **Researcher** agent: "Do a deep dive on [industry] - trends, key companies, hiring patterns"
   - Save research in `records/` folder
   - Update `data/companies.csv` with new findings

2. **Company Deep Dives** (60 minutes)
   - Select 3-5 target companies
   - For each company:
     - Research their products, culture, and hiring process
     - Identify key people to connect with
     - Find recent news or funding announcements
     - Save research in `records/` folder
   - Add new contacts to `data/people.csv`

3. **Skill Gap Analysis** (30 minutes)
   - Ask the **Interview Coach** agent: "What skills am I missing for my target roles?"
   - Compare your skills in `PROOF.md` to job requirements
   - Create a plan to fill the gaps
   - Add new study topics to `data/study.csv`

## Ad-Hoc Workflows

### When You Find a New Company

1. Ask the **Researcher** agent: "Research [Company Name] - size, industry, recent news, hiring status"
2. Add the company to `data/companies.csv`
3. Identify key people to connect with
4. Add relevant contacts to `data/people.csv`
5. Save research in `records/` folder

### When You Find a New Job Posting

1. Ask the **Application** agent: "Evaluate this job posting against my profile"
2. Add the job to `data/jobs.csv`
3. If it's a good match, prepare application materials
4. Save the job description in `records/jobs/`

### When You Connect with Someone New

1. Add them to `data/people.csv`
2. Record the initial contact in `data/outreach.csv`
3. Save the conversation in `records/messages/`
4. Set a follow-up reminder

### When You Get an Interview

1. Ask the **Interview Coach** agent: "Create an interview prep plan for [Job Title] at [Company]"
2. Review the job description and company information
3. Add interview-specific study topics to `data/study.csv`
4. Schedule mock interviews
5. Save all prep materials in `records/jobs/`

### When You Need to Research Someone

1. Ask the **Researcher** agent: "Research [Person Name] at [Company] - role, background, recent activity"
2. Add them to `data/people.csv` if not already there
3. Note any useful information for outreach
4. Save research in `records/` folder
5. Never invent information - only use public, verifiable data

## Communication Guidelines

### How to Talk to Agents

1. **Be Specific** - Instead of "Find me jobs," say "Find me remote backend developer jobs in fintech"
2. **Provide Context** - Reference your files: "Based on my TARGETS.md, what should I focus on?"
3. **Ask for Options** - "Give me 3 options for outreach messages to this person"
4. **Request Explanations** - "Why do you recommend this approach?"
5. **Always Review** - Never let agents take action without your approval

### What to Expect from Agents

- **Manager:** Will coordinate and delegate, but won't do the work for you
- **Researcher:** Will find information, but won't invent or guess
- **Outreach:** Will create personalized messages, but you must review and approve
- **Application:** Will prepare materials, but you must review and submit
- **Interview Coach:** Will create prep plans, but you must do the studying

## Time Management Tips

1. **Batch Similar Tasks** - Do all outreach on the same day, all applications on another
2. **Set Time Limits** - Spend 30 minutes on research, not 3 hours
3. **Prioritize** - Focus on high-priority targets first
4. **Be Consistent** - Daily small efforts > sporadic large efforts
5. **Track Time** - Note how long tasks take to improve efficiency

## Quality Standards

1. **Personalization** - Every message should be tailored to the recipient
2. **Accuracy** - Never invent information or experience
3. **Professionalism** - All communications should be polished and error-free
4. **Value** - Every outreach should offer value to the recipient
5. **Follow-through** - Always follow up and follow through on commitments

---

**Remember:** This system works best when you use it consistently. The workflows are guidelines - adapt them to your needs and schedule.

*Last updated: [Add date when you update this file]*
