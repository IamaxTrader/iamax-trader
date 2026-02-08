# 📱 Iamax Trader - PWA

Progressive Web App para cadastro de clientes interessados no sistema Iamax Trader.

## ✨ Funcionalidades

- ✅ Funciona como app nativo no celular
- ✅ Pode ser instalado na tela inicial
- ✅ Funciona offline após primeira visita
- ✅ Formulário de cadastro completo
- ✅ Integração direta com WhatsApp (37) 99971-3275
- ✅ Design responsivo e moderno
- ✅ Animações suaves
- ✅ Máscara automática de telefone

## 📋 Arquivos Inclusos

```
iamax-trader/
├── index.html          # Página principal do PWA
├── manifest.json       # Configuração do PWA
├── service-worker.js   # Funcionamento offline
├── icon-192.png        # Ícone 192x192
├── icon-512.png        # Ícone 512x512
└── README.md           # Este arquivo
```

## 🚀 Como Publicar Online (GRÁTIS)

### Opção 1: Vercel (Recomendado - Mais Fácil)

1. Acesse https://vercel.com
2. Crie uma conta gratuita
3. Clique em "Add New Project"
4. Faça upload da pasta `iamax-trader`
5. Clique em "Deploy"
6. Pronto! Você terá um link como: `iamax-trader.vercel.app`

### Opção 2: Netlify

1. Acesse https://netlify.com
2. Crie uma conta gratuita
3. Arraste a pasta `iamax-trader` para a área de upload
4. Aguarde o deploy automático
5. Seu site estará no ar em segundos!

### Opção 3: GitHub Pages

1. Crie um repositório no GitHub
2. Faça upload dos arquivos
3. Vá em Settings > Pages
4. Ative GitHub Pages
5. Seu site ficará em: `seu-usuario.github.io/iamax-trader`

## 📱 Como Instalar no Celular

### Android:
1. Abra o site no Chrome
2. Toque nos 3 pontinhos (menu)
3. Selecione "Adicionar à tela inicial"
4. Pronto! O app aparecerá como um ícone normal

### iOS (iPhone):
1. Abra o site no Safari
2. Toque no botão de compartilhar
3. Selecione "Adicionar à Tela Inicial"
4. Confirme

## 🎨 Personalização

### Mudar Cores:
Edite o `index.html` nas linhas de CSS:
- Cor principal: `#10b981` (verde)
- Cor de fundo: `#0f172a` (azul escuro)

### Mudar Ícone:
Substitua os arquivos `icon-192.png` e `icon-512.png` pelos seus próprios ícones.

### Mudar WhatsApp:
No arquivo `index.html`, linha ~420, altere:
```javascript
const whatsappNumber = '5537999713275'; // Seu número aqui
```

## 📊 O Que Acontece Quando Alguém Preenche?

1. Usuário preenche o formulário
2. Mensagem é formatada automaticamente
3. Abre o WhatsApp com a mensagem pronta
4. Você recebe a mensagem no seu WhatsApp!

Exemplo de mensagem recebida:
```
📊 Novo Lead - Iamax Trader

👤 Nome: João Silva
📱 Telefone: (37) 99999-9999
✉️ Email: joao@email.com
📈 Experiência: Iniciante (< 1 ano)

💬 Mensagem:
Quero saber mais sobre o robô trader
```

## 🔒 Segurança

- Não armazena dados sensíveis
- Não usa banco de dados
- Tudo é enviado direto para o WhatsApp
- Conexão segura (HTTPS automático no Vercel/Netlify)

## 💡 Dicas

1. **Compartilhe o link** nas redes sociais, stories, bio do Instagram
2. **Crie um QR Code** do link para divulgar offline
3. **Teste sempre** antes de divulgar
4. **Monitore** as mensagens que chegam no WhatsApp

## 🆘 Precisa de Ajuda?

Se tiver dúvidas sobre o deploy ou personalização, me avise!

## 📝 Próximos Passos

Após publicar, você pode:
- [ ] Criar domínio próprio (ex: iamaxtrader.com.br)
- [ ] Adicionar Google Analytics para rastrear visitantes
- [ ] Criar página de obrigado após envio
- [ ] Adicionar mais campos no formulário
- [ ] Integrar com CRM ou planilha Google

---

Desenvolvido para Iamax Trader © 2026
