
# Dry Run 

## Summary

Dry-run is a new feature that we intend to implement in the api-server. The goal
is to be able to send requests to modifying endpoints, and see if the request
would have succeeded (admission chain, validation, merge conflicts, ...) and/or
what would have happened without having it actually happen. The response body
for the request should be as close as possible to a non dry-run response.
