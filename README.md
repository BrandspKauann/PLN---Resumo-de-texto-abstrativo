# ✨ Projeto PLN Avançado: Resumo de Texto Abstrativo (Transformers)

## 🎯 Objetivo e Arquitetura

O foco deste projeto é ir além do resumo extrativo (seleção de frases) para implementar o **Resumo Abstrativo**, a técnica mais avançada em PLN.

Para isso, a arquitetura simula o uso da *pipeline* de `summarization` do Hugging Face e o modelo Transformer **DistilBART (`sshleifer/distilbart-cnn-12-6`)**.

| Característica | Resumo Abstrativo (DistilBART) | Vantagem |
| :---: | :---: | :--- |
| **Método** | **Gera frases novas** e originais. | Cria um resumo mais conciso, coeso e fluido. |
| **Coerência Semântica** | Alta. | Ideal para consolidar informações complexas ou jargões. |



---

## 💡 Aplicações e Resultados Abstrativos

O modelo DistilBART demonstra a capacidade de **reformulaçar e consolidar** informações em diferentes domínios:

### 1. 📰 Resumo de Notícias (Consolidação de Fatos)

O modelo combina o avanço tecnológico, o licenciamento e o impacto nas ações em uma única declaração fluida.

> **Resumo Abstrativo:** A Tech Innovate anunciou um avanço em baterias de estado sólido que dobrarão a autonomia dos veículos elétricos. O CEO, Dr. Elias Santos, confirmou que a tecnologia será licenciada a partir do próximo ano, e as ações da empresa já subiram 15%.

### 2. 🏥 Resumos Clínicos (Simplificação de Jargão)

O modelo traduz a linguagem técnica para um resumo focado no status do paciente e plano de cuidados.

> **Resumo Abstrativo:** Paciente, 65 anos, foi admitido com dor torácica. Exames confirmaram lesão miocárdica e estenose de 70% na artéria descendente anterior. Ele foi submetido com sucesso a angioplastia e terá alta em 48 horas com uso contínuo de betabloqueadores e estatinas.

### 3. 🤖 Assistentes Virtuais (Fluidez Conversacional)

O modelo transforma itens de lista em um formato de notificação conversacional e direto.

> **Resumo Abstrativo:** Sua agenda inclui a reunião do 'Projeto Alpha' às 9h e um almoço com a equipe de vendas às 14h. Às 16h, participe do webinar 'Tendências de IA'. Não há tarefas urgentes no fim da tarde.

---
