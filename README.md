# WAF_Bypass
bypass WAF using dns history 
# Use the script like this:

bash bypass-firewalls-by-DNS-history.sh -d example.com

-d --domain: domain to bypass

-o --outputfile: output file with IP's

-l --listsubdomains: list with subdomains for extra coverage

-a --checkall: Check all subdomains for a WAF bypass

# Requirements (optional)
jq is needed to parse output to gather automatically subdomains. Install with apt install jq.

# For more detail information
https://github.com/vincentcox/bypass-firewalls-by-DNS-history
