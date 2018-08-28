---
swagger: "2.0"
x-collection-name: Reddit
x-complete: 0
info:
  title: Reddit Add Subreddit Delete Sr Icon
  description: Remove the subreddit&#39;s custom mobile icon.
  version: 1.0.0
host: www.reddit.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '{/r/subreddit}/delete_sr_icon':
    post&nbsp;:
      summary: Add Subreddit Delete Sr Icon
      description: Remove the subreddit&#39;s custom mobile icon.
      operationId: post&nbsp;RSubredditDeleteSrIcon
      x-api-path-slug: rsubredditdelete-sr-icon-postnbsp
      parameters:
      - in: query
        name: api_type
        description: the string json
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - ""
      - Sr
      - Icon
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---