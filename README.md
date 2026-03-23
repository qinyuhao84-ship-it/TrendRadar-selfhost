# TrendRadar Selfhost

This repository is a standalone deployment of TrendRadar for daily DingTalk hotspot digests.

## What it does
- Runs on GitHub Actions every day at 09:00 Beijing time
- Collects multi-platform hot topics
- Pushes a morning digest to DingTalk

## Required GitHub Secret
- `DINGTALK_WEBHOOK_URL`
