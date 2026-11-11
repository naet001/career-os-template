# CareerOS - Start Here

## Welcome to CareerOS

CareerOS is a simple, file-based career management system designed to help you find professional opportunities through cold outreach, build relationships, apply for jobs, and prepare for interviews—all by talking to AI agents.

## How This System Works

This is **not** an application. There is no frontend, backend, database, or dashboard. You interact with it through **natural language** by talking to AI agents that read and write to these files.

### The Core Idea

1. **You** talk to AI agents (like me)
2. **Agents** read and update the files in this workspace
3. **Files** store all your career data in a structured, portable format
4. **You** review and approve all actions before they happen

## Quick Start

### Step 1: Complete Your Profile

Start by filling out these files with your information:
- `PROFILE.md` - Your background, education, experience, and career interests
- `PROOF.md` - Your projects, skills, and achievements (be accurate)
- `TARGETS.md` - Your target roles, companies, industries, and people

### Step 2: Understand the Agents

This system has 5 specialized agents, each with a specific role:

| Agent | Role | When to Use |
|-------|------|-------------|
| **Manager** | Main entry point, coordinates everything | Start here, or when you need help deciding what to do |
| **Researcher** | Finds companies and people to connect with | When you need to identify targets or research contacts |
| **Outreach** | Creates personalized cold messages | When you want to reach out to someone |
| **Application** | Finds jobs and prepares applications | When you're applying to positions |
| **Interview Coach** | Prepares you for interviews | When you have an interview coming up |

### Step 3: Daily Workflow

1. **Talk to the Manager** - Start your session by asking the Manager agent what you should focus on
2. **Follow the prompts** - The Manager will guide you or delegate to the right agent
3. **Review everything** - Agents will always ask for approval before sending messages or applications
4. **Stay consistent** - Always check existing records before adding new ones

## File Structure Overview

```
careeros/
├── START_HERE.md          # This file - your guide
├── PROFILE.md             # Your professional background
├── PROOF.md               # Your skills, projects, achievements
├── TARGETS.md             # Your career targets
├── WORKFLOWS.md           # Daily activity instructions
│
├── agents/                # Agent instruction files
│   ├── manager.md         # Main coordinator
│   ├── researcher.md      # Finds targets
│   ├── outreach.md        # Creates messages
│   ├── application.md     # Job applications
│   └── interview-coach.md # Interview prep
│
├── data/                  # Structured data files
│   ├── companies.csv      # Companies you're targeting
│   ├── people.csv         # People you want to connect with
│   ├── outreach.csv       # Your outreach history
│   ├── jobs.csv           # Job opportunities
│   └── study.csv          # Interview study materials
│
└── records/               # Saved conversations and research
    ├── messages/          # Message history
    └── jobs/              # Job application records
```

## Important Rules

✅ **DO:**
- Fill out your profile completely and accurately
- Review all messages and applications before sending
- Keep your data files up to date
- Use the system consistently

❌ **DON'T:**
- Never let agents send messages without your approval
- Never let agents submit applications without your approval
- Never let agents invent experience or research findings
- Don't create duplicate entries

## Example Usage

### Finding a New Job

You: "I want to find a new job as a software engineer"

Manager: "I'll delegate this to the Researcher to find relevant companies and the Application agent to find job postings. First, let me check your TARGETS.md..."

### Reaching Out to Someone

You: "I found a founder I want to connect with"

Manager: "I'll have the Researcher look them up, then the Outreach agent can help you craft a personalized message."

### Preparing for an Interview

You: "I have an interview coming up"

Manager: "The Interview Coach will create a preparation plan based on the job description."

## Next Steps

1. **Read WORKFLOWS.md** - Understand the daily workflows
2. **Complete PROFILE.md** - Fill in your background
3. **Complete PROOF.md** - Document your skills and achievements
4. **Complete TARGETS.md** - Define your career goals
5. **Start talking to the Manager agent** - Begin using the system

## Tips for Success

- **Be specific** - The more details you provide, the better the agents can help
- **Review regularly** - Check your data files weekly for updates
- **Stay organized** - Use the records folder to save important conversations
- **Be patient** - Building relationships takes time

---

*Last updated: [Add date when you start using the system]*
