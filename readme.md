- download sink connector
- create source.json
- call api using
    curl -i -X POST -H "Accept:application/json" -H  "Content-Type:application/json" http://localhost:8083/connectors/ -d @source.json

    curl -i -X POST -H "Accept:application/json" -H  "Content-Type:application/json" http://localhost:8083/connectors/ -d @sink.json

    curl -X DELETE http://localhost:8083/connectors/<connector-nam>