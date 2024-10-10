# ARIN_query
Standalone function to query a list of IP addresses against arin.net and return a dictionary with ISP info for the IP addresses

Expects an IP address (ipAddress = list), and optional arin.net API key (apiKey = string).
Queries arin.net to obtain ISP names.
Returns a dictionary (output = {IPAddress:ISP}).
As of OCT.2024, arin.net allows for 10 queries per minute on a non API account
or 100 per minute on a free API account.

required library:
requests
