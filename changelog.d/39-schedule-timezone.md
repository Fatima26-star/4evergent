Issue #39: schedule validation now evaluates cron fields in the selected
timezone before persisting the next run time, rather than using the host's
local timezone.
