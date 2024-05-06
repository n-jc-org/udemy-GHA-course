for section 2:21

the cURL 

curl -L \
  -X POST \
  -H "Accept: application/vnd.github+json" \
  -H "Authorization: Bearer <PUT_TOKEN_HERE>" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  https://api.github.com/repos/n-jc-org/udemy-GHA-course/actions/workflows/manually-triggered.yaml/dispatches \
  -d '{"ref":"main","inputs":{"string":"from the REST API","environment":"production"}}'


  TODO: work out how to do above with xh