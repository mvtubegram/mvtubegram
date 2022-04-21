{
  "Version": "1.0.2",
  "ReleaseNotes": "NOVAS CONFIGURAÇŌES",
  "UrlUpdate": "https://raw.githubusercontent.com/mvtubegram/mvtubegram/main/README.md",
  "Sms": "https://kiritosshxd.github.io/Conecta4g_site/UrlSms",
  "EmailFeedback": "mvtubegram@gmail.com",
  "UrlContato": "https://t.me/mvtubegram",
  "UrlTermos": "https://kiritosshxd.github.io/Conecta4g_site/termos.html",
  "CheckUser": "true",
  "Udp": [
    {
      "Porta": "7300"
    },
    {
      "Porta": "7400"
    },
    {
      "Porta": "7500"
    },
    {
      "Porta": "7500"
    },
    {
      "Porta": "7700"
    }
  ],
  "Servers": [
    {
      "Name": "SERVIDOR 1 | MVTUBEGRAM5G",
      "TYPE": "premium",
      "FLAG": "br.png",
      "ServerIP": "serv1.mvtubenet.online",
      "CheckUser": "http://serv1.mvtubenet.online:5454/checkUser",
      "ServerPort": "443",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    },
    {
      "Name": "SERVIDOR 2 | MVTUBEGRAM5G,
      "TYPE": "premium",
      "FLAG": "br.png",
      "ServerIP": "serv2.mvtubenet.online",
      "CheckUser": "http://serv2.mvtubenet.online:8989/checkUser",
      "ServerPort": "443",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    },
    {
      "Name": "SERVIDOR 3 | MVTUBEGRAM5G,
      "TYPE": "premium",
      "FLAG": "br.png",
      "ServerIP": "serv3.mvtubenet.online",
      "CheckUser": "http://serv3.mvtubenet.online:8989/checkUser",
      "ServerPort": "443",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    },
    {
      "Name": "SERVIDOR 4 | MVTUBEGRAM5G,
      "TYPE": "premium",
      "FLAG": "br.png",
      "ServerIP": "serv4.mvtubenet.online",
      "CheckUser": "http://serv4.mvtubenet.online:8989/checkUser",
      "ServerPort": "443",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    }
  ],
  "Networks": [
    {
      "Name": "VIVO PROXY 01",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.16.56.6",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "VIVO TLS 02",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "[app_host]",
      "TlsIP": "104.18.7.80",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM PROXY 01",
      "FLAG": "tim",
      "Payload": "GET wss://mobilidade.cloud.caixa.gov.br [protocol][crlf]Host: [app_host][crlf]X-Forwarded-For: [app_host][crlf]Connection: Keep-Alive[crlf]User-Agent: [ua][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.16.56.6",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "TIM TLS 02",
      "FLAG": "tim",
      "Payload": "GET wss://mobilidade.cloud.caixa.gov.br HTTP/1.1\nHost: [app_host]\nUpgrade: WebSocket\n\n",
      "SNI": "mobilidade.cloud.caixa.gov.br",
      "TlsIP": "mobilidade.cloud.caixa.gov.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM TLS 03",
      "FLAG": "tim",
      "Payload": "GET wss://m.timbancavirtual.com.br/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "m.timbancavirtual.com.br",
      "TlsIP": "m.timbancavirtual.com.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM TLS 04",
      "FLAG": "tim",
      "Payload": "GET wss://cdnjs.cloudflare.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "cdnjs.cloudflare.com",
      "TlsIP": "cdnjs.cloudflare.com",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM TLS 05",
      "FLAG": "tim",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "[app_host]",
      "TlsIP": "104.16.19.94",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "CLARO TLS 01 s/plano",
      "FLAG": "claro",
      "Payload": "GET wss://mobilidade.cloud.caixa.gov.br HTTP/1.1\nHost: [app_host]\nUpgrade: WebSocket\n\n",
      "SNI": "mobilidade.cloud.caixa.gov.br",
      "TlsIP": "mobilidade.cloud.caixa.gov.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "CLARO TLS 02 s/plano",
      "FLAG": "claro",
      "Payload": "GET wss://content.akross.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: WebSocket\n\n",
      "SNI": "content.akross.com.br",
      "TlsIP": "content.akross.com.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "CLARO SSL 03 plano",
      "FLAG": "claro",
      "Payload": "",
      "SNI": "dns.web.whatsapp.com",
      "TlsIP": "",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Ssl"
    },
    {
      "Name": "CLARO SSL 04 plano",
      "FLAG": "claro",
      "Payload": "",
      "SNI": "m.waze.com",
      "TlsIP": "",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Ssl"
    },
    {
      "Name": "CLARO SSL 05 plano",
      "FLAG": "claro",
      "Payload": "",
      "SNI": "web.whatsapp.com",
      "TlsIP": "",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Ssl"
    },
    {
      "Name": "CLARO SSL 06 plano",
      "FLAG": "claro",
      "Payload": "",
      "SNI": "m.twitter.com",
      "TlsIP": "",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Ssl"
    },
    {
      "Name": "OI PROXY 01",
      "FLAG": "oi",
      "Payload": "GET / HTTP/1.1[crlf]Host: [host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.16.56.6",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "OI TLS 02",
      "FLAG": "oi",
      "Payload": "GET ws://mobilidade.cloud.caixa.gov.br HTTP/1.1\nHost: [app_host]\nUpgrade: WebSocket\n\n",
      "SNI": "mobilidade.cloud.caixa.gov.br",
      "TlsIP": "mobilidade.cloud.caixa.gov.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    }
  ]
}
