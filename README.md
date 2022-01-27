fly --target main login --team-name main --concourse-url http://localhost:8080/ <br>
fly -t main set-pipeline --pipeline my-pipeline --config pipeline.yml <br>
fly -t main destroy-pipeline --pipeline my-pipeline --config pipeline.yml <br>
fly -t main intercept -j my-pipeline/unit <br>
