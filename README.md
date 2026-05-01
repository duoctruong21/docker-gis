Cài đặt Docker Desktop. <br>
Remove-Item -Recurse -Force "C:\ProgramData\DockerDesktop" <br>
winget source update <br>
winget install -e --id Docker .DockerDesktop <br>
Mở Terminal tại thư mục chứa file đó.<br>
Gõ lệnh: docker-compose up -d<br>
