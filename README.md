# Measure Cron Delay

This repository is created to **measure the execution delay of GitHub Actions cron jobs**.

---

## Overview

- GitHub Actions cron jobs **do not always run exactly at the scheduled time**, and delays of a few seconds to several minutes can occur.
- Especially around **the 00 minute of each hour**, jobs are prone to congestion, which can increase delays.
- This repository runs jobs every minute within a specified time window and **logs the difference between the scheduled time and the actual execution time**.
