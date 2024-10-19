---
name: Bug Report
about: Bug Reporting.
title: "[BUG] ParaTronChat"
labels: bug
assignees: Maatijaa

---

name: Bug Report

description: Use this template to report a bug.

title: "[BUG] - [Question Summary]"

labels: bug

assignees: ''

body:
  - type: markdown
    attributes:
      value: |
        Thank you for reporting a bug! Please fill out the following information:

  - type: input
    id: server_version
    attributes:
      label: Server Version
      description: Please replace "Version" with your server version (i.e., Paper 1.21).
      placeholder: e.g., Paper 1.21

  - type: input
    id: title
    attributes:
      label: Title
      description: Provide a short summary of your question.
      placeholder: e.g., Plugin not loading


  - type: input
    id: plugin_version
    attributes:
      label: Plugin Version
      description: Use "/version ParaTronChat" to get the plugin version.
      placeholder: e.g., 1.0.0

  - type: textarea
    id: error_log
    attributes:
      label: Optional: Error Log
      description: If you are reporting a console error, upload relevant log excerpts to https://pastebin.com and paste the link here.
      placeholder: Paste your link here...
