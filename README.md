**Take heed: this package was originally meant for deploying our websites at SFI.ru. Take inspiration, but don't blindly copy!**

## Usage example

`ansible-playbook deploy.yml --extra-vars "REPOSITORY_URL=https://github.com/sfi-ru/ErmDistr HOST=your_target_host PORT=1234"`

## Environment Variables

|env_var|description|
|---|---|
|`REPOSITORY_URL`|Url of your git repository, possibly including github auth token for private repos|
|`HOST`|Host name of a target machine|
|`VERSION`|Git repository branch, commit SHA or release tag, defaults to master|
|`PORT`|Ssh port number on a target machine|
|`PROTOCOL`|Optional, defaults to `http`. Protocol to be used for testing.|
|`ES`|Optional, when set to true would automatically rebuild ES index on deployment, when one of NodeTypes.*.yaml have changed|

## Credit

Thanks to [Rens Admiraal](https://www.simplyadmire.com/) for initial inspiration!
