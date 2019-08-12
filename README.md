# DC/OS Prometheus Alert Rules

This repository is the DC/OS Prometheus alert rules used in work. 

## Severity Levels

Alerts should be configured at two severity levels, warning and critical:

- **`warning`** should be used for alerts which will be read by a human, but do not
require immediate action. They would, for example, trigger an email notification. 

- **`critical`** should be used for alerts which will immediately interrupt a human.
They would, for example, trigger a pager notification. 

## Related Projects

- https://github.com/dcos/grafana-dashboards
- https://github.com/dcos/telegraf

 