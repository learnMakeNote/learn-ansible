# learn-ansible

1. run
   - `ansible-playbook -v install_apache.yml`
   - `ansible-playbook -v site.yml`
2. debug
   - `ansible all -m gather_facts --limit 52.188.208.196 | grep ansible_distribution`
3. show tags
   - `ansible-playbook --list-tags site.yml `
   - `ansible-playbook -v --tags "db,web" site.yml`
     `
