# Dummy Data for JSON Server

This is just one json file with some dummy data, so I can play around in either React, Next or VSF2.
To change the data, just edit the file and overwrite the existing data with the new data.

### How to access the mockend?

  1. List your fake users with a GET request:
     curl https://mockend.com/org/repo/users
  2. Fake a creation with a POST
     (don't worry changes aren't persisted):
     curl https://mockend.com/org/repo/users \
     -X POST \
     -H "Content-Type: application/json" \
     --data '{"name": "alice"}'
  3. Access your GraphQL endpoint:
     https://mockend.com/org/repo/graphql

### More information:

Go to the docs: https://docs.mockend.com/
