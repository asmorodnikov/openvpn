# openvpn
Installation guide for for OEL 7
sudo yum install oracle-epel-release-el7
yum-config-manager --enable repository ol7_developer_EPEL
git clone https://github.com/asmorodnikov/openvpn.git
cd openvpn-install.git
sudo sh ./openvpn-install.sh
