BUG_Author:
       YE jia xing
Affected version:
      Contec SolarView Compact <6.00
Vendor:
      https://www.contecinc.com/

Vulnerability File:
      downloader.php
      Description:
Attacker exploit the vulnerability through downloader.php? The file parameter reads sensitive files through the directory pass.
![图片](https://github.com/Yobing1/SolarView-vuln-/assets/135513064/d1758aef-dc42-4d37-9f17-f4eb8324d90b)
downloader.php?file Existential directory traversal
It can read the sensitive file /etc/password 
![图片](https://github.com/Yobing1/SolarView-vuln-/assets/135513064/1d625d56-611e-4854-a3b1-4be2c106631c)
The password hash of the root administrator can be used to crack it
![图片](https://github.com/Yobing1/SolarView-vuln-/assets/135513064/c392da59-c285-4c28-98dd-ff29160b688c)

