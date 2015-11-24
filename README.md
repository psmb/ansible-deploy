**Take heed: this package is meant for deploying only our websites at SFI.ru. Take inspiration, but don't blindly copy!**

# Usage

### Deploy code in Surf-style

`ansible-playbook deploy.yml --extra-vars "REPOSITORY_URL=https://github.com/sfi-ru/ErmDistr HOST=your_target_host PORT=1234"`

### Initial setup: copy resources and import db

`ansible-playbook destructive-deploy-persistent.yml --extra-vars "HOST=your_target_host PORT=1234"`
