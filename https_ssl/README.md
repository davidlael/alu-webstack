# HTTPS SSL

Web Infrastructure project: subdomain audit script, HAProxy SSL termination
with certbot, and HTTP to HTTPS 301 redirect.

- `0-world_wide_web`: Bash script that audits subdomains with dig and awk
- `1-haproxy_ssl_termination`: HAProxy config terminating SSL on port 443
- `2-redirect_http_to_https`: HAProxy config redirecting HTTP to HTTPS (301)
