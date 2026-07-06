# assistente-vendas-notebooklm

# 📈 Assistente de Vendas para Refrigeração com NotebookLM

Este projeto automatiza o atendimento de clientes de refrigeração via WhatsApp utilizando a Inteligência Artificial do **NotebookLM do Google**. Ele identifica defeitos comuns de geladeiras Frost-Free por sintomas e calcula o valor da taxa de visita de forma automática, protegendo o lucro do técnico.

---

## 🎯 1. Objetivo do Projeto
* **O que faz:** Transforma mensagens de reclamação de clientes em scripts de vendas profissionais.
* **O diferencial:** Oculta o nome técnico das peças para evitar que o cliente faça o conserto sozinho (pirataria de diagnóstico) e cobra o valor correto de visita técnica.

---

## 📚 2. Fontes de Dados (Insumos)
O NotebookLM foi alimentado com 3 arquivos simples criados por mim:
1. `defeitos_comuns.txt`: Guia técnico de defeitos (bloqueio de gelo, estalo no motor e vazamento de água).
2. `tabela_precos.txt`: Regras de cobrança divididas por zonas de distância (Zonas A, B e C) e tipo de imóvel (Casa ou Prédio).
3. `roteiros_whatsapp.txt`: Modelos de mensagens que vendem a visita técnica sem dar o diagnóstico de graça.

---

## 🛠️ 3. Passo a Passo de Execução (Método F.I.A.R.)

Siga estas 4 etapas mecânicas para fazer o sistema funcionar no dia a dia:

* **Passo 1 [F] Fim:** Defini o objetivo: ter um roteiro de vendas rápido no celular que calcula preços e esconde o nome das peças.
* **Passo 2 [I] Insumo:** Baixei e juntei as informações de defeitos comuns de geladeiras Frost-Free e criei as tabelas de preços por zonas de distância.
* **Passo 3 [A] Ação:** Enviei os arquivos para o NotebookLM e treinei a IA com o seguinte comando (prompt) mestre:
  > *"Atue como um técnico de refrigeração focado em vendas. Quando eu colar o sintoma do cliente e a região dele, identifique o problema real. NÃO diga o nome de nenhuma peça. Use termos gerais como 'falha no sistema de degelo' e calcule o valor final somando a Zona de distância e a taxa de R$ 15 se for prédio."*
* **Passo 4 [R] Refino:** Testei e ajustei as respostas no chat lateral para garantir que as mensagens geradas fossem curtas, diretas e prontas para copiar e colar no WhatsApp.

---

## 🧮 4. Regras de Precificação Inteligente (Exemplo Fictício)
A IA calcula o preço da visita técnica aplicando esta lógica de forma automática:
* **Zona A (Próxima):** R$ 80,00  |  **Zona B (Média):** R$ 100,00  |  **Zona C (Afastada):** R$ 120,00
* **Taxa de Prédio/Apartamento:** Adiciona +R$ 15,00 fixos em qualquer zona (devido ao tempo de portaria e elevador).

---
🔬 *Projeto prático desenvolvido para o portfólio da plataforma DIO.*
