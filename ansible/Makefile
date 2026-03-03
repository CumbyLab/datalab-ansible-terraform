all:
	ansible-playbook -v -i inventory.yml --ask-vault-pass playbook.yml -kK

deploy:
	ansible-playbook -v -i inventory.yml --ask-vault-pass playbook.yml -kK --tags="deploy"

setup:
	ansible-playbook -v -i inventory.yml --ask-vault-pass playbook.yml -kK --tags="setup"

maintenance:
	ansible-playbook -v -i inventory.yml --ask-vault-pass playbook.yml -kK --tags="maintenance"

borg:
	ansible-playbook -v -i inventory.yml --ask-vault-pass playbook.yml -kK --tags="borg"

ssl:
	ansible-playbook -v -i inventory.yml --ask-vault-pass playbook.yml -kK --tags="ssl"

datalab_scraper:
	ansible-playbook -v -i inventory.yml --ask-vault-pass playbook.yml -kK --tags="datalab_scraper"
