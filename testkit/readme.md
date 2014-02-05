# Send a test request

	curl --header "content-type: text/soap+xml; charset=utf-8" --data @request.xml http://taylor.stand.sh/api

# Sends a test response

	curl --header "content-type: text/soap+xml; charset=utf-8" --data @response.xml http://taylor.stand.sh/api