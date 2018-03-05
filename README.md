This is a mock server which return a random result when receiving a http req.
Usage: ./HttpMock -f <config>

3 ways to loading data:
  1. LINE, each line is a result.
  2. WHOLE, reading all of the file as a result.
  3. CHUNK, several lines marked by [START,END] symble is a result.
