This is a sample experiment and metrics configuration for an SLO validation for a KFServing model.

Please note the `namespace_name`, and `startingTime` in the `collect-metrics-database` task in the experiment configuration.

Also note that `elapsedTimeSeconds` is not intended to be set by the user. It is calculated from `startingTime`.

To run the experiment:

```bash
iter8 run
```

After running the experiment, to check the metrics:

```bash
iter8 report
```

Or:

```bash
iter8 report -o html > report.html 
```

... and view the report in a browser.