CONFIG_JSON


{   "log": {     "loglevel": "warning"   },   "inbound": {     "protocol": "vmess",     "port": 8080,     "settings": {       "clients": [         {           "id": "459352e1-cd4d-4384-93f9-1709746b9d7c",           "alterId": 64,           "security": "aes-128-cfb"         }       ]     },     "streamSettings": {       "network": "ws"     }   },   "inboundDetour": [],   "outbound": {     "protocol": "freedom",    "settings": {}   } }
