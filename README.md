# Sistema de Passaporte da Polícia Federal

Um sistema web responsivo para solicitação e emissão de passaportes, desenvolvido como parte de um desafio prático de desenvolvimento front-end.

## 📋 Descrição do Projeto

Este projeto consiste em uma interface web que simula o sistema oficial da Polícia Federal para solicitação de passaportes. O sistema foi desenvolvido com foco em usabilidade, acessibilidade e experiência do usuário, seguindo os padrões visuais de sistemas governamentais brasileiros.

## 🎯 Objetivos

- Criar uma interface intuitiva para solicitação de passaportes
- Implementar navegação por abas para organizar o processo
- Garantir responsividade em diferentes dispositivos
- Aplicar boas práticas de desenvolvimento front-end
- Seguir padrões de acessibilidade web

## 🚀 Funcionalidades

### ✅ Implementadas
- **Navegação por Abas**: Sistema de 4 etapas (Dados Pessoais, Documentos, Dados Complementares, Revisar Dados)
- **Formulários Validados**: Campos obrigatórios e validação de dados
- **Design Responsivo**: Adaptação para desktop, tablet e mobile
- **Interface Governamental**: Visual profissional seguindo padrões da Polícia Federal
- **Navegação Intuitiva**: Botões de "Anterior" e "Próximo" para facilitar o processo

### 📝 Etapas do Processo

1. **Dados Pessoais**
   - Nome completo
   - Sexo e filiação
   - Data de nascimento
   - Raça/cor e estado civil
   - Nacionalidade

2. **Documentos**
   - Documento de identificação (RG)
   - CPF (titular e responsável)
   - Certidão civil
   - Passaporte anterior (se houver)

3. **Dados Complementares**
   - Profissão
   - E-mail de contato
   - Endereço completo
   - Telefone

4. **Revisar Dados**
   - Confirmação de todas as informações
   - Termo de responsabilidade

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilização moderna com Flexbox e Grid
- **JavaScript**: Interatividade e validações (implementação futura)
- **Design Responsivo**: Media queries para diferentes telas

## 📁 Estrutura do Projeto

```
├── index.html              # Página principal
├── css/
│   ├── style.css           # Arquivo principal de estilos
│   ├── reset.css           # Reset e variáveis CSS
│   ├── form.css            # Estilos específicos dos formulários
│   └── tema.css            # Temas e cores
├── assets/
│   ├── logo.png            # Logo da Polícia Federal
│   └── cadeado.png         # Ícone de segurança
└── README.md               # Documentação do projeto
```

## 🎨 Design System

### Cores Principais
- **Azul Primário**: `#296da8` (Cor institucional da PF)
- **Azul Hover**: `#286499`
- **Texto Primário**: `#333333`
- **Texto Secundário**: `#d8dbe2`
- **Fundo**: `#ffffff`

### Componentes
- Formulários com validação visual
- Botões de navegação estilizados
- Headers com navegação institucional
- Footer com informações de segurança

## 📱 Responsividade

O sistema foi desenvolvido com abordagem **mobile-first**, garantindo:
- Layout adaptável de 320px a 1920px
- Navegação otimizada para touch
- Formulários acessíveis em dispositivos móveis
- Tipografia escalável

## 🔧 Como Executar

1. **Clone o repositório**
   ```bash
   git clone [url-do-repositorio]
   cd sistema-passaporte-pf
   ```

2. **Abra o arquivo HTML**
   - Abra `index.html` diretamente no navegador
   - Ou use um servidor local (Live Server, Python SimpleHTTPServer, etc.)

3. **Navegue pelo sistema**
   - Preencha os formulários em cada aba
   - Use os botões "Anterior" e "Próximo" para navegar
   - Revise os dados na última etapa

## 👨‍💻 Autor

Desenvolvido por [Lucas Carvalho](https://github.com/LucasCarvalhoo).

Orientador: Luan Oliveira

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Projeto desenvolvido como parte do programa Geração Tech do IEL 2025.

**Nota**: Este é um projeto educacional e não está vinculado oficialmente à Polícia Federal do Brasil. Não utilize para solicitações reais de passaporte.
