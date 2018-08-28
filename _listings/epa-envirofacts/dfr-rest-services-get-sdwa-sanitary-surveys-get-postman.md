{
  "info": {
    "name": "U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility Report (DFR) Detailed Facility Report SDWA Sanitary Surveys Service",
    "_postman_id": "6e28e0f6-49fe-4831-97f1-a904a9131fd0",
    "description": "This procedure obtains data for the SDWA, Sanitary Surveys section of the DFR.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "da1a8f9b-7dc7-4190-a32d-20f1a7144597",
      "name": "this-procedure-obtains-data-for-air-compliance-in-the-environmental-conditions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_air_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Air Compliance in the Environmental Conditions Section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "bb75beb4-da75-4d8f-b231-45d8e965f719"
        }
      ]
    },
    {
      "id": "258b4ee3-2e2c-41eb-b8c6-6c56b0d44703",
      "name": "this-procedure-obtains-data-for-air-quality-in-the-environmental-conditions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_air_quality?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Air Quality in the Environmental Conditions Section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "10241c0d-052e-453f-a8e1-ac3d540321f2"
        }
      ]
    },
    {
      "id": "e960f79e-1d05-42e8-8565-59ec882fa18f",
      "name": "this-procedure-obtains-data-for-the-compliance-monitoring-history-5-years-in-the-enforcement-and-com",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_compliance_history?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Compliance Monitoring History (5 years) in the Enforcement and Compliance Section of the Detailed Facility report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "288c545c-2dd1-4c7b-ab5c-5dae04e78c1d"
        }
      ]
    },
    {
      "id": "4cb383a4-2e8c-4e70-8f12-0d9c6cc72b5c",
      "name": "this-procedure-obtains-data-for-compliance-summary-data-in-the-enforcement-and-compliance-section-of",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_compliance_summary?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Compliance Summary Data in the Enforcement and Compliance Section of the Detailed Facility report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "d1b127c8-3191-46cb-9296-22cbf65d9b2d"
        }
      ]
    },
    {
      "id": "4881e59c-446b-4844-b295-41398b0aed05",
      "name": "this-procedure-obtains-data-for-the-cwa-facilitylevel-status-section-located-in-the-three-year-compl",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_3yr_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Facility-Level Status section located in the Three Year Compliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows:\n> \"In Viol\" = Facility is in violation\n> \"No Viol\" = No violation found\n> \"Unk\" = Unknown status\n> \"SNC/Cat 1\" = SNC/Category I violation found"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "fc0bbf74-5215-43f5-b773-5a4834e892e6"
        }
      ]
    },
    {
      "id": "2cf0b445-c394-4f40-9f7a-6ba6794cd0d9",
      "name": "this-procedure-obtains-data-for-the-cwa-compliance-schedule-violations-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_cs_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Compliance Schedule Violations section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "0bb64a5d-bc13-4cf0-87d7-9c294531ae00"
        }
      ]
    },
    {
      "id": "61de057b-7c56-4747-982f-b0ae932f8247",
      "name": "this-procedure-obtains-data-for-the-cwa-pollutant-discharge-section-located-in-the-three-year-compli",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_eff_alr?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Pollutant Discharge section located in the Three Year Compliance Status by Quarter portion of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "cfafebe6-357e-445d-b968-ea33ba6f281a"
        }
      ]
    },
    {
      "id": "12858dd2-319a-4b62-9261-b8bfef5ec5e8",
      "name": "this-procedure-obtains-data-for-the-cwa-effluent-compliance-section-on-the-dfr---",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_eff_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Effluent Compliance section on the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "9acc6c8b-3b84-49d4-a454-682eafc3364e"
        }
      ]
    },
    {
      "id": "3852fa82-5c23-4c1b-9ebd-9125f3e2fa37",
      "name": "this-procedure-obtains-data-for-the-cwa-permit-schedule-violations-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_ps_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Permit Schedule Violations section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "1aa8df9a-476e-4aaf-8586-96f316cf7b83"
        }
      ]
    },
    {
      "id": "48663046-1f8d-49c5-92ea-cf70382ad464",
      "name": "this-procedure-obtains-data-for-the-cwa-sncrnc-history-section-located-in-the-three-year-ompliance-s",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_rnc_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA SNC/RNC History section located in the Three Year ompliance Status by Quarter portion of the DFR. Valid Compliance Statuses are as follows.\n> S = SNC/Category I - an enforcement action has been issued, and the facility is not meeting its compliance schedule\n> E = SNC/Category I - effluent violations of monthly average limits (Technical Review Criteria and chronic)\n> X = SNC/Category I - effluent violations of non-monthly average limits (Technical Review Criteria and chronic)\n> T = SNC/Category I - compliance schedule reporting violation\n> D = SNC/Category I - reporting violation - nonreceipt of DMR\n> N = RNC/Category II - reportable non-compliance\n> P = Resolved Pending - an enforcement action has been issued, and facility compliance with the action is pending final completion\n> R = Resolved - the facility has returned to compliance with its permit conditions, either with or without issuance of an enforcement action\n> C = Not considered in RNC/SNC based on manual review of data by state or EPA region. This manual override status is also indicated by a superscripted \"m\".\n> Blank = Not considered in RNC/SNC\n> N/A = EPA's data system is not able to determine the facility-level compliance status based upon the information available. This information may be available from a state database."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "38348611-3ca9-4726-9dfa-091b4b2c6683"
        }
      ]
    },
    {
      "id": "7cafc3ff-1613-4e38-be39-e03c04bcbf9c",
      "name": "this-procedure-obtains-data-for-the-cwa-single-event-violations-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_cwa_se_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the CWA Single Event Violations section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "2a64bad0-5e97-453d-9a8a-110968448a51"
        }
      ]
    },
    {
      "id": "679cacc5-771a-4f5e-a737-b8534d991164",
      "name": "returns-a-complex-object-with-demographics-from-the-2010-census-and-2010-american-community-survey-b",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_demographics?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Returns a complex object with Demographics from the 2010 Census and 2010 American Community Survey based on a 3 mile radius around the facility spatial coordinates."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "2a1de791-1fe0-4763-800f-be4024812090"
        }
      ]
    },
    {
      "id": "bf769a6e-66a0-4e7c-8d03-57b975b7ecea",
      "name": "this-procedure-is-the-overall-service-for-the-detailed-facility-report--it-returns-all-of-the-data-d",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_dfr?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure is the overall service for the Detailed Facility Report. It returns all of the data displayed in the DFR web report by invoking individual procedures that each return a targeted portion of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "d46fc9c3-bba8-4685-94f3-3bb11dfd65a3"
        }
      ]
    },
    {
      "id": "36d60735-a632-4d49-93a4-e876732b849b",
      "name": "this-procedure-obtains-data-for-the-enforcement-and-compliance-summary-in-the-facility-summary-secti",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_enforcement_summary?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Enforcement and Compliance Summary in the Facility Summary section of the Detailed Facility Report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "56ce18ad-ba2b-41b5-bbd6-6e6140b3c69d"
        }
      ]
    },
    {
      "id": "bedadd12-a475-4fe7-8c80-a399203d2a41",
      "name": "this-procedure-obtains-data-for-the-formal-enforcement-actions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_formal_actions?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Formal Enforcement Actions section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "4c61a9d8-9779-4478-8083-abc3afa791c1"
        }
      ]
    },
    {
      "id": "91a2e999-0dee-454a-9511-e8dee863c098",
      "name": "this-procedure-obtains-data-for-the-integrated-compliance-information-system-formal-enforcement-acti",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_icis_formal_actions?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Integrated Compliance Information System, Formal Enforcement Actions section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "af9d95f7-9d3a-4781-b57a-0deb17f41ace"
        }
      ]
    },
    {
      "id": "8c07719e-5cf8-427b-afbb-895798bcf30f",
      "name": "this-procedure-obtains-data-for-enforcement-and-compliance-summary-section-of-the-detailed-facility-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_inspections?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for Enforcement and Compliance Summary Section of the Detailed Facility report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "43dbcc98-d1b5-4ae9-8141-dbcf06d5093b"
        }
      ]
    },
    {
      "id": "482c10bb-d126-4662-8025-9ca82bbcee6e",
      "name": "returns-an-object-with-the-facilitys-latitude-and-longitude-coordinates-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_map?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Returns an object with the facility's latitude and longitude coordinates."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "831f958d-009e-4019-9113-5deec6519885"
        }
      ]
    },
    {
      "id": "0f8dff1f-3b1a-497a-9bf9-2a03dea159a5",
      "name": "this-procedure-obtains-data-for-the-facility-naics-codes-section-in-facilitysystem-characteristics-o",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_naics?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Facility NAICS Codes section in Facility/System Characteristics of the Detailed Facility Report."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "c4f33709-89c3-4656-9092-aa81082c46ae"
        }
      ]
    },
    {
      "id": "03b0871a-8725-4062-9c4d-18237adeffd7",
      "name": "this-procedure-obtains-data-for-the-permits-by-statute-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_nnnPermits?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Permits by Statute section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "d67dc6a7-0bcd-4917-9fe5-eb9ec351076b"
        }
      ]
    },
    {
      "id": "6ff57a20-f430-4bee-be7f-b83c6299ad09",
      "name": "this-procedure-obtains-data-for-the-noticesinformal-actions-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_notices?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the Notices/Informal Actions section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "6abb5acc-6627-4e8a-b7d8-a3d6e47e944d"
        }
      ]
    },
    {
      "id": "aeeb480e-d997-4bc2-879b-be5085c784dd",
      "name": "this-procedure-obtains-data-for-the-following-sections-of-the-detailed-facility-report--facility-inf",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_permits?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the following sections of the Detailed Facility Report.\n> Facility Information (FRS) in the Facility Summary.\n> Regulatory Interests in the Facility Summary.\n> Also Reports in the Facility Summary.\n> Facility/System Characteristics in Facility/System Characteristics.\n> Facility Contact Information in Facility/System Characteristics.\n> Facility SIC Codes in Facility/System Characteristics section.\n> Facility NAICS Codes in Facility/System Characteristics section."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "cff04e2a-b594-49b0-8341-435702c1fab6"
        }
      ]
    },
    {
      "id": "23503ca0-8c26-4815-8963-a0956ca5ea44",
      "name": "this-procedure-obtains-data-for-the-rcra-compliance-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_rcra_compliance?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the RCRA Compliance section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "ee067d69-a5cf-4528-9f6b-5145638e4ecc"
        }
      ]
    },
    {
      "id": "0c7561a7-ee18-4766-84f5-005069163d35",
      "name": "this-procedure-obtains-data-for-the-sdwa-lead-and-copper-rule-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_sdwa_lead_and_copper?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the SDWA, Lead and Copper Rule section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "fe33acdf-f8fa-4b1d-bc9e-5a3983a1e53c"
        }
      ]
    },
    {
      "id": "c1cecb60-5d02-4026-b631-94157144b26a",
      "name": "this-procedure-obtains-data-for-the-sdwa-sanitary-surveys-section-of-the-dfr-",
      "request": {
        "url": "http://ofmpub.epa.gov/echo/dfr_rest_services.get_sdwa_sanitary_surveys?No Name=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This procedure obtains data for the SDWA, Sanitary Surveys section of the DFR."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "2317a057-492b-49c6-84c0-11ab12d1eb99"
        }
      ]
    }
  ]
}