# 🏫 Tutorial – Usando SQLite com DB Browser

📍 **Objetivo:**  
Aprender a instalar o **DB Browser for SQLite**, conectar-se a um banco já existente chamado **`fabrica_programadores.db`**, e rodar consultas SQL.

---

## 🚀 Passo 1 – Download do DB Browser
1. Acesse o site oficial:  
   👉 [https://sqlitebrowser.org/dl/](https://sqlitebrowser.org/dl/)  

2. Escolha a versão do seu sistema:  
   - **Windows:** clique no instalador `.exe` (64-bit ou 32-bit).  
   - **MacOS:** baixe o `.dmg`.  
   - **Linux:** pode instalar pelo terminal:  
     ```bash
     sudo apt install sqlitebrowser
     ```

---

## ⚙️ Passo 2 – Instalação
- No **Windows**, abra o instalador `.exe` e clique em:  
  **Next > Next > Finish**  
- No final, você terá o programa **DB Browser for SQLite** instalado.  

---

## 📂 Passo 3 – Conectando ao Banco de Dados
1. Abra o **DB Browser for SQLite**.  
2. Clique em **File > Open Database**.  
3. Navegue até a pasta compartilhada:  
   ```
   \\DT246715\Banco de Dados\Alunos_14h
   ```
4. Selecione o arquivo **`fabrica_programadores.db`** e clique em **Open**.  

Pronto 🎉 Você está conectado ao banco da Fábrica de Programadores!  

---

## 🏗️ Passo 4 – Explorando as Tabelas
- Vá até a aba **Database Structure** (Estrutura do Banco).  
- Ali você verá as tabelas disponíveis, como:  
  - Alunos  
  - Professores  
  - Cursos  
  - Matriculas  

Para visualizar os dados:  
1. Clique na tabela desejada.  
2. Vá até a aba **Browse Data**.  

---

## ✏️ Passo 5 – Executando Queries
Na aba **Execute SQL**, você pode rodar consultas no banco:

```sql
-- Listar todos os alunos
SELECT * FROM Alunos;
etc
```

Clique em **▶️ Play (Executar)** para ver os resultados.  

---

## ✅ Passo 6 – Salvando Alterações
- Se fizer mudanças (inserções, atualizações ou exclusões), clique em **Write Changes** para salvar no arquivo.  
- O banco ficará sempre disponível em:  
  ```
  \\DT246715\Banco de Dados\Alunos_14h\fabrica_programadores.db
  ```

---

🎯 **Agora vocês sabem conectar ao banco da Fábrica de Programadores e rodar consultas SQL!**
