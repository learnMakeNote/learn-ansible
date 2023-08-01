# learn-ansible

1. run
   - `ansible-playbook install_apache.yml`
2. debug
   - `ansible all -m gather_facts --limit 52.188.208.196 | grep ansible_distribution`
3. show tags
   - `ansible-playbook --list-tags site.yml `
   - `ansible-playbook --tags "db,web" site.yml`
     `
