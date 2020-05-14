# pydelighted

This is pydelighted, a python package to import your data from the delighted API


**--> example of the config.yaml file**

schema_prefix: my_delighted_schema
endpoints:
  survey_responses:
    table: 'responses'
    date_fields:
      - 'created_at'
      - 'updated_at'
  other_endpoint:
    date_fields:
      - 'date_field1'