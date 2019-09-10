## ansible playbook examples

### using variables
ansible-playbook -e '@.vars.yml' -v update-expression-frontend.yml

- -e @.vars using file .vars.yml as varibles
- -v show detail
