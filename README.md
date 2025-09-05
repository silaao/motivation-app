# 📱 Motivation App

O **Motivation** é um aplicativo Android desenvolvido em **Kotlin** que exibe frases motivacionais de acordo com a categoria selecionada.  
É um projeto simples e prático para treinar **View Binding, SharedPreferences e manipulação de eventos de UI**.

---

## 🚀 Funcionalidades
- O usuário informa seu **nome** no primeiro acesso.  
- O nome é **salvo localmente** usando `SharedPreferences` (similar a um banco de dados).  
- Exibição de frases motivacionais separadas por categorias:  
  - 🟣 **Todos**  
  - 😀 **Feliz**  
  - ☀️ **Ensolarado**  
- Botão para **gerar uma nova frase** conforme a categoria escolhida.  
- Interface amigável e de fácil interação.

---

## 🛠️ Tecnologias utilizadas
- **Kotlin** (linguagem principal)
- **Android Studio**
- **View Binding**
- **SharedPreferences** (persistência de dados local)
- **AppCompat / Material Design**

---

## 📂 Estrutura do projeto
- `ui/` → telas do aplicativo  
- `repository/` → repositório de frases motivacionais  
- `helper/` → constantes e utilitários  

---

## 📸 Demonstração (Exemplo de Fluxo)
![Preview da aplicação](https://i.imgur.com/ywRWS2i.png)

1. Usuário informa o **nome** → App salva no `SharedPreferences`.  
2. Tela principal exibe:  
   - Saudação personalizada: *"Olá, [Nome]"*.  
   - Filtros de categorias (Todos, Feliz, Ensolarado).  
   - Uma frase motivacional inicial.  
3. Usuário pode:  
   - **Trocar o filtro** para mudar o estilo das frases.  
   - **Gerar nova frase** ao clicar no botão.  

---

## ▶️ Como executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/silaao/motivation-app.git
   
2. Abra o projeto no Android Studio.

3. Compile e rode no emulador ou em um dispositivo Android físico.

