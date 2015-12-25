**Take heed: this package is meant for deploying only our websites at SFI.ru. Take inspiration, but don't blindly copy!**

## Usage

### Deploy code in Surf-style

`ansible-playbook deploy.yml --extra-vars "REPOSITORY_URL=https://github.com/sfi-ru/ErmDistr HOST=your_target_host PORT=1234"`

### Sync persistent stuff

`ansible-playbook sync-persistent.yml --extra-vars "SOURCE_HOST=server.psmb.ru SOURCE_PORT=xxxx TARGET_HOST=localhost TARGET_PORT=xxxx" -i "i"`

## Credit

Thanks to [Rens Admiraal](https://www.simplyadmire.com/) for initial inspiration!
