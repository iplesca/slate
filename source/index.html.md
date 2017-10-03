--- 

title: GeoPal API 

language_tabs: 
   - shell 

toc_footers: 
   - <a href='#'>Sign Up for a Developer Key</a> 
   - <a href='https://github.com/lavkumarv'>Documentation Powered by lav</a> 

includes: 
   - errors 

search: true 

--- 

# Introduction 

geopal desc 

**Version:** 1-oas3 

# /JOBS/CREATE
## ***POST*** 

**Summary:** Create a new job

**Description:** Create a new GeoPal job

### HTTP Request 
`***POST*** /jobs/create` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| template_id | query | An existing JobTemplate ID | Yes |  |
| job_identifier | query | Associate a specific job identifier value. | Yes |  |
| asset_identifier | query | An existing Asset Identifier value. | No |  |
| person_id | query | An existing Contact id value. | No |  |
| person_identifier | query | . | No |  |
| person_title | query | . | No |  |
| person_first_name | query | . | No |  |
| person_last_name | query | . | No |  |
| person_email | query | . | No |  |
| person_phone_number | query | . | No |  |
| person_fax_number | query | . | No |  |
| person_mobile_number | query | . | No |  |
| person_address_line_1 | query | . | No |  |
| person_address_line_2 | query | . | No |  |
| person_address_line_3 | query | . | No |  |
| person_city | query | . | No |  |
| person_postal_code | query | . | No |  |
| address_id | query | . | No |  |
| address_identifier | query | . | No |  |
| address_line_1 | query | . | No |  |
| address_line_2 | query | . | No |  |
| address_line_3 | query | . | No |  |
| city | query | . | No |  |
| postal_code | query | . | No |  |
| country_id | query | . | No |  |
| customer_id | query | . | No |  |
| customer_name | query | . | No |  |
| customer_phone_number | query | . | No |  |
| customer_fax_number | query | . | No |  |
| customer_web_site | query | . | No |  |
| customer_mobile_number | query | . | No |  |
| customer_email | query | . | No |  |
| customer_address_line_1 | query | . | No |  |
| customer_address_line_2 | query | . | No |  |
| customer_address_line_3 | query | . | No |  |
| customer_city | query | . | No |  |
| customer_postal_code | query | . | No |  |
| asset_identifier | query | . | No |  |
| estimated_duration | query | . | No |  |
| rate_per_hour | query | . | No |  |
| preffered_start_date_time | query | . | No |  |
| preffered_stop_date_time | query | . | No |  |
| priority_text | query | . | No |  |
| priority_color | query | . | No |  |
| job_assets | query | . | No |  |
| job_notes | query | . | No |  |
| force_unique_job_identifier_if_set | query | . | No |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | A JSON array of user namess |

<!-- Converted with the swagger-to-slate https://github.com/lavkumarv/swagger-to-slate -->
