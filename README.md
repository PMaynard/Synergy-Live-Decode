Synergy Live Decode
===================

## Once completed
This displays Live decoding of any synergy traffic that is found on the network.

### Requires:
- Python (any)
- Python Libpcap (http://pylibpcap.sourceforge.net)

## Wireshark filter
- ip.src == 10.0.0.15 || ip.src == 10.0.0.12 && synergy.keypressed

## Notes
- http://www.wireshark.org/docs/wsdg_html_chunked/ChDissectAdd.html
- https://www.wireshark.org/docs/dfref/s/synergy.html
- http://anonsvn.wireshark.org/viewvc/trunk/epan/dissectors/packet-synergy.c?revision=39426&view=markup
