# status

[status.dotsbox.com](https://status.dotsbox.com): the status of the sites dotsbox hosts, checked
every 5 minutes from GitHub Actions by [Upptime](https://upptime.js.org).

- `main` (this branch) holds the settings (`upptime.base.json`) and the workflow
  (`.github/workflows/upptime.yml`, which says how it works). It changes only through pull requests.
- `master` holds Upptime's data (each site's history, response times, graphs), written by the
  workflow. Don't edit it.
- The sites aren't listed here: they come from the org variable `STATUS_SITES`, which the platform
  repo writes from its site records. A site that goes live appears by itself.
- An outage opens an issue here (and closes it when the site is back). It assigns and notifies
  nobody: alerting is Grafana Cloud's job.
