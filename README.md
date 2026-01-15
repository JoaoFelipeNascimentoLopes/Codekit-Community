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

### 🌗 Modo Escuro & Interface de Usuário
O sistema conta com um design moderno e minimalista, garantindo conforto visual em qualquer horário.

<img width="1352" height="640" alt="image" src="https://github.com/user-attachments/assets/8b23ee8f-09bd-4ad2-8bd8-d281a5e3aaf7" />
<img width="1351" height="642" alt="image" src="https://github.com/user-attachments/assets/ead3aa46-f3d9-44f2-8ec2-9427fd76c87e" />


---

## 📄 Informações Adicionais
* **Status do Projeto:** Versão 1.0 (Estável).
* **Privacidade:** O código-fonte deste projeto é privado para proteção de infraestrutura e propriedade intelectual.
* **Desenvolvedor:** João Felipe do Nascimento Lopes
