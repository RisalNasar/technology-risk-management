# <p><strong><u>VPN (Virtual Private Network)</u></strong></p>
<p>A virtual private network (VPN) extends a private network across a public network, such as the Internet. It enables users to send and receive data across shared or public networks as if their computing devices were directly connected to the private network, and thus are benefiting from the functionality, security and management policies of the private network. A VPN is created by establishing a virtual point-to-point connection through the use of dedicated connections, virtual tunneling protocols, or traffic encryption.</p>
<p>A VPN spanning the Internet is similar to a wide area network (WAN). From a user perspective, the extended network resources are accessed in the same way as resources available within the private network. Traditional VPNs are characterized by a point-to-point topology, and they do not tend to support or connect broadcast domains. Therefore, communication, software, and networking, which are based on OSI layer 2 and broadcast packets, such as NetBIOS used in Windows networking, may not be fully supported or work exactly as they would on a local area network (LAN). VPN variants, such as Virtual Private LAN Service (VPLS), and layer 2 tunneling protocols, are designed to overcome this limitation.</p>
<p>VPNs allow employees to securely access the corporate intranet while traveling outside the office. Similarly, VPNs securely connect geographically separated offices of an organization, creating one cohesive network. VPN technology is also used by individual Internet users to secure their wireless transactions, to circumvent geo-restrictions and censorship, and to connect to proxy servers for the purpose of protecting personal identity and location.</p>
<p><span style="text-decoration: underline;"><strong>Why Use VPN?  What is the most frequent Use-Case of a VPN?</strong></span></p>
<p>Imagine you check-in into a hotel in China.  The hotel may provide a Wifi service.  The traffic from your phone/laptop may be easily eavesdropped by other "fellow" tourists or a criminal who might have embedded a sniffing tool within the hotel premises.  Over and above this scenario, the hotel may itself present a proxy server / gateway through which all internet traffic from the hotel rooms have to go through to be routed to the public Internet.  This proxy server is able to inspect all your unencrypted traffic.  Furthermore, some hotels might also do a Man-In-The-Middle for your SSL sessions (you are presented with an SSL certificate by the hotel's proxy server when you try to visit https://www.google.com/ for example).  This would result in the proxy server able to intercept and read all your SSL traffic.</p>
<p>The only safe way to protect yourself in such a scenario is to use a VPN service.  All the traffic originating from your mobile/laptop will be encrypted and sent to a secure remote proxy server for decryption and release into the Public Internet; Protected from the prying eyes and  ears in the hotel environment.</p>
<p><strong><u>OpenVPN</u></strong></p>
<p>OpenVPN is an open-source software application that implements virtual private network (VPN) techniques for creating secure point-to-point or site-to-site connections in routed or bridged configurations and remote access facilities. It uses a custom security protocol that utilizes SSL/TLS for key exchange. It is capable of traversing network address translators (NATs) and firewalls. It is published under the GNU General Public License (GPL).</p>
<p>OpenVPN allows peers to authenticate each other using a pre-shared secret key, certificates, or username/password. When used in a multiclient-server configuration, it allows the server to release an authentication certificate for every client, using signature and Certificate authority. It uses the OpenSSL encryption library extensively and contains many security and control features.</p>
<p><strong><u>VPN Services</u></strong></p>
<p>There are many VPN service providers to choose from.</p>
<p>An example - Private Tunnel VPN service is a commercial VPN service based on the OpenVPN platform.  They provide free VPN service for upto 500 MB.  Their charging model is based on the amount of data transferred rather than monthly recurring charges.  This business model of paying per GB could be a very useful asset for those that only need intermittent secure internet connections.</p>
<p><u>References:</u></p>
<p><a href="https://en.wikipedia.org/wiki/Virtual_private_network" target="_blank" rel="noopener">https://en.wikipedia.org/wiki/Virtual_private_network</a></p>
<p><a href="https://en.wikipedia.org/wiki/OpenVPN" target="_blank" rel="noopener">https://en.wikipedia.org/wiki/OpenVPN</a></p>
<p><a href="https://openvpn.net/index.php/open-source/333-what-is-openvpn.html" target="_blank" rel="noopener">https://openvpn.net/index.php/open-source/333-what-is-openvpn.html</a></p>
<p><a href="http://lifehacker.com/5940565/why-you-should-start-using-a-vpn-and-how-to-choose-the-best-one-for-your-needs" target="_blank" rel="noopener">http://lifehacker.com/5940565/why-you-should-start-using-a-vpn-and-how-to-choose-the-best-one-for-your-needs</a></p>
<p><a href="http://www.techradar.com/news/networking/wi-fi/why-you-should-avoid-hotel-wi-fi-like-the-plague-1292555/2" target="_blank" rel="noopener">http://www.techradar.com/news/networking/wi-fi/why-you-should-avoid-hotel-wi-fi-like-the-plague-1292555/2</a></p>