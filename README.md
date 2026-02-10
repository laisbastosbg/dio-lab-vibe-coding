# 💸 App de Organização de Tarefas e Cronograma com Vibe Coding

## Product Requirements Document

```txt
## Assistente de tarefas

### Contexto

Quero criar um aplicativo que gera automaticamente um cronograma visual em formato de calendário a partir de conversas naturais com o usuário.

O usuário pode escrever ou falar de forma livre tudo o que precisa ou quer fazer — sem se preocupar com estrutura, prioridade ou clareza — e o sistema transforma isso em uma agenda organizada por dias, semanas ou meses.

---

### Problema

Muitas pessoas sofrem com disfunção executiva, TDAH ou sobrecarga mental, o que dificulta:

* Organizar tarefas
* Definir prioridades
* Transformar intenções vagas em planos concretos

Ferramentas tradicionais exigem estrutura, disciplina e clareza logo no início — exatamente o que esse público mais tem dificuldade de fornecer.

---

### Objetivo do Produto

Permitir que o usuário **despeje seus pensamentos de forma caótica** e receba como retorno:

* Um cronograma organizado
* Tarefas distribuídas no tempo
* Uma visão clara do que fazer agora, depois e mais tarde

---

### Público-alvo (MVP)

Pessoa adulta, familiarizada com tecnologia, que:

* Se sente sobrecarregada com tarefas do dia a dia
* Já tentou usar apps de lista ou agenda, mas abandonou
* Prefere explicar as coisas “conversando” em vez de preencher formulários

*(Ex: pessoas com TDAH, freelancers, estudantes, pessoas em burnout leve)*

---

### Proposta de Valor

> “Fale tudo o que você precisa fazer. Eu organizo.”

---

### Funcionalidades-Chave (priorizadas)

#### Essenciais (MVP)

1. **Entrada via chat em linguagem natural**

   * Texto livre, sem formato obrigatório

2. **Interpretação e extração de tarefas**

   * Identificar:

     * O que é tarefa
     * Prazo ou período (se existir)
     * Tipo de atividade (trabalho, pessoal, estudo, saúde etc.)

3. **Geração automática de agenda**

   * Visual em calendário (dia / semana)
   * Tarefas distribuídas de forma razoável no tempo

4. **Edição simples**

   * Marcar tarefa como feita
   * Ajustar dia ou horário manualmente

---

## 3. Plano de MVP

### 3.1 Principais telas

#### 1. Tela de Chat (tela principal)

**Função:** onde tudo começa

* Campo de texto grande e acolhedor

* Placeholder tipo:

  > “Me conta tudo o que você precisa fazer, sem se preocupar em organizar”

* Respostas da IA:

  * Confirmações simples
  * Perguntas pontuais quando algo estiver ambíguo

📌 **Momento mágico aqui**:
Usuário escreve um texto caótico → clica em “Organizar” → vê a agenda surgir.

---

#### 2. Tela de Agenda (Calendário)

**Função:** visualização da ordem criada

* Visão semanal (default)
* Tarefas coloridas por tipo
* Indicador simples de carga do dia (leve / médio / pesado)

Ações:

* Marcar como concluída
* Arrastar para outro dia
* Abrir detalhes da tarefa

---

#### 3. Tela de Detalhe da Tarefa (simples)

* Nome da tarefa
* Data / período
* Tipo
* Status (pendente / feito)

Nada complexo no MVP.

---

### 3.2 Recursos técnicos essenciais

* **IA de linguagem natural**

  * Extração de tarefas
  * Interpretação de tempo (“essa semana”, “até sexta”, “algum dia”)

* **Lógica de distribuição**

  * Evitar sobrecarregar um único dia
  * Se prazo for vago, sugerir e permitir ajuste

* **Persistência básica**

  * Salvar tarefas e status

```
