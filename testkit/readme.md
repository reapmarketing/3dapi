# Send a test request

	curl --header "content-type: text/soap+xml; charset=utf-8" --data @request.xml http://162.243.103.153:3000/api

# Sends a test response

	curl --header "content-type: text/soap+xml; charset=utf-8" --data @response.xml http://162.243.103.153:3000/api