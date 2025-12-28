# Ask Agent - Frontend

Este é o front-end do **Ask Agent**, uma interface moderna, rápida e intuitiva para interação com salas de perguntas e agentes de IA.

## 🚀 Tecnologias

- **Framework**: [Vite](https://vitejs.dev/) + [React](https://react.dev/)
- **Linguagem**: TypeScript
- **Estilização**: [Tailwind CSS 4](https://tailwindcss.com/)
- **UI System**: [Shadcn UI](https://ui.shadcn.com/) (Radix UI + Lucid Icons)
- **Data Fetching**: [TanStack Query v5](https://tanstack.com/query/latest)
- **Formulários**: [React Hook Form](https://react-hook-form.com/) + [Zod](https://zod.dev/)
- **Datas**: DayJS

## 💻 Funcionamento

O Ask Agent permite que usuários criem salas de discussão onde perguntas podem ser enviadas e respondidas por agentes de inteligência artificial.

1. **Salas de Interação**: O usuário cria ou entra em uma sala específica através de um ID único.
2. **Transcrição de Áudio**: Suporte para gravação de áudio em tempo real, que é enviado para processamento e transcrição automática.
3. **Fluxo de Perguntas**: Dentro da sala, qualquer participante pode enviar dúvidas ou tópicos de discussão.
4. **Respostas com IA**: O backend processa as perguntas e áudios utilizando modelos de linguagem e retorna respostas contextualizadas.
4. **Interface Reativa**: A aplicação utiliza hooks modernos e gerenciamento de estado eficiente para garantir uma experiência fluida sem recarregamentos desnecessários.

## 🏁 Como Rodar

### Pré-requisitos
- Node.js (v20+)

### Passo a Passo

1. **Instale as dependências**:
   ```bash
   npm install
   ```

2. **Inicie o servidor de desenvolvimento**:
   ```bash
   npm run dev
   ```

A aplicação estará disponível em `http://localhost:5173`.

---
Desenvolvido com foco em performance e uma experiência de usuário premium.
