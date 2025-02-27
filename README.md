Documentation for building

authenticate google account and store id in session: POST -> /google/auth?idToken=" token credential here "



access webscraping tool: POST -> /scrape?url=" enter url link here "

access news generation tool: GET -> /getnews?symbol=" enter stock symbol here "




get s3 bucket data: GET -> /s3/retrieve?id=" enter item object key here (without prefix and type) "


get sentiment: POST-> /analyze-sentiment?key=" enter key to item in s3 bucket "





FOR FUNCTIONS INVOLVING SYMBOLS, INCLUDE SET-COOKIE: JSESSIONID (should be auto included if allow credentials)

retrieve all symbols: GET -> /getsymbols

add a symbol: POST -> /add?symbol=" enter stock symbol here "

delete a symbol DELETE -> /delete?symbol=" enter stock symbol here "