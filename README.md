pwnacle-fusion
==============

Automated exploit for Oracle Reports, CVE-2012-3153 / CVE-2012-3152

Credits to @miss_sudo for the disclosure

Usage: ./pwnacle.rb target_url payload_url

This exploit uses both CVEs to upload a .jsp shell from your payload_url which is then reachable from /reports/images/<shell>.jsp

payload_url should contain a .jsp payload but it could be anything really with some modification.
