---
swagger: "2.0"
info:
  title: Consumer Surveys
  description: Creates and conducts surveys, lists the surveys that an authenticated
    user owns, and retrieves survey results and information about specified surveys.
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
  /mobileAppPanels/{panelId}:
    get:
      summary: Get Mobile App Panel
      description: Retrieves a MobileAppPanel that is available to the authenticated
        user
      operationId: consumersurveys.mobileapppanels.get
      parameters:
      - in: path
        name: panelId
        description: External URL ID for the panel
      responses:
        200:
          description: OK
      tags:
      - mobile application
definitions:
  FieldMask:
    properties:
      fields:
        description: This is a default description.
        type: parameters
      id:
        description: This is a default description.
        type: parameters
  MobileAppPanel:
    properties:
      country:
        description: This is a default description.
        type: parameters
      isPublicPanel:
        description: This is a default description.
        type: parameters
      language:
        description: This is a default description.
        type: parameters
      mobileAppPanelId:
        description: This is a default description.
        type: parameters
      name:
        description: This is a default description.
        type: parameters
      owners:
        description: This is a default description.
        type: parameters
  MobileAppPanelsListResponse:
    properties:
      requestId:
        description: This is a default description.
        type: parameters
      resources:
        description: This is a default description.
        type: parameters
  PageInfo:
    properties:
      resultPerPage:
        description: This is a default description.
        type: parameters
      startIndex:
        description: This is a default description.
        type: parameters
      totalResults:
        description: This is a default description.
        type: parameters
  ResultsGetRequest:
    properties: []
  ResultsMask:
    properties:
      fields:
        description: This is a default description.
        type: parameters
      projection:
        description: This is a default description.
        type: parameters
  Survey:
    properties:
      customerData:
        description: This is a default description.
        type: parameters
      description:
        description: This is a default description.
        type: parameters
      owners:
        description: This is a default description.
        type: parameters
      questions:
        description: This is a default description.
        type: parameters
      state:
        description: This is a default description.
        type: parameters
      surveyUrlId:
        description: This is a default description.
        type: parameters
      title:
        description: This is a default description.
        type: parameters
      wantedResponseCount:
        description: This is a default description.
        type: parameters
  SurveyAudience:
    properties:
      ages:
        description: This is a default description.
        type: parameters
      country:
        description: This is a default description.
        type: parameters
      countrySubdivision:
        description: This is a default description.
        type: parameters
      gender:
        description: This is a default description.
        type: parameters
      languages:
        description: This is a default description.
        type: parameters
      mobileAppPanelId:
        description: This is a default description.
        type: parameters
      populationSource:
        description: This is a default description.
        type: parameters
  SurveyCost:
    properties:
      costPerResponseNanos:
        description: This is a default description.
        type: parameters
      currencyCode:
        description: This is a default description.
        type: parameters
      maxCostPerResponseNanos:
        description: This is a default description.
        type: parameters
      nanos:
        description: This is a default description.
        type: parameters
  SurveyQuestion:
    properties:
      answerOrder:
        description: This is a default description.
        type: parameters
      answers:
        description: This is a default description.
        type: parameters
      hasOther:
        description: This is a default description.
        type: parameters
      highValueLabel:
        description: This is a default description.
        type: parameters
      images:
        description: This is a default description.
        type: parameters
      lastAnswerPositionPinned:
        description: This is a default description.
        type: parameters
      lowValueLabel:
        description: This is a default description.
        type: parameters
      mustPickSuggestion:
        description: This is a default description.
        type: parameters
      numStars:
        description: This is a default description.
        type: parameters
      openTextPlaceholder:
        description: This is a default description.
        type: parameters
  SurveyQuestionImage:
    properties:
      altText:
        description: This is a default description.
        type: parameters
      data:
        description: This is a default description.
        type: parameters
      url:
        description: This is a default description.
        type: parameters
  SurveyRejection:
    properties:
      explanation:
        description: This is a default description.
        type: parameters
      type:
        description: This is a default description.
        type: parameters
  SurveyResults:
    properties:
      status:
        description: This is a default description.
        type: parameters
      surveyUrlId:
        description: This is a default description.
        type: parameters
  SurveysDeleteResponse:
    properties:
      requestId:
        description: This is a default description.
        type: parameters
  SurveysListResponse:
    properties:
      requestId:
        description: This is a default description.
        type: parameters
      resources:
        description: This is a default description.
        type: parameters
  SurveysStartRequest:
    properties:
      maxCostPerResponseNanos:
        description: This is a default description.
        type: parameters
  SurveysStartResponse:
    properties:
      requestId:
        description: This is a default description.
        type: parameters
  SurveysStopResponse:
    properties:
      requestId:
        description: This is a default description.
        type: parameters
  TokenPagination:
    properties:
      nextPageToken:
        description: This is a default description.
        type: parameters
      previousPageToken:
        description: This is a default description.
        type: parameters
x-collection-name: Google Consumer Surveys
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