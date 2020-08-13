# parse-text


## To test API V1

    curl -X POST \
      http://127.0.0.1:9095/api/v1//parse \
      -H 'accept: application/json' \
      -H 'cache-control: no-cache' \
      -H 'content-type: application/json' \
      -d '{
    	"data":"JOHN0000MICHAEL0009994567"
    }'

## To test API V2

    curl -X POST \
      http://127.0.0.1:9095/api/v2/parse \
      -H 'accept: application/json' \
      -H 'cache-control: no-cache' \
      -H 'content-type: application/json' \
      -d '{
    	"data":"JOHN0000MICHAEL0009994567"
    }'
