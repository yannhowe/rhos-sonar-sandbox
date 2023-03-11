```
oc project yannhowe-dev
oc new-app python:3.9-ubi8~https://github.com/yannhowe/rhos-sonar-sandbox
oc build status
oc start-build rhos-sonar-sandbox
oc describe service/rhos-sonar-sandbox
```