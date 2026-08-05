# ACC Academic Support Skill

## Overview
Comprehensive academic support for Austin Community College students pursuing Business Administration AAS degree.

## Capabilities
- Textbook concept explanation (Accounting, History, Business Systems)
- Study strategies and homework help
- Curriculum requirements and course planning
- GPA and progress tracking
- Exam preparation

## Usage

### Textbook & Concepts
```
Explain [concept]
Course info [code]
What is [topic]?
```

### Study & Homework
```
Study strategies
Exam prep [days_until_exam]
Homework tips [subject]
Help with [topic]
```

### Curriculum & Planning
```
Degree requirements
Semester plan
ACC resources
Course prerequisites
```

### Progress Tracking
```
Add course [code] [name] [credits] [grade]
Degree progress
Show transcript
Calculate GPA
```

## Knowledge Base

### Textbooks
- Horngren's Financial & Managerial Accounting (ACCT 1011)
- American Stories: A History of the United States, Volume 2 (HIST 1302)
- Connect Online Access (ITSC 1301)

### Accounting Concepts
Journal entry, double-entry bookkeeping, ledger, trial balance, financial statements, depreciation, accrual accounting, debit/credit rules, income statement, balance sheet

### History Concepts
Civil War, Reconstruction, Manifest Destiny, Industrial Revolution, Emancipation, social change

### Business Concepts
Information systems, management, marketing, economics, business ethics

### Study Techniques
- Active Recall: Test yourself without looking at notes
- Spaced Repetition: Review at intervals (1, 3, 7, 14, 30 days)
- Feynman Technique: Explain simply to find gaps
- Interleaving: Mix different topics while studying
- Cornell Notes: Organized note-taking
- Pomodoro: 25 min study, 5 min break

### Degree Requirements
**Business Administration AAS (60 credits)**
- General Education: 15 credits (English, History, Math, Psychology, elective)
- Core Business: 24 credits (Accounting I&II, Management, Marketing, IT, Economics)
- Electives: 21 credits

### Key Courses
- ACCT 1011: Financial Accounting I (4 cr)
- ACCT 1012: Managerial Accounting (4 cr)
- HIST 1302: American History II (3 cr)
- ENGL 1301: Composition I (3 cr)
- MATH 1314: College Algebra (4 cr)
- ITSC 1301: Business Information Systems (3 cr)
- MGMT 1319: Business & Society (3 cr)
- MKTG 1311: Introduction to Marketing (3 cr)
- ECON 2301: Microeconomics (3 cr)

### ACC Resources
- Main Campus: 3852 S. Leander Dr., Round Rock, TX 78665
- Phone: (512) 223-7000
- Website: www.austincc.edu
- MyACC Portal: myacc.austincc.edu
- Financial Aid: www.fafsa.ed.gov
- Academic Calendar: Fall (Aug-Dec), Spring (Jan-May), Summer (Jun-Jul)

## Configuration

### System Prompt
You are an ACC Academic Support Assistant for Austin Community College students.

You provide:
1. Textbook explanations - Break down complex concepts simply
2. Study guidance - Teach effective study techniques
3. Curriculum help - Explain degree requirements and course info
4. Progress tracking - Calculate GPA and degree progress
5. Homework support - Subject-specific tips and strategies

Respond conversationally, use real-world examples, connect concepts to Business Administration program.

### Context Parameters
- Student Program: Business Administration AAS
- Total Credits Required: 60
- Minimum GPA: 2.0
- Expected Duration: 2 years (4 semesters)
- Target Graduation: Spring 2026

### Knowledge Integration
- Accounting concepts tied to ACCT 1011/1012 textbooks
- History concepts from American Stories Volume 2
- Business systems from Connect platform
- All degree requirements for Business Administration AAS

## Integration Points

### With Textbooks
- Explains chapters and concepts from assigned books
- Connects theory to practice
- Provides study guides for major topics

### With Courses
- Supports homework in all Business Administration courses
- Explains prerequisites and course sequences
- Recommends optimal semester scheduling

### With Study
- Provides evidence-based study strategies
- Creates exam prep plans
- Gives subject-specific homework tips

### With Progress
- Tracks GPA calculation
- Monitors degree progress
- Generates transcripts and degree plans

## Files

- `SKILL.md` - This skill definition
- `ACC_BRAIN.txt` - Full knowledge base (can be imported as brain context)
- `acc_comprehensive_skill.py` - Python implementation

## Installation

### Method 1: Copy Brain Context
1. Open Odysseus settings
2. Find "Brain" or "System Prompt" section
3. Copy content from ACC_BRAIN.txt
4. Paste into brain field
5. Save

### Method 2: Import as Skill
1. In Odysseus, go to Skills/Tools
2. Click "Import Skill"
3. Select this folder or SKILL.md file
4. Configure system prompt
5. Activate

## Usage Examples

**Textbook Help:**
- "Explain what a journal entry is"
- "What's the difference between debit and credit?"
- "Help me understand the Civil War causes"

**Study Support:**
- "I have an exam in 5 days, create a study plan"
- "Homework tips for accounting problems"
- "What study technique works best for memorization?"

**Course Planning:**
- "What courses do I need for my degree?"
- "What are the prerequisites for Accounting II?"
- "Create a semester plan for me"

**Progress Tracking:**
- "Add course ACCT 1011 A 4 credits"
- "Show my degree progress"
- "Calculate my GPA"

## Data Storage

Skill can optionally track:
- Completed courses and grades
- Current GPA
- Credits completed
- Degree progress percentage

Data stored in: `/Users/tr3_4dams/odysseus/acc_skill_data.json`

## Support

For questions about:
- **ACC policies**: Check ACC website or MyACC portal
- **Financial aid**: Visit FAFSA.ed.gov or ACC Financial Aid office
- **Academic advising**: Contact ACC Advising at (512) 223-7000
- **Course content**: Use this skill or visit course professor during office hours

## Version
1.0 - Comprehensive ACC Academic Support Skill

## Author
Created for Austin Community College Business Administration program
