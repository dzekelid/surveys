---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) Detailed Facility Report SDWA Sanitary Surveys Service
  description: This procedure obtains data for the SDWA, Sanitary Surveys section
    of the DFR.
  contact:
    name: US EPA, OECA Integration, Targeting and Access Branch
  version: 0.0.0
host: ofmpub.epa.gov
basePath: /echo
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /dfr_rest_services.get_sdwa_sanitary_surveys:
    get:
      summary: Detailed Facility Report SDWA Sanitary Surveys Service
      description: This procedure obtains data for the SDWA, Sanitary Surveys section
        of the DFR.
      operationId: this-procedure-obtains-data-for-the-sdwa-sanitary-surveys-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-sdwa-sanitary-surveys-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - SDWA
      - Sanitary
      - Surveys
      - Service
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