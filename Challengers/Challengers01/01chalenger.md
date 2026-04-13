Aqui está a versão profissional em **inglês e português**, estruturada e pronta para README ou documentação:

---

## 🇺🇸 English Version

### Challenge: Task Management System (CLI)

🎯 **Objective**

Create a Node.js application (without frameworks) that manages tasks via the terminal, with modularized code.

---

📦 **Technical Requirements**

You must use separate modules, practicing:

* `module.exports` / `require` **OR**
* `export` / `import` (ES Modules)

---

🏗️ **Expected Structure**

Try to organize your project like this:

```
task-manager/
│
├── index.js            # entry point
├── services/
│   └── taskService.js  # task logic
├── utils/
│   └── fileHelper.js   # file read/write
├── models/
│   └── task.js         # task structure
└── data/
    └── tasks.json      # persistence
```

---

⚙️ **Features**

1. **Create Task**

   * Title
   * Description
   * Status: pending by default

2. **List Tasks**

   * Show all tasks
   * Optional: filter by status

3. **Update Status**

   * Mark task as completed

4. **Delete Task**

---

🧠 **Important Rules**

* Use file persistence (`fs`)
* Each responsibility must be in a separate module
* Do not mix business logic with IO operations
* Avoid duplicated code

---

## 🇧🇷 Versão em Português

### Desafio: Sistema de Gerenciamento de Tarefas (CLI)

🎯 **Objetivo**

Criar uma aplicação em Node.js (sem frameworks) que gerencie tarefas via terminal, com código modularizado.

---

📦 **Requisitos Técnicos**

Você deve utilizar módulos separados, praticando:

* `module.exports` / `require` **OU**
* `export` / `import` (ES Modules)

---

🏗️ **Estrutura Esperada**

Tente organizar o projeto da seguinte forma:

```
task-manager/
│
├── index.js            # ponto de entrada
├── services/
│   └── taskService.js  # lógica de tarefas
├── utils/
│   └── fileHelper.js   # leitura/escrita de arquivos
├── models/
│   └── task.js         # estrutura da tarefa
└── data/
    └── tasks.json      # persistência
```

---

⚙️ **Funcionalidades**

1. **Criar tarefa**

   * Título
   * Descrição
   * Status: pendente por padrão

2. **Listar tarefas**

   * Exibir todas
   * Opcional: filtrar por status

3. **Atualizar status**

   * Marcar como concluída

4. **Deletar tarefa**

---

🧠 **Regras importantes**

* Utilizar persistência em arquivo (`fs`)
* Cada responsabilidade deve estar em um módulo separado
* Não misturar lógica de negócio com operações de IO
* Evitar código duplicado
