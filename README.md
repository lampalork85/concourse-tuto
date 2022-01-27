fly --target main login --team-name main --concourse-url http://localhost:8080/
fly -t main set-pipeline --pipeline my-pipeline --config pipeline.yml
fly -t main destroy-pipeline --pipeline my-pipeline --config pipeline.yml
