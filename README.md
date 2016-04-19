# overview-form-example
This example demonstrate how to create an overview form that display business data for running or archived process instances.

Overview form includes a custom widgets to get process context independently of process state (running or achived).

The overview form display a simple business data value.

## Compatibility
This example has been created and built with Bonita BPM 7.2.2 Community edition.

It should be compatible with any newer version as well as Subscription edition.

## Known limitations
A first REST API call is needed to get the process instance state before getting the context. That's because two REST resources exist in order to get case context: one if process instance is running, one if process instance is archived.

## Issues
Reports issues and improvement request on GitHub tracker.
