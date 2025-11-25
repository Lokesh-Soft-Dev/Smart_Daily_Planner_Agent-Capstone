# ADK Workflow — Smart Daily Planner Agent

## Overview
This file maps the Smart Daily Planner Agent logic to ADK concepts: tools, memory, and workflow orchestration. It is a blueprint used during implementation and for the final submission description.

## ADK Components Used
1. **Tool Calling**
   - Tools: `task_parser_tool`, `time_slot_tool`, `priority_tool`
   - Purpose: small helpers to parse durations, suggest time slots, and normalize priorities.

2. **Memory**
   - Memory store: simple user preferences (wake-up time, preferred work hours, recurring tasks).
   - Purpose: remember user's routine across sessions (demo with ADK memory API).

3. **Workflow Orchestration**
   - Steps:
     1. Receive input (text list of tasks).
     2. Call `task_parser_tool` to split tasks and extract durations/priorities.
     3. Call `priority_tool` to assign priorities when missing.
     4. Call `time_slot_tool` to suggest available time slots (starting 08:00 default).
     5. Assemble final schedule and store any preferences in memory.

## Example flow (high-level)
User input -> task_parser_tool -> priority_tool -> time_slot_tool -> assemble schedule -> save user prefs to memory -> output schedule

## Notes for implementation
- Tools can be implemented as local Python helper functions in the Kaggle notebook for demo (no external API needed).
- Memory can be emulated with a JSON file or Python dict for the Kaggle demo — for ADK showcase, call the ADK Memory API (or show placeholder calls).
- Keep the notebook cells small and well-commented so judges see the mapping clearly.
