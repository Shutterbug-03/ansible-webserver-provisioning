# Ansible Web Server Provisioning

This repository contains Ansible playbooks and configurations to:

- Install Nginx
- Copy a static HTML page to `/var/www/html`
- Create a system user
- Restart Nginx when config or content changes
- Use variables, handlers, tags, and check mode
- (Bonus) Send a Slack/Webhook notification

## How to Use

```bash
ansible-playbook -i inventory.ini playbook.yml
