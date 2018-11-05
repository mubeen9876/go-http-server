# go-http-server

- defines the main package
- imports ther functions from net/http package

- main function:
  - it registers a new handler for every route we want using the http.HandleFunc. it represents 2 parameters:
      - the first is a string represents a path to match
      - the second is a function that will be executed to handle a request

- next thing will be to serve satic assets which will use http.FileServer from the net/http package
- will link to the static assets internal server and map URL path

- then need to accept the connection, allow listen and accept ioncoming connections
- using http.ListenAndServe including port 9000

- when typing the IP address with port 9000, it will display the index.html page
