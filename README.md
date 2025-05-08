# Hybrid-ACO-RL-Task-assigner
# Task Scheduler Cheat Sheet

## Basic Commands

| Command | Description |
|---------|-------------|
| `python main.py` | Run with default settings |
| `python main.py --config config.json` | Use custom configuration |
| `python main.py --log-level INFO` | Set logging verbosity |

## Optimization Commands

| Command | Description |
|---------|-------------|
| `python main.py --optimize` | Run optimization (30 trials) |
| `python main.py --optimize --trials 50` | Run with 50 trials |
| `python main.py --optimize --log-level DEBUG` | Verbose optimization |

## Log Levels

| Level | Use Case |
|-------|----------|
| `DEBUG` | Show all details |
| `INFO` | Standard information |
| `WARNING` | Only warnings/errors |
| `ERROR` | Critical issues only |

## Common Combinations

| Command | Purpose |
|---------|---------|
| `python main.py --optimize --trials 100` | Thorough optimization |
| `python main.py --config output/optimized_config.json` | Use optimized parameters |

## Output Directories

| Directory | Contents |
|-----------|----------|
| `plots/` | Visualizations, charts, graphs |
| `output/` | Excel reports, JSON results |
| `logs/` | Log files (if configured) |

## Key Output Files

| File | Description |
|------|-------------|
| `output/assignment_report.xlsx` | Detailed results |
| `output/optimized_config.json` | Best parameters |
| `plots/dashboard.png` | Performance summary |
| `plots/gantt_*.png` | Task schedules |
