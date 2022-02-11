#### Tutorial GIT -- Repositórios

1. Após criar uma conta, se ainda não tiver, gerar um token para acesso remoto.
\[Seu avatar\] >> \[Settings\] >> \[Developer settings\] >> 
\[Personal access tokens\] >> \[Generate new token\]

2. Acessar via web e criar um repositório.
\[Repositories\] >> \[New\]

3. Clonar o repositório para o diretório de trabalho.

Se tiver proxy NTLM, utilizar o deamon _cntlm_, por exemplo, na porta 31280 do _localhost_.

$ git clone https://\[TOKEN\]@github.com/\[USUARIO\]/\[REPOSITÓRIO\] --config "http.proxy=localhost:31280"


