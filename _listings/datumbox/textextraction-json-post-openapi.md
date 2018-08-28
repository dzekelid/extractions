---
swagger: "2.0"
x-collection-name: Datumbox
x-complete: 0
info:
  title: Datumbox Extracts the clear text from Webpage
  description: The Text Extraction function enables you to extract the important information
    from a given webpage. Extracting the clear text of the documents is an important
    step before any other analysis.
  version: 1.0.0
host: api.datumbox.com
basePath: 1.0/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /KeywordExtraction.json:
    post:
      summary: Extracts the Keywords of the Document
      description: The Keyword Extraction function enables you to extract from an
        arbitrary document all the keywords and word-combinations along with their
        occurrences in the text.
      operationId: KeywordExtraction
      x-api-path-slug: keywordextraction-json-post
      parameters:
      - in: formData
        name: "n"
        description: The number of keyword combinations (n-grams) that you wish to
          extract
      - in: formData
        name: text
        description: The text that you want to analyze
      responses:
        200:
          description: OK
      tags:
      - Keyword
      - Extraction
  /TextExtraction.json:
    post:
      summary: Extracts the clear text from Webpage
      description: The Text Extraction function enables you to extract the important
        information from a given webpage. Extracting the clear text of the documents
        is an important step before any other analysis.
      operationId: TextExtraction
      x-api-path-slug: textextraction-json-post
      parameters:
      - in: formData
        name: text
        description: The HTML source of the webpage
      responses:
        200:
          description: OK
      tags:
      - Text
      - Extraction
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