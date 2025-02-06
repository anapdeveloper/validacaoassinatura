# validacaoassinatura
 Sistema de Validação de Receita Digital
© 2025 Ana Paula Apolinário Soares. Todos os direitos reservados.

## Guia de Instalação Passo a Passo

### 1. Instalação do XAMPP

1. Baixe o XAMPP:
   - Acesse o site: https://www.apachefriends.org/pt_br/index.html
   - Clique no botão de download para Windows
   - Baixe a versão mais recente

2. Instale o XAMPP:
   - Execute o arquivo baixado (exemplo: xampp-windows-x64-8.2.4-0-VS16-installer.exe)
   - Clique "Next" nas telas do instalador
   - Mantenha o local de instalação padrão (geralmente C:\xampp)
   - Aguarde a instalação terminar

3. Inicie o XAMPP:
   - Abra o XAMPP Control Panel
   - Clique no botão "Start" ao lado de "Apache"
   - Clique no botão "Start" ao lado de "MySQL"
   - Você verá as luzes ficarem verdes, indicando que está funcionando

### 2. Criação das Pastas do Projeto

1. Abra o Windows Explorer
2. Vá até C:\xampp\htdocs
3. Crie as seguintes pastas nesta ordem:
   - Crie uma pasta chamada "clinicacheckup"
   - Dentro dela, crie uma pasta "sistema"
   - Dentro de "sistema", crie uma pasta "painel"
   - Dentro de "painel", crie uma pasta "rel"

Você terá esta estrutura:
```
C:\xampp\htdocs\clinicacheckup\
└── sistema\
    └── painel\
        └── rel\
```

### 3. Criação dos Arquivos

1. Dentro da pasta "rel", crie um arquivo chamado "receita_class.php"
2. Copie e cole o código que forneci anteriormente neste arquivo

### 4. Teste do Sistema

1. Abra seu navegador (Chrome, Firefox, etc)
2. Digite na barra de endereços:
   ```
   http://localhost/clinicacheckup/sistema/painel/rel/receita_class.php
   ```
3. Você deverá ver a página de validação de receitas

### Problemas Comuns e Soluções

1. **Página não abre**
   - Verifique se o XAMPP está rodando (luzes verdes)
   - Confirme se digitou o endereço corretamente
   - Verifique se criou as pastas nos lugares certos

2. **Página em branco**
   - Verifique se salvou o arquivo .php corretamente
   - Confirme se copiou todo o código
   - Verifique se não há erros de digitação

3. **XAMPP não inicia**
   - Feche outros programas que possam usar a porta 80 (Skype, etc)
   - Execute o XAMPP como administrador
   - Reinicie o computador

### Próximos Passos

Depois que o sistema estiver funcionando localmente, você pode:
1. Fazer ajustes no design
2. Testar em diferentes navegadores
3. Preparar para hospedar na Hostinger

## Licença e Direitos Autorais

© 2025 Ana Paula Apolinário Soares
Todos os direitos reservados. Este software é propriedade de Ana Paula Apolinário Soares e seu uso, cópia, modificação ou distribuição sem autorização expressa é estritamente proibido.
