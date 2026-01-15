# 🌐 CodeKit Community

O **CodeKit Community** é a plataforma web oficial do ecossistema CodeKit. Ele foi desenvolvido para servir como um hub centralizado onde desenvolvedores podem compartilhar, explorar e baixar snippets de código (arquivos `.codekit`) de forma integrada.

🔗 **Acesse o sistema:** [Visualizar Projeto Online](https://codekit.free.nf/)

---

## 💡 Sobre o Projeto
Este portal é o braço online do projeto **CodeKit Desktop**. Enquanto o software gerencia seus códigos localmente, a comunidade permite que o conhecimento seja compartilhado. O sistema foi construído focando em uma experiência de usuário (UX) fluida, segurança de dados e alta performance em ambientes de hospedagem web.

### 🚀 Funcionalidades Principais
* **Exploração Inteligente:** Sistema de busca em tempo real com filtros por "Mais Baixados", "Mais Curtidos" e "Recentes".
* **Visualização de Código:** Syntax Highlighting profissional para diversas linguagens (Python, PHP, JS, SQL, etc) utilizando *Prism.js*.
* **Perfil do Criador:** Painel dedicado para cada desenvolvedor com estatísticas de downloads e galeria de snippets.
* **Segurança de Autenticação:** Sistema de login com gestão de sessões e proteção de rotas privadas.
* **Recuperação por Pergunta de Segurança:** Método de recuperação de conta independente de servidores de e-mail, utilizando respostas criptografadas.
* **Interface Adaptável:** Suporte completo a **Dark Mode** com persistência de preferência via LocalStorage.

---

## 🛠️ Stack Tecnológica & Arquitetura
Como este repositório é focado na documentação do sistema, aqui estão os pilares técnicos da implementação:

- **Backend:** PHP 8+ com arquitetura **PDO (PHP Data Objects)** para prevenção de SQL Injection.
- **Banco de Dados:** MySQL com tabelas relacionais para gestão de usuários, snippets e curtidas.
- **Frontend:** Tailwind CSS para uma interface responsiva, moderna e otimizada.
- **Segurança:** Criptografia de senhas e respostas de segurança utilizando o algoritmo **Bcrypt** (`password_hash`).

---

## 📸 Demonstração Visual

### 🌗 Interface & Experiência do Usuário
O sistema conta com um design moderno e minimalista, garantindo conforto visual em qualquer horário através do suporte nativo ao Modo Escuro.

<div align="center">
  <table>
    <tr>
      <td width="50%"><img src="https://github.com/user-attachments/assets/8b23ee8f-09bd-4ad2-8bd8-d281a5e3aaf7" alt="Home Page"></td>
      <td width="50%"><img src="https://github.com/user-attachments/assets/ead3aa46-f3d9-44f2-8ec2-9427fd76c87e" alt="Interface Dark"></td>
    </tr>
    <tr>
      <td width="50%"><img src="https://github.com/user-attachments/assets/a6378c4c-0b4e-4f33-9e66-ded1ef01ba2d" alt="Visualização de Código"></td>
      <td width="50%"><img src="https://github.com/user-attachments/assets/5d1c6ffd-b3f7-4947-a837-0ec74e11ce80" alt="Perfil do Usuário"></td>
    </tr>
  </table>
  <p><i>Capturas de tela demonstrando a Home, o sistema de filtros, o Visualizador de Código e o Perfil do Desenvolvedor.</i></p>
</div>

---

## 📄 Informações Adicionais
* **Status do Projeto:** Versão 1.0 (Estável).
* **Privacidade:** O código-fonte deste projeto é privado para proteção de infraestrutura e propriedade intelectual.
* **Desenvolvedor:** João Felipe do Nascimento Lopes
