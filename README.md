# Proxy-Cache-Server
Cache web proxy server is an intermediate server between the client and the main server. The proxy server is used to reduce the bandwidth, latency and the server load. The cache web proxy server caches the client’s requests to the server. Each client request goes through the proxy server. The cache web proxy server responds to the client with the requested information if the files exist. If the cache web proxy doesn’t host the requested information, it talks to the server and fetches the requested information. The subsequent requests to that file will be handled by the cache web proxy server instead of the main server hosting the files. The cache web proxy server fetches the files from the main server until its buffer runs out. The server then deletes the files to make space for the new files.
