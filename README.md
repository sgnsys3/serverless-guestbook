# A serverless guestbook web application and API built with Cloud Functions

The application is a simple guestbook website where users can post messages. It demonstrates how to build a serverless web application where static content is hosted in a storage bucket (here it uses GitHub Pages) and the backend is implemented with Cloud Functions. API Gateway is used to expose the Cloud Functions for the web user interface.

Refer to [this tutorial](https://console.bluemix.net/docs/tutorials/serverless-api-webapp.html) for instructions.

## License

See [License.txt](License.txt) for license information.

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```
