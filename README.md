<h1>Commands</h1>
<div class="copy-container rounded-4">
  <h4>Nginx Domain</h4>
  <pre><code id="copy-command">ansible-playbook playbook.yml --become --ask-become-pass -e "domain_name=DOMAIN_NAME app_port=PORT_HERE"</code></pre>
  <button class="copy-button" onclick="copyToClipboard()"></button>
  <h4>OpenVpn Server</h4>
  <pre><code id="copy-command">ansible-playbook playbook.yml --become --ask-become-pass -e "client_name=CLIENT_NAME"</code></pre>
  <button class="copy-button" onclick="copyToClipboard()"></button>
  <h4>Openvpn Client</h4>
  <pre><code id="copy-command">ansible-playbook playbook.yml --become --ask-become-pass -e "client_name=CLIENT_NAME openvpn_server_ip=SERVER_IP openvpn_port=PORT_HERE"</code></pre>
  <button class="copy-button" onclick="copyToClipboard()"></button>
</div>
