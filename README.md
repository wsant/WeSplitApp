# 📱 WeSplit - Projeto 1 do "100 Days of SwiftUI"

Este é o primeiro projeto prático desenvolvido durante o curso **[100 Days of SwiftUI](https://www.hackingwithswift.com/100/swiftui)** de Paul Hudson. O objetivo é construir um aplicativo funcional para iOS que calcula a divisão de uma conta de restaurante, incluindo gorjetas.

Este repositório serve como um registro do meu progresso e da aplicação dos conceitos fundamentais de Swift e SwiftUI aprendidos nos primeiros 15 dias do curso.

## 🚀 Funcionalidades

O aplicativo permite ao usuário:

* **Inserir o valor total da conta:** Um campo de texto formatado para a moeda local do usuário.
* **Selecionar o número de pessoas:** Um seletor para dividir a conta entre 2 a 99 pessoas.
* **Escolher a porcentagem de gorjeta:** Um seletor que abre uma nova tela com opções de 0% a 100%.
* **Ver o cálculo em tempo real:**
    * O valor total que cada pessoa deve pagar.
    * O valor total da conta (valor original + gorjeta).

## ✨ Destaques Técnicos

Este projeto foi uma introdução prática a vários dos pilares do SwiftUI:

* **`@State` e `@FocusState`:** Para gerenciar o estado da aplicação de forma reativa, atualizando a interface automaticamente a cada mudança.
* **Bindings de Mão Dupla (`$`):** Conectando os controles da UI (como `TextField` e `Picker`) diretamente às nossas propriedades `@State`.
* **Views e Modificadores:** Utilização de `NavigationView`, `Form`, `Section`, `Picker` e `ForEach` para construir uma interface de usuário estruturada e com aparência nativa.
* **Propriedades Computadas:** Isolamento da lógica de cálculo (`totalPerPerson`, `totalAmount`) do código da interface, tornando o `body` mais limpo e legível.
* **Formatação de Dados:** Uso de `.currency` e `.percent` para apresentar os dados de forma amigável e localizada para o usuário.

## 🛠️ Tecnologias Utilizadas

```swift
- Swift 5
- SwiftUI
- Xcode
