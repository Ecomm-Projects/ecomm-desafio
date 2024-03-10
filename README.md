# Desafio Ecomm

## Descrição

Este desafio tem como objetivo verificar as habilidades do desenvolvedor na migração de HTML para Blade e avaliar o nível de conhecimento em PHP com Laravel.

## Instruções

1. **Baixar e Instalar o NODE:**
   - Baixe o NODE a partir deste [link](https://nodejs.org/dist/v21.7.1/node-v21.7.1-x64.msi).
   - Após o download, instale o NODE.

2. **Baixar e Instalar o XAMPP:**
   - Baixe o XAMPP a partir deste [link](https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/8.0.30/xampp-windows-x64-8.0.30-0-VS16-installer.exe).
   - Após o download, instale o XAMPP.

3. **Configuração do Ambiente:**
   - Acesse a pasta htdocs, normalmente localizada em C:\xampp\htdocs ou na pasta onde o XAMPP foi instalado.
   - Clone o repositório para dentro da pasta HTDOCS.

4. **Iniciar Servidores:**
   - Inicie o Apache utilizando o controle do XAMPP.
   - Abra o terminal na pasta htdocs e execute os seguintes comandos:
     ```
     npm install # (executar apenas uma vez)
     npm run dev
     ```
   - Acesse a URL http://localhost para verificar se a instalação foi concluída corretamente. A página inicial do Laravel deve ser exibida.

5. **Instalação do Projeto Laravel:**
   - Abra o terminal.
   - Navegue até a pasta do projeto clonado dentro da pasta HTDOCS.
   - Baixe o composer  [link](https://getcomposer.org/Composer-Setup.exe).
   - Instale-o.
   - Execute o seguinte comando para instalar as dependências do Laravel:
     ```
     composer install
     ```
   - Copie o arquivo `.env.example` e renomeie para `.env`.
   - Execute o seguinte comando para gerar a chave de criptografia do Laravel:
     ```
     php artisan key:generate
     ```

## Desafios

### 1° Migrar um arquivo HTML para o Blade do Laravel

O arquivo HTML está localizado na pasta **ARQUIVO MIGRAÇÃO**.

Dentro desta pasta, você encontrará dois arquivos: **migração.html** e **w3.css**. Esses arquivos fazem parte de um site público. O desafio é pegar o HTML deste site e migrá-lo para o Laravel, seguindo o template do Blade, o motor de template do Laravel.

Na página de boas-vindas (welcome), é possível visualizar a estrutura da página utilizando o Vite e o motor do Laravel. Reproduza a mesma estrutura no arquivo **migracao.blade.php**, migrando o HTML.