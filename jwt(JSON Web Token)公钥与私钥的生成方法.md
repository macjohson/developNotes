RSA密钥生成
----------

>本操作在macOS环境下操作，linux下同理（未测试）

###私钥生成
	ssh-keygen -t rsa -b 2048 -f private.key
	
###公钥生成
	openssl rsa -in private.key -pubout -outform PEM -out public.key
	
	
	
>前后端分离，最常见的身份验证方式为jwt（JSON Web Token）,私钥用于生成token，公钥用于解密token