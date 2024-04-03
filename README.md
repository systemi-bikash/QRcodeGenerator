# For Running
## change your free port  
	http.ListenAndServe(":8000", nil)

## For running the app 
run the "go run main.go"

## for testing [you can use either postman or command below]
curl -X POST \
    --form "size=256" \
    --form "content=https://google.com" \
    --output data/qrcode.png \
    http://localhost:8080/generate
