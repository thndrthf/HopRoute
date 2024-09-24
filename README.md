
HopRoute v2.0 beta
Release Date: 2024-09-25

Overview:
HopRoute is an advanced network mapping and traceroute tool designed to analyze network paths, provide hop-by-hop geolocation information, and display average connection times to a specified destination server. It supports both IPv4 and IPv6 addresses, performing in-depth tracing and delivering geographic details at each hop.

Key Features:
- Traceroute with GeoLocation: Perform IPv4 and IPv6 traceroutes to a destination server and fetch geolocation information for each hop, including city, region, country, and organization.
- End-to-End Network Mapping: Provides an end-to-end network map from the user's source IP address to the destination, including detailed connection times.
- IP Address and URL Resolution: Resolves both URLs and IP addresses (IPv4/IPv6) to help map the entire route.
- Average Connection Times: Returns the average connection time for multiple connection attempts to the destination server.
- Source IP Location Detection: Detects and displays the user’s public IP address and its associated geolocation information.
- Asynchronous Connections: Ensures efficient connection handling with asynchronous functions for server connections.

What's New in v2.0:
- IPv6 Support: Full support for traceroute and connection handling for both IPv4 and IPv6 addresses.
- GeoLocation Integration: Geolocation information for each hop along the traceroute path.
- Improved Error Handling: Better handling of invalid URLs and IP addresses, with informative error messages.
- Streamlined Connection: Improved connection time tracking and reporting.
- User-Friendly Interface: Simpler input prompts for IP, port number, and number of connection attempts.

System Requirements:
- Python 3.x
- Required Libraries:
  - scapy
  - requests
  - asyncio
  - socket

How to Use:
1. Run the program: The program begins by asking for the IP address or URL of the target destination.
2. Input port number: Enter the port number you wish to connect to.
3. Specify number of connections: Enter the number of connection attempts to calculate average connection time.
4. Traceroute Execution: The tool performs a traceroute to the destination and returns detailed hop-by-hop information, including geolocation for each hop.
5. Connection Times: After all connections are made, the average connection time is displayed.
6. Exit: Type 'exit' at any prompt to quit the program.
