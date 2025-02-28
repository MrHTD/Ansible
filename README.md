<h1>Commands</h1>
<div class="copy-container rounded-3">
  <h4>Complete Setup</h4>
  <pre><code id="copy-command">ansible-playbook Complete_Setup.yml --become --ask-become-pass"</code></pre>
  <button class="copy-button" onclick="copyToClipboard()"></button>
  
  <h4>Nginx Domain</h4>
  <pre><code id="copy-command">ansible-playbook Domain-Nginx.yml --become --ask-become-pass -e "domain_name=DOMAIN_NAME app_port=PORT_HERE"</code></pre>
  <button class="copy-button" onclick="copyToClipboard()"></button>
  
  <h4>OpenVpn Server</h4>
  <pre><code id="copy-command">ansible-playbook OpenVPN.yml --become --ask-become-pass -e "client_name=CLIENT_NAME"</code></pre>
  <button class="copy-button" onclick="copyToClipboard()"></button>
  
  <h4>Openvpn Client</h4>
  <pre><code id="copy-command">ansible-playbook openvpn_client.yml --become --ask-become-pass -e "client_name=CLIENT_NAME openvpn_server_ip=SERVER_IP openvpn_port=PORT_HERE"</code></pre>
  <button class="copy-button" onclick="copyToClipboard()"></button>
</div>
