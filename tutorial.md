## Tutorial GIT -- Repositórios

#### 1. Após criar uma conta, se ainda não tiver, gerar um token para acesso remoto.

**[Seu avatar] >> [Settings] >> [Developer settings] >> [Personal access tokens] >> [Generate new token]**

#### 2. Acessar via web e criar um repositório.

**[Repositories] >> [New]**

#### 3. Clonar o repositório para o diretório de trabalho.

Se tiver proxy NTLM, utilizar o deamon _cntlm_, por exemplo, na porta 31280 do _localhost_.

~~~
$ git clone https://[TOKEN]@github.com/[USUARIO]/[REPOSITÓRIO] --config "http.proxy=localhost:31280"
~~~

~~~
$$$$$$$$$$$$$$$$$$$$$$$$$
$$$ EM CASO DE EDIÇÃO $$$
$$$$$$$$$$$$$$$$$$$$$$$$$
~~~

#### 4. Editar os arquivos.

#### 5. Adicionar as mudanças do DIRETÓRIO LOCAL para a área de STAGE -- "STAGING AREA".

**$ git add .**

#### 6. Criar o snapshot do projeto através do COMMIT no REPOSITÓRIO LOCAL.

**$ git commit -m "comentário: fechando snapshot e testando atualização"**

#### 7. Fazer o upload do snapshot para o SERVIDOR GIT através do PUSH.

**$ git push -u origin master**

~~~
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
$$$ EM CASO DE EDIÇÃO POR OUTROS $$$
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
~~~

#### 8. Atualizar -- fazer download das ultimas mudanças do SERVIDOR GIT para o DIRETÓRIO LOCAL.

**$ git pull origin**

~~~ FIM ~~~
