```markdown
# 🐕 Formulário de Adoção de Animais

Um sistema web desenvolvido em Flask para gerenciar solicitações de adoção de animais, com envio automático de e-mails e armazenamento de dados.

![Flask](https://img.shields.io/badge/Flask-2.3.3-green)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Resend](https://img.shields.io/badge/Email-Resend-orange)

## ✨ Funcionalidades

- **📝 Formulário Interativo**: Interface amigável para solicitações de adoção
- **📧 Envio Automático de E-mails**: Notificações instantâneas via Resend
- **💾 Armazenamento de Dados**: Salva todas as mensagens em JSON
- **📊 Dashboard de Mensagens**: Visualização organizada das solicitações
- **⏰ Timestamp Automático**: Registro preciso da data e hora de cada solicitação

## 🛠️ Tecnologias Utilizadas

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Email Service**: Resend API
- **Armazenamento**: JSON
- **Deploy**: Flask development server

## 📋 Pré-requisitos

- Python 3.8 ou superior
- pip (gerenciador de pacotes do Python)
- Conta no [Resend](https://resend.com) para serviço de e-mails

## 🚀 Instalação e Configuração

1. **Clone o repositório**:
```bash
git clone https://github.com/seu-usuario/formulario-adocao.git
cd formulario-adocao
```

2. **Crie um ambiente virtual**:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# ou
venv\Scripts\activate  # Windows
```

3. **Instale as dependências**:
```bash
pip install flask resend
```

4. **Configure a API Key do Resend**:
```python
# No arquivo app.py, substitua pela sua chave:
resend.api_key = "sua_chave_api_resend_aqui"
```

5. **Execute a aplicação**:
```bash
python app.py
```

6. **Acesse no navegador**:
```
http://localhost:5000
```

## 📁 Estrutura do Projeto

```
formulario-adocao/
│
├── app.py              # Aplicação principal Flask
├── dados.json          # Banco de dados das mensagens
├── templates/
│   └── index.html     # Página principal do formulário
├── static/
│   ├── css/
│   │   └── style.css  # Estilos da aplicação
│   └── js/
│       └── script.js  # Scripts JavaScript
└── README.md
```

## 🔧 Configuração do Resend

1. Crie uma conta no [Resend](https://resend.com)
2. Obtenha sua API Key no dashboard
3. Verifique seu domínio de e-mail
4. Substitua a chave no código e configure os e-mails de destino

## 📊 Estrutura dos Dados

As mensagens são armazenadas no formato JSON:
```json
[
  {
    "nome": "João Silva",
    "email": "joao@email.com",
    "mensagem": "Gostaria de adotar um cachorro...",
    "data": "2024-01-15 10:30:45.123456"
  }
]
```

## 🎨 Personalização

### Modificar Estilos
Edite o arquivo `static/css/style.css` para personalizar a aparência do formulário.

### Alterar Template
Modifique `templates/index.html` para ajustar o layout do formulário.

### Configurar E-mails
Ajuste o template de e-mail no arquivo `app.py` na função de envio.

## 🤝 Contribuição

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📞 Suporte

Para dúvidas ou sugestões, entre em contato:

- **Email**: alexsandracampos@hotmail.com
- **Issues**: [GitHub Issues](https://github.com/seu-usuario/formulario-adocao/issues)

## 🚀 Próximas Melhorias

- [ ] Sistema de autenticação
- [ ] Painel administrativo
- [ ] Notificações por SMS
- [ ] Integração com redes sociais
- [ ] Sistema de agendamento de visitas

---

**Desenvolvido com ❤️ para ajudar animais a encontrarem um lar amoroso.**
```

Este README inclui:

- 🎨 **Badges coloridas** para visualização rápida das tecnologias
- 🐕 **Emojis temáticos** relacionados a adoção de animais
- 📋 **Seções organizadas** com informações completas
- 🚀 **Instruções claras** de instalação e configuração
- 📊 **Estrutura visual** do projeto e dados
- 🔧 **Configurações detalhadas** para personalização
- 🤝 **Guidelines** para contribuição
- 📝 **Licença e suporte**

Você pode personalizar ainda mais adicionando screenshots, gifs demonstrativos, ou informações específicas sobre seu projeto!
