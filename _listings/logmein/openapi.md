swagger: "2.0"
x-collection-name: LogMeIn
x-complete: 1
info:
  title: GoToWebinar API
  description: todo-add-description
  version: 1.0.0
host: api.getgo.com
basePath: /G2W/rest/organizers
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{organizerKey}/webinars/{webinarKey}/sessions/{sessionKey}/surveys:
    get:
      summary: Get session surveys
      description: Get session surveys.
      operationId: WebinarsSessionsSessionKeySurveysByOrganizerKeyAndWebinarKeyGet
      x-api-path-slug: organizerkeywebinarswebinarkeysessionssessionkeysurveys-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: organizerKey
      - in: path
        name: sessionKey
      - in: path
        name: webinarKey
      responses:
        200:
          description: OK
      tags:
      - Session
      - Surveys
  /{organizerKey}/webinars/{webinarKey}/sessions/{sessionKey}/attendees/{registrantKey}/surveys:
    get:
      summary: Get attendee survey answers
      description: Get attendee survey answers.
      operationId: WebinarsSessionsSessionKeyAttendeesRegistrantKeySurveysByOrganizerKeyAndWebinarKeyGet
      x-api-path-slug: organizerkeywebinarswebinarkeysessionssessionkeyattendeesregistrantkeysurveys-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: organizerKey
      - in: path
        name: registrantKey
      - in: path
        name: sessionKey
      - in: path
        name: webinarKey
      responses:
        200:
          description: OK
      tags:
      - Attendee
      - Survey
      - Answers