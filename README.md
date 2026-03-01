# Real Time Disease Monitor

Real-time disease outbreak monitoring platform with configurable alerting thresholds, interactive dashboards, and automated situation reports.

## Architecture

```
real-time-disease-monitor/
  src/           # Core modules
  tests/         # Unit and integration tests
  config/        # Configuration files
  docs/          # Documentation
```

## Modules

- **alert_engine**: Core alert engine functionality
- **signal_detector**: Core signal detector functionality
- **dashboard_builder**: Core dashboard builder functionality
- **report_generator**: Core report generator functionality
- **threshold_manager**: Core threshold manager functionality

## Quick Start

```bash
pip install -r requirements.txt
python -m real_time_disease_monitor.main
```

## Testing

```bash
pytest tests/ -v
```

## License

MIT License - see LICENSE for details.
