# github-actions-test

To try out repository dispatch:

curl   -X POST   -H "Accept: application/vnd.github+json"   -H "Authorization: Bearer xxxx"  -H "X-GitHub-Api-Version: 2022-11-28"   https://api.github.com/repos/dmchughaxway/github-actions-test/dispatches   -d '{"event_type":"build","client_payload":{"env":"production"}}'
