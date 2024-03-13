After locally configuring /.ssh/config,

On the local terminal, run:

`ssh-keygen`

Keep pressing enter is fine.
`type $env:USERPROFILE\.ssh\id_rsa.pub | ssh ali@ali.local "cat >> .ssh/authorized_keys"`

or

`Get-Content $env:USERPROFILE/.ssh/id_rsa.pub | ssh ali@ali.local "cat >> .ssh/authorized_keys"`


Enter your remote pswd to the prompt.
Then simply run:

ssh ip or username@hostname You're in!