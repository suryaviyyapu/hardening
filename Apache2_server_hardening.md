# Server Hardening checklist

Replace necessary files from your conf folder to implement hardening measures

### Security.conf (/etc/apache2/conf-enabled)
  - Limit HTTP Headers to GET, POST, HEAD
  - Disable directory Listing
  - System settings protection: AllowOverride
  -  Disable trace 
  -  Set HTTP, Secure flag to cookies (Requires mod_headers enabled)
  -  Set X-frame-options to SAMEORIGIN (Requires mod_headers enabled)
  