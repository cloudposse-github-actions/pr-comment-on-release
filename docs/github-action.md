<!-- markdownlint-disable -->

## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| include\_regex | Only include releases whose tag name matches this regular expression. This regular expression should not include delimeters. i.e. instead of `/.\*/g`, supply only `.\*`. | .\* | false |
| retries | Number of retries. | 0 | false |
| tag | The git tag used to determine the release. If omitted, the release will be determined from `github.event.release.id`. | N/A | false |


## Outputs

| Name | Description |
|------|-------------|
| result | A JSON-encoded string which contains information on the comments it created (if any). |
<!-- markdownlint-restore -->
