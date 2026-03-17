# Exemplo Aula 2 - Fragments no Android

Este é um projeto de exemplo desenvolvido para demonstrar o funcionamento básico de **Fragments** e **ConstraintLayout** no Android usando Kotlin.

## 🚀 Funcionalidades

- **MainActivity**: Tela principal que serve como hospedeira.
- **ExemploFragment**: Um fragmento simples carregado dinamicamente dentro da activity.
- **Layout Responsivo**: Uso de `ConstraintLayout` para organizar elementos visualmente.
- **Boas Práticas**: Uso de recursos de string (`strings.xml`) para evitar textos fixos no código.

## 🛠️ Tecnologias Utilizadas

- **Linguagem**: [Kotlin](https://kotlinlang.org/)
- **Interface**: XML (ConstraintLayout, FrameLayout)
- **Componentes**: Android Jetpack (AppCompat, Fragments)

## 📁 Estrutura do Projeto

- `MainActivity.kt`: Gerencia o ciclo de vida da tela principal e realiza a transação do fragmento.
- `ExemploFragment.kt`: Define a lógica e o conteúdo do fragmento.
- `activity_main.xml`: Define a estrutura visual da activity principal com um container para o fragmento.
- `fragment_exemplo.xml`: Define o layout visual do fragmento.

## ⚙️ Como executar

1. Clone este repositório.
2. Abra o projeto no **Android Studio**.
3. Certifique-se de que o SDK do Android está configurado corretamente.
4. Execute o app em um emulador ou dispositivo físico (recomendado: API 30+).

---
Desenvolvido como exemplo de aula para aprendizado de desenvolvimento Android.