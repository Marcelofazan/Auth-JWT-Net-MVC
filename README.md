## 🌐 AdminLTE3-Autorização-Net-Mvc5
Exemplo de autorização Jwt com renderização AdminLTE3 em C# ASP.NET .NETFramework MVC5 com banco de dados MySQL.

#### 🎨 Aqui está uma demonstração do Projeto
<img width="800" height="350" alt="19 04 2026_19 13 55_REC" src="https://github.com/user-attachments/assets/3c9cdbbe-cc65-46ed-97bd-d335ed109cd2" />

#### 📋 O que você vai encontrar neste projeto
| Tecnologia | Descrição |
|-----------|-----------|
| **AdminLTE** | Template responsivo criado para facilitar a construção de painéis administrativos (dashboards) com framework Bootstrap |
| **Bootstrap4** | Famework front-end de códigos prontos em HTML, CSS e JavaScript para criar sites e interfaces web responsivas |
| **Claims** | Declarações e dados de informações sobre o usuário (como nome, identificador e permissões)  |
| **Dicionário de Dados** | Armazenamento de coleções de pares (chave-valor), permitindo busca e recuperação de dados.  |
| **JWT** | É um crachá digital usado para identificar usuários e trocar informações de forma segura entre computadores. |

#### 💬 Requisitos do Projeto
- Para executar a aplicação é necessário executar o Script do MySQL.
- Baixar Pacote de Distribuição de Download da biblioteca e descompactar [AdminLTE](https://github.com/ColorlibHQ/AdminLTE/archive/refs/tags/v3.2.0-rc.zip)

Criar uma nova pasta chamada adminlte no Solution do Projeto
- Acessar o diretorio na pasta AdminLTE-3.2.0-rc /dist ->  Arrastar as pastas (css), (img) e (js) e Colar dentro da pasta adminlte
- Acessar AdminLTE-3.2.0-rc /plugins -> Arrastar a pasta (plugins) e Colar dentro da pasta adminlte

Ficara com a seguinte estrutura: 

**Solution** Pasta na Raiz do Projeto 
```bash
adminlte
|-------|
        |-------| /css
        |-------| /img 
        |-------| /js
        |-------| /plugins
```
#### ⚠️ String de conexão do banco

- Modifique a string de conexão no arquivo **Web.config**, no trecho indicado:
```bash
server=127.0.0.1;userid=root;password=SUASENHA;database=SEUBANCO;persistsecurityinfo=True;

```
O script para criação da tabela do exemplo encontra-se na pasta **Database**.
