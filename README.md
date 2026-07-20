# keepalive-ping

Hourly-scheduled ping loop that triggers the notification endpoint of my personal
Master Tracker app (a private project). Runs a ~5.5h curl loop so notifications
keep flowing even when GitHub's scheduler is delayed. The endpoint secret lives
in Actions secrets, not in this repo.
