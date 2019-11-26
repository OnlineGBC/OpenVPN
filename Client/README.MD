How to downoad, install, start and stop Openvpn client

Download and Install OpenVPN full package from here:  https://openvpn.net/vpn-software-packages/

Copy server files:
    /etc/openvpn/ca.crt
    /etc/openvpn/easy-rsa/keys/client-certificate.crt
    /etc/openvpn/easy-rsa/keys/client-certificate.key 
to /etc/openvpn
sudo openvpn --config ./client.conf
Will prompt for user ID and pswd (vpn-user, openvpn w 2FA string added)
