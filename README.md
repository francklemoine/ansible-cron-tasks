
Cron tasks
----------
  - Connection = sudo user

	`ansible-playbook -i hosts --become --ask-become-pass --tags cron_tasks_timespe cron_install.yml`

	`ansible-playbook -i hosts --become --ask-become-pass --tags cron_tasks cron_install.yml`
