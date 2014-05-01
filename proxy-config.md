git proxy config
============================
/etc/gitconfig or ~/.gitconfig or project/.gitconfig
> [http]
>>  proxy = http://127.0.0.1:8087

>>  sslVerify = false   # Close ssl verification when issue command, such as: git clone https://xxxxxx
                        # You should keep in mind that this setting must place in http section.
  
> [https]
>>  proxy = http://127.0.0.1:8087
