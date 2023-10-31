# COMO INTEGRAR O WORDPRESS AO MAUTIC?
Para integrar o WordPress ao Mautic, você pode usar um plugin ou integrar as duas plataformas manualmente.

**Usando um plugin**

Existem vários plugins que podem ser usados para integrar o WordPress ao Mautic. Um dos plugins mais populares é o **Mautic WordPress Integration**. Este plugin permite sincronizar os usuários do WordPress com os contatos do Mautic. Ele também permite que você crie formulários de inscrição no Mautic e os exiba em seu site WordPress.

Para instalar o plugin **Mautic WordPress Integration**, siga estas etapas:

1. Acesse o painel de administração do seu site WordPress.
2. Vá para **Plugins** > **Adicionar novo**.
3. Pesquise por "mautic".
4. Clique no botão **Instalar agora**.
5. Clique no botão **Ativar**.

Depois de instalar o plugin, você precisará configurar as conexões com o WordPress e o Mautic. Para fazer isso, siga as instruções do plugin.

**Integrando manualmente**

Se você não quiser usar um plugin, também pode integrar o WordPress ao Mautic manualmente. Para fazer isso, você precisará seguir estas etapas:

1. Configure um servidor de API para o Mautic.
2. Crie um aplicativo no Mautic.
3. Obtenha as chaves de API do seu aplicativo Mautic.
4. Configure as conexões com o WordPress e o Mautic.

**Configurando um servidor de API para o Mautic**

Para configurar um servidor de API para o Mautic, você precisará instalar o servidor Nginx ou Apache em seu servidor. Depois de instalar o servidor, você precisará criar um arquivo de configuração para o Mautic.

O arquivo de configuração deve conter as seguintes informações:

* O endereço IP ou o nome de domínio do seu servidor Mautic.
* A porta do servidor Mautic.
* O caminho para o diretório de instalação do Mautic.

Depois de criar o arquivo de configuração, você precisará reiniciar o servidor.

**Criando um aplicativo no Mautic**

Para criar um aplicativo no Mautic, siga estas etapas:

1. Acesse o painel de administração do Mautic.
2. Vá para **Configurações** > **Aplicativos**.
3. Clique no botão **Novo aplicativo**.
4. Digite um nome para o seu aplicativo.
5. Selecione o tipo de aplicativo.
6. Digite a URL do seu servidor de API.
7. Clique no botão **Criar**.

**Obtendo as chaves de API do seu aplicativo Mautic**

Depois de criar o aplicativo, você poderá obter as chaves de API. Para fazer isso, siga estas etapas:

1. Acesse o painel de administração do Mautic.
2. Vá para **Configurações** > **Aplicativos**.
3. Clique no nome do seu aplicativo.
4. Clique na guia **Chaves de API**.

As chaves de API são exibidas na seção **Chaves de API**.

**Configurando as conexões com o WordPress e o Mautic**

Depois de obter as chaves de API, você precisará configurar as conexões com o WordPress e o Mautic. Para fazer isso, você precisará editar o arquivo de configuração do seu site WordPress.

O arquivo de configuração deve conter as seguintes informações:

* O endereço IP ou o nome de domínio do seu servidor Mautic.
* A porta do servidor Mautic.
* As chaves de API do seu aplicativo Mautic.

Depois de configurar as conexões, você poderá sincronizar os usuários do WordPress com os contatos do Mautic.

**Sincronizando usuários**

Para sincronizar os usuários do WordPress com os contatos do Mautic, você precisará usar o script de sincronização do Mautic. O script de sincronização está localizado no diretório **app/console** do Mautic.

Para executar o script de sincronização, você precisará usar o seguinte comando:

```
php app/console mautic:sync:users
```

Este comando sincronizará todos os usuários do WordPress com os contatos do Mautic.

**Conclusão**

A integração do WordPress ao Mautic permite que você use o Mautic para gerenciar seus leads e clientes. Ao integrar as duas plataformas, você poderá:

* Sincronizar os usuários do WordPress com os contatos do Mautic.
* Criar formulários de inscrição no Mautic e os exibir em seu site WordPress.
* Enviar e-mail marketing para seus leads e clientes.

A melhor maneira de integrar o WordPress ao Mautic depende das suas necessidades