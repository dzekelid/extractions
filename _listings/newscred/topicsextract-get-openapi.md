---
swagger: "2.0"
x-collection-name: NewsCred
x-complete: 0
info:
  title: News Cred Extract Related Topics
  description: Returns a list of topics extracted from the input query.
  version: v1
host: api.newscred.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  topics/extract/:
    get:
      summary: Extract Related Topics
      description: Returns a list of topics extracted from the input query.
      operationId: getTopicsExtract
      x-api-path-slug: topicsextract-get
      parameters:
      - in: query
        name: access_key
        description: Unique API access key
      - in: query
        name: query
        description: The string to extract topics from
      - in: query
        name: topics
        description: List of topics to retrieve items from
      - in: query
        name: topic_classifications
        description: Limit results to those with the specified topic classification
      - in: query
        name: topic_filter_mode
        description: Enables topic_filter_name and indicates filtering type
      - in: query
        name: topic_filter_name
        description: Limit items to a predefined list of topics
      - in: query
        name: topic_subclassifications
        description: Limit results to those with the specified topic sub-classification
      responses:
        200:
          description: OK
      tags:
      - News
      - Topics
      - Extract
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