powershell administrator
PS C:\Users\Administrator> Get-Service -Name ssh-agent | Set-Service -StartupType Manual
PS C:\Users\Administrator> Start-Service ssh-agent


C:\Users\Administrator\.ssh>ssh-keygen -t ed25519 -C "1295185745@qq.com"
ssh-add c:\Users\Administrator\.ssh\id_ed25519

就可以git clone ssh的库链接
