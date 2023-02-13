# ISS-CW2 - TEAM NAME: KILO2

1. Adapt the VPN netkit laboratory, used during
the teaching sessions to represent your
organisation on the Internet.

2. Instantiate the x509 certificate authority
hierarchy.

3. Configure the necessary components to
achieve what you consider the most
appropriate VPN implementations.

4. Evaluate your VPN configurations against
each other.

5. Configure the necessary components to
achieve what you consider the most
appropriate HTTPS server configuration.

6. Provide assurance that the various
configurations work correctly.

7. Use your personal GPG keys appropriately.






### TO TEST THAT HTTPS IS WORKING FROM ANY MACHINE###
openssl s_client -connect www.kilo2.cyber.test:443 </dev/null 2>/dev/null | openssl x509 -inform pem -text
