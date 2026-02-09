# 🔧 Sistema de Orçamentos para Oficina Mecânica

Sistema web completo para geração de orçamentos de serviços mecânicos, com cálculos automáticos, impressão otimizada e interface profissional.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📋 Funcionalidades

### ✨ Principais Recursos

- 📝 **Cadastro Completo**: Dados do cliente e veículo
- 🛠️ **Gestão de Serviços**: Adicione/remova serviços e peças dinamicamente
- 🧮 **Cálculos Automáticos**: 
  - Valor total por item (quantidade × valor unitário)
  - Cálculo de impostos por serviço
  - Subtotal, total de impostos e valor final
- 🖨️ **Impressão Otimizada**: PDF em uma única página
- 📱 **Design Responsivo**: Funciona em desktop, tablet e mobile
- 💾 **Interface Intuitiva**: Fácil de usar, sem necessidade de treinamento

### 📊 Campos do Orçamento

**Dados do Cliente:**
- Nome completo
- Telefone (com formatação automática)
- E-mail

**Dados do Veículo:**
- Placa (formatação automática em maiúsculas)
- Modelo do veículo
- Quilometragem atual

**Serviços e Peças:**
- Quantidade
- Descrição detalhada
- Valor unitário
- Valor total (calculado automaticamente)
- Porcentagem de imposto
- Valor final com imposto

## 🚀 Como Usar

### Opção 1: Uso Direto
1. Baixe o arquivo `orcamento_mecanico.html`
2. Abra no seu navegador (Chrome, Firefox, Edge, Safari)
3. Pronto! Comece a criar orçamentos

### Opção 2: Hospedar Online
Você pode hospedar gratuitamente em:
- **GitHub Pages**
- **Netlify**
- **Vercel**

## 💻 Instalação

```bash
# Clone o repositório
git clone https://github.com/SEU-USUARIO/sistema-orcamento-mecanica.git

# Entre na pasta
cd sistema-orcamento-mecanica

# Abra o arquivo no navegador
# Ou use um servidor local:
python -m http.server 8000
# Acesse: http://localhost:8000
```

## 📖 Manual de Uso

### Passo 1: Preencher Dados
1. Preencha os dados do cliente (campos com * são obrigatórios)
2. Preencha os dados do veículo

### Passo 2: Adicionar Serviços
1. Clique em "**+ Adicionar Serviço/Peça**"
2. Preencha:
   - Quantidade
   - Descrição do serviço
   - Valor unitário
   - Porcentagem de imposto (se houver)
3. Os valores são calculados automaticamente!

### Passo 3: Imprimir
1. Revise todos os dados
2. Clique em "**🖨️ Imprimir Orçamento**"
3. Escolha "Salvar como PDF" ou imprimir diretamente

### Passo 4: Limpar (Opcional)
- Use "**🗑️ Limpar Formulário**" para começar um novo orçamento

## 🎨 Capturas de Tela

### Interface Principal
![Interface](https://via.placeholder.com/800x400.png?text=Interface+do+Sistema)

### Orçamento Impresso
![Impressão](https://via.placeholder.com/800x400.png?text=Orcamento+Impresso)

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Design moderno com gradientes e animações
- **JavaScript Vanilla**: Lógica e cálculos automáticos
- **Responsividade**: Media queries para todos os dispositivos

## ✅ Recursos Técnicos

- ✨ Interface moderna com gradientes
- 🎯 Validação de campos obrigatórios
- 🔢 Formatação automática (telefone, placa)
- 💰 Cálculos em tempo real
- 🖨️ Otimização de impressão (cabe em 1 página A4)
- 📊 Totalizadores automáticos
- 🗑️ Confirmação antes de limpar dados
- 🚫 Sem dependências externas
- 📦 Arquivo único (fácil de distribuir)

## 🌐 Compatibilidade

- ✅ Chrome/Edge (v90+)
- ✅ Firefox (v88+)
- ✅ Safari (v14+)
- ✅ Opera (v76+)
- ✅ Mobile browsers

## 📝 Melhorias Futuras

- [ ] Salvar orçamentos no LocalStorage
- [ ] Exportar para PDF diretamente (sem impressão)
- [ ] Adicionar logo da oficina
- [ ] Sistema de numeração de orçamentos
- [ ] Histórico de orçamentos
- [ ] Busca de clientes cadastrados
- [ ] Envio por e-mail
- [ ] Modo escuro

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um Fork do projeto
2. Criar uma Branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a Branch (`git push origin feature/MinhaFeature`)
5. Abrir um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👤 Autor

Criado com ❤️ para facilitar o trabalho de oficinas mecânicas

## 📞 Suporte

Encontrou algum problema? Abra uma [Issue](https://github.com/SEU-USUARIO/sistema-orcamento-mecanica/issues)

---

⭐ Se este projeto foi útil para você, considere dar uma estrela!
