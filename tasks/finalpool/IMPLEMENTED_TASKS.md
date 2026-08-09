# Final Pool of Implemented Tasks

This directory contains all tasks implemented so far (i.e. their implementation satisfies the requirements from `tasks/examples/example-task`, as tracked in the Notion Task Tracker). Each implemented task (its full directory) is placed under `tasks/finalpool/<task-name>/`.

## Requirements (from tasks/examples/example-task)

- `docs/agent_system_prompt.md` — must be non-empty and all English (no Chinese)
- `docs/task.md` — must be non-empty and all English (no Chinese)
- `docs/user_system_prompt.md` — optional; if non-empty, must be all English
- `task_config.json` — if present, must have non-empty `needed_mcp_servers` and non-empty `needed_local_tools` containing `claim_done`
- `evaluation/main.py`, `preprocess/main.py`, `groundtruth_workspace/`, `initial_workspace/` — optional; only existence is checked

A task is **implemented** when it satisfies these requirements; otherwise it is **implementing**.

## Implemented tasks in this pool (30 total)

### Previously tracked implemented tasks (5)
- price-tracker (fan-dev)
- shipment-tracker (junteng_dev)
- expense-tracker (ruige)
- error-tracker (xiaochen_dev)
- task-scheduler (yuxuan-dev)

### New implemented tasks from the most recent commits (25)

#### fan-dev
- discount-calculator
- loyalty-program

#### gyy
- robots-handler
- sitemap-generator
- tag-manager

#### haoze
- media-organizer
- streaming-service

#### jl_dev
- customer-feedback-processor
- inventory-management

#### junteng_dev
- customer-portal
- help-desk

#### junxian_dev
- social-connector

#### lueyang-dev
- territory-manager
- client-portal

#### lv
- analytics-dashboard
- survey-builder

#### ruige
- log-analyzer
- web-crawler

#### wenshuo-dev
- cache-optimizer
- scheduler

#### xiaochen_dev
- health-monitor
- status-checker

#### yuxuan-dev
- sync-service

#### zhaochen
- certificate-manager
- storage-manager

## Excluded — still implementing (5)

- currency-converter (junxian_dev) — `docs/task.md` contains Chinese text
- insights-engine (lv) — `docs/agent_system_prompt.md` contains Chinese text
- audit-logger (yuzhen-dev) — `docs/agent_system_prompt.md` contains Chinese text
- resource-monitor (yuzhen-dev) — `docs/agent_system_prompt.md` contains Chinese text
- (unnamed task by yuxuan-dev) — task name is empty and files were committed at `tasks/yuxuan/` root instead of a task folder (malformed commit e82c829)

Note: `audit-logger/`, `insights-engine/` and `resource-monitor/` directories under `tasks/finalpool/` are stale leftovers from earlier (incorrect) runs and are NOT part of the implemented pool — they fail the English-only requirement above.
