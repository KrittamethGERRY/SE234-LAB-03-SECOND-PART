- **name** (string): `Bug Report`
- **description** (string): `File a bug report.`
- **title** (string): `[Bug]: `
- **labels** (array):
  - Item 1:
    `bug`
  - Item 2:
    `triage`
- **projects** (array):
  - Item 1:
    `octo-org/1`
  - Item 2:
    `octo-org/44`
- **assignees** (array):
  - Item 1:
    `octocat`
- **type** (string): `bug`
- **body** (array):
  - Item 1:
    - **type** (string): `markdown`
    - **attributes** (object):

```json
{
  "value": "Thanks for taking the time to fill out this bug report!\n"
}
```

- Item 2:
  - **type** (string): `input`
  - **id** (string): `contact`
  - **attributes** (object):

```json
{
  "label": "Contact Details",
  "description": "How can we get in touch with you if we need more info?",
  "placeholder": "ex. email@example.com"
}
```

    - **validations** (object):

```json
{
  "required": false
}
```

- Item 3:
  - **type** (string): `textarea`
  - **id** (string): `what-happened`
  - **attributes** (object):

```json
{
  "label": "What happened?",
  "description": "Also tell us, what did you expect to happen?",
  "placeholder": "Tell us what you see!",
  "value": "A bug happened!"
}
```

    - **validations** (object):

```json
{
  "required": true
}
```

- Item 4:
  - **type** (string): `dropdown`
  - **id** (string): `version`
  - **attributes** (object):

```json
{
  "label": "Version",
  "description": "What version of our software are you running?",
  "options": ["1.0.2 (Default)", "1.0.3 (Edge)"],
  "default": 0
}
```

    - **validations** (object):

```json
{
  "required": true
}
```

- Item 5:
  - **type** (string): `dropdown`
  - **id** (string): `browsers`
  - **attributes** (object):

```json
{
  "label": "What browsers are you seeing the problem on?",
  "multiple": true,
  "options": ["Firefox", "Chrome", "Safari", "Microsoft Edge"]
}
```

- Item 6:
  - **type** (string): `textarea`
  - **id** (string): `logs`
  - **attributes** (object):

```json
{
  "label": "Relevant log output",
  "description": "Please copy and paste any relevant log output. This will be automatically formatted into code, so no need for backticks.",
  "render": "shell"
}
```

- Item 7:
  - **type** (string): `checkboxes`
  - **id** (string): `terms`
  - **attributes** (object):

```json
{
  "label": "Code of Conduct",
  "description": "By submitting this issue, you agree to follow our [Code of Conduct](https://example.com).",
  "options": [
    {
      "label": "I agree to follow this project's Code of Conduct",
      "required": true
    }
  ]
}
```
