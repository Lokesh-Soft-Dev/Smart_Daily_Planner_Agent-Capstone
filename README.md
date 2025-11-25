## Smart Daily Planner Agent — Capstone

**Track:** Concierge Agents  
**Author(s):** [Your name / team members]  
**Submission type:** Kaggle Notebook + GitHub Repo

## Project summary
A simple agent that organizes and schedules a user's daily tasks, prioritizes them, and outputs a clear time-based plan. Demonstrates ADK concepts: tool-calling, memory, and workflow orchestration.

## What you will find here
- `notebooks/SmartDailyPlanner.ipynb` — main notebook (link to Kaggle notebook)
- `adk_workflow.md` — ADK workflow & explanation
- `assets/` — demo GIFs and screenshots
- `submission.txt` — submission checklist & deadline

## Status

Initial implementation complete. To run the demo:

1. Open the Kaggle Notebook: `Smart Daily Planner Agent - Capstone`
2. Run the notebook cells from top to bottom.
3. Use the demo inputs in the notebook or open the saved JSON demo files in `assets/` (demo_study.json, demo_workday.json, demo_personal.json).
4. For submission, include the Kaggle notebook link and this GitHub repo.

Note: This demo uses simple local helper functions to emulate ADK tools and memory. Replace them with ADK APIs for the final polished submission if available.

## Demo Screencast Instructions (to be recorded before submission)

To create the final GIF:

1. Start screen recorder (Loom / OBS / Screencastify / built-in Windows recorder). 
2. Open the Kaggle notebook.  
3. Paste a short input into the demo cell.  
4. Run `run_agent()`.  
5. Show the printed schedule.  
6. Scroll to `assets/` folder to show saved `.json` demo files.  
7. Export the video as MP4 and convert to GIF (EZGIF.com).  
8. Save the GIF as `assets/agent_demo.gif`.

This GIF will be included in the final Kaggle submission + GitHub repo.

## Project Structure
```
smart-daily-planner-agent-capstone/
│
├── adk_workflow.md # ADK workflow logic & sequence
├── submission.txt # Submission checklist & metadata
├── README.md # Project overview + run instructions
│
├── notebooks/
│ └── info.txt # Kaggle notebook link placeholder
│
└── assets/
├── agent_demo.gif # Will contain screencast GIF before submission
└── placeholder.txt # Placeholder for empty folder
\`\`\`

## Important Links

- **Kaggle Notebook:** [Add your Kaggle Notebook URL here]
- **Competition Page:** https://www.kaggle.com/competitions/agents-intensive-capstone-project
- **Project Demo GIF:** Will be added before final submission

## Run Locally (Optional)

To run the notebook locally:

1. Clone this repository: git clone <your-repo-url>
2. Open the Kaggle notebook in your browser (recommended).
3. Or copy the code from the notebook into a local Jupyter Notebook.
4. Install dependencies: pip install notebook
5. Run all cells to generate schedules and demo outputs.

Note: Local run is optional — Kaggle Notebook is the main execution environment.


