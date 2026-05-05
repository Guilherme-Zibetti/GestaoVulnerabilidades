# 📑 Gerador de Plano de Testes de Vulnerabilidades

Este projeto é uma ferramenta web estática para a criação padronizada de **Planos de Testes de Vulnerabilidades**. Ele foi desenvolvido para auxiliar analistas de segurança no planejamento de varreduras e testes de intrusão, garantindo conformidade com as diretrizes da universidade.

---

## 🎯 Objetivos do Relatório

O documento gerado por esta ferramenta visa atender aos seguintes requisitos de governança:

*   **Formalização:** Registrar oficialmente o escopo e as autorizações antes de qualquer atividade técnica de varredura.
*   **Gestão de Riscos:** Mapear possíveis impactos na infraestrutura (como instabilidade ou saturação de link) e definir planos de mitigação.
*   **Padronização:** Garantir que todos os testes sigam a mesma metodologia, facilitando auditorias e revisões de conformidade.
*   **Comunicação:** Servir como base para notificar o NOC e os donos de sistemas sobre as janelas de manutenção e testes.

---

## 🚀 Como Usar

Para utilizar a ferramenta hospedada via **GitLab Pages**:

1.  **Acesso:** Abra a URL do projeto (disponível em *Settings > Pages* após o deploy).
2.  **Preenchimento:**
    *   Os campos possuem exemplos em cinza (*placeholders*) baseados na política oficial.
    *   Ao começar a digitar, o exemplo desaparecerá automaticamente.
    *   Atenção especial ao campo de **Exclusões** para proteger sistemas legados ou sensíveis.
3.  **Geração do PDF:**
    *   Clique no botão **"GERAR PDF DO PLANO"** ao final do formulário.
    *   O arquivo será processado e baixado localmente pelo seu navegador.
4.  **Aprovação:**
    *   Colete as assinaturas ou aprovações.
    *   Anexe o plano ao chamado de execução e repositório de evidências.

---

## 🛠️ Detalhes Técnicos e Segurança

*   **Tecnologias:** HTML5, CSS3 e JavaScript.
*   **Bibliotecas Externas:** [jsPDF](https://github.com/parallax/jsPDF) e [jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable).
*   **Privacidade:** O processamento dos dados é **client-side**. Nenhuma informação inserida no formulário é enviada para servidores ou armazenada no GitLab, garantindo a confidencialidade dos dados da rede.

---

## ⚖️ Licença e Uso
Este projeto é de uso restrito institucional. As atividades de teste planejadas com este documento devem respeitar a Política de Gestão de Vulnerabilidades da organização.