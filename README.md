# headerdebug
quick binary that can be pushed to CF to show http headers and values
cf push testheaders -c './headers' -b binary_buildpack

Go Router should be setting X-Forwarded-Proto - http or https