curl -L \
  -X POST \
  -H "Accept: text/html" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  https://api.github.com/markdown \
  -d '{"text":"Hello **world**"}'
