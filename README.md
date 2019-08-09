# Composer Language Server

## Getting started

1. Clone project
2. Import as Gradle project into Eclipse
3. Open command line in project folder and run following commands:

```sh
.\gradlew.bat clean build
cd monaco-editor-lsp-example
npm install
```

4. Run the `main`-method in the class `RunWebSocketServer3.xtend` in the subproject in Eclipse
5. On the command line start the frontend with the Monaco Editor:

```sh
npm run serv
```

After that your browser will open up `localhost:8080` with a running Monaco Editor which is connected with the port 4389. See the network tab in the Chrome developer tools for more information regarding the messages which are sent between the client and the server.
