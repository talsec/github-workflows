# Talsec GitHub Workflows

This repository contains the GitHub workflows which are reused across the Talsec repositories.

## Issue Watcher

The issue watcher workflow is used to automatically track state of the issue by labeling stale
issues with `stale` label and closing them after long period of inactivity.

### Variables

| Name                    | Type   | Description                                       | Required | Default value |
|-------------------------|--------|---------------------------------------------------|----------|---------------|
| day-before-issue-stale  | number | Number of days before an issue is marked as stale | ❌        | 14            |
| days-before-issue-close | number | Number of days before an issue is closed          | ❌        | 14            |
