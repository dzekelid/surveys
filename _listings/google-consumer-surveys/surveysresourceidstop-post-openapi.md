---
swagger: "2.0"
x-collection-name: Google Consumer Surveys
x-complete: 0
info:
  title: Google Surveys API Stop Survey
  description: Stops a running survey.
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /consumersurveys/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /surveys:
    get:
      summary: Get Surveys
      description: Lists the surveys owned by the authenticated user.
      operationId: consumersurveys.surveys.list
      x-api-path-slug: surveys-get
      parameters:
      - in: query
        name: maxResults
      - in: query
        name: startIndex
      - in: query
        name: token
      responses:
        200:
          description: OK
      tags:
      - Survey
    post:
      summary: Create Survey
      description: Creates a survey.
      operationId: consumersurveys.surveys.insert
      x-api-path-slug: surveys-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Survey
  /surveys/{resourceId}/start:
    post:
      summary: Begin Survey
      description: Begins running a survey.
      operationId: consumersurveys.surveys.start
      x-api-path-slug: surveysresourceidstart-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceId
      responses:
        200:
          description: OK
      tags:
      - Survey
  /surveys/{resourceId}/stop:
    post:
      summary: Stop Survey
      description: Stops a running survey.
      operationId: consumersurveys.surveys.stop
      x-api-path-slug: surveysresourceidstop-post
      parameters:
      - in: path
        name: resourceId
      responses:
        200:
          description: OK
      tags:
      - Survey
  /surveys/{surveyUrlId}:
    delete:
      summary: Remove Survey
      description: Removes a survey from view in all user GET requests.
      operationId: consumersurveys.surveys.delete
      x-api-path-slug: surveyssurveyurlid-delete
      parameters:
      - in: path
        name: surveyUrlId
        description: External URL ID for the survey
      responses:
        200:
          description: OK
      tags:
      - Survey
    get:
      summary: Get Survey
      description: Retrieves information about the specified survey.
      operationId: consumersurveys.surveys.get
      x-api-path-slug: surveyssurveyurlid-get
      parameters:
      - in: path
        name: surveyUrlId
        description: External URL ID for the survey
      responses:
        200:
          description: OK
      tags:
      - Survey
    put:
      summary: Update Survey
      description: Updates a survey. Currently the only property that can be updated
        is the owners property.
      operationId: consumersurveys.surveys.update
      x-api-path-slug: surveyssurveyurlid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: surveyUrlId
        description: External URL ID for the survey
      responses:
        200:
          description: OK
      tags:
      - Survey
  /surveys/{surveyUrlId}/results:
    get:
      summary: Get Survey Results
      description: Retrieves any survey results that have been produced so far. Results
        are formatted as an Excel file. You must add "?alt=media" to the URL as an
        argument to get results.
      operationId: consumersurveys.results.get
      x-api-path-slug: surveyssurveyurlidresults-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: surveyUrlId
        description: External URL ID for the survey
      responses:
        200:
          description: OK
      tags:
      - Survey
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