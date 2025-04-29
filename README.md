# README.md
# Criação de Máquina Virtual no Azure

## Descrição
Repositório criado para documentar o processo de criação e configuração de uma máquina virtual (VM) no Microsoft Azure, conforme desafio da DIO.

## Objetivos
- Praticar a criação de VMs no Azure.
- Documentar o processo de forma clara e estruturada.
- Compartilhar dicas e aprendizados.

## Pré-requisitos
- Conta ativa no Microsoft Azure.
- Acesso ao portal do Azure.
- Cliente de Área de Trabalho Remota (para acesso à VM).

## Passo a Passo

1. **Acessar o Portal do Azure**
   - Entre em [portal.azure.com](https://portal.azure.com).

2. **Criar uma Nova Máquina Virtual**
   - No menu, pesquise por "Máquinas virtuais" e clique em "Criar" > "Máquina virtual do Azure"[1][7].
   - Preencha os detalhes da instância (nome, imagem, região, etc.).
   - Defina o usuário e senha de administrador.
   - Permita as portas RDP (3389) e HTTP (80).
   - Clique em "Examinar + criar" e, após validação, em "Criar".

3. **Acessar a Máquina Virtual**
   - Após a implantação, clique em "Ir para o recurso".
   - Use o endereço IP público e as credenciais para conectar via RDP.

4. **Configurações Adicionais**
   - Instale softwares, configure firewall, etc.

## Dicas e Observações
- Utilize nomes de recursos padronizados para facilitar a organização.
- Salve os dados de acesso em local seguro.
- Para ambientes de produção, revise as regras de segurança.

## Imagens
![Tela de criação da VM](images/criacao-vm.png)

## Referências
- [Documentação Oficial Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
- [Guia de Markdown GitHub](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

## Autor
Seu Nome - [LinkedIn](#)
Boas Práticas para Organização do Repositório
Mantenha uma estrutura de pastas clara: por exemplo, /docs para documentação extra, /images para capturas de tela, etc.

Utilize um arquivo .gitignore para evitar versionar arquivos desnecessários.

Atualize o README.md sempre que o projeto evoluir.

Use links relativos para imagens hospedadas no próprio repositório.

Considere adicionar badges, status do projeto e índice para facilitar a navegação.

Como Adicionar Imagens ao README.md
Coloque as imagens na pasta /images do repositório.

Referencie-as no README usando a sintaxe Markdown:
![Descrição da imagem](images/nome-da-imagem.png)
Recursos Úteis
Como criar uma VM no Azure (documentação oficial)

Guia de Markdown do GitHub

Modelos de README
