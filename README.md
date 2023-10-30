# :file_folder: PROJECT: API Trello - board name validation
Verification of REST API in Trello / create a new board with correct name (available characters and length) and E2E scenario.

[REST API Trello - documentation](https://developer.atlassian.com/cloud/trello/rest/api-group-actions/#api-group-actions)

## Collection #1 - P.1.Trello - board name tests [QueryParams]

[POST / Create a Board - documentation ](https://developer.atlassian.com/cloud/trello/rest/api-group-boards/#api-boards-post)

Endpoint: https://api.trello.com/1/boards

Required Query Params:
- name={name}
    - name (string)
    - 1 to 16384 characters long.
    - Min length: 1
    - Max length: 16384
- key=APIKey
- token=APIToken'

Report
