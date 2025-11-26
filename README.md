📱 App de Cotação de Moedas

Um aplicativo Android desenvolvido em Kotlin, criado para consultar cotações de moedas em tempo real utilizando a API pública Frankfurter.

O app permite selecionar a moeda de origem, moeda de destino e um valor para conversão, retornando instantaneamente a taxa atualizada.

🏗️ Estrutura da Arquitetura
/app
 ├── java/com/example/cotacao
 │     ├── MainActivity.kt       # Tela principal e lógica da conversão
 │     └── ApiService.kt         # Interface Retrofit para acessar a API
 ├── res/layout
 │     └── activity_main.xml     # Layout da tela (inputs, botões, resultado)
 ├── res/values
 │     └── strings.xml           # Strings utilizadas no app
 └── AndroidManifest.xml         # Configuração geral do aplicativo


Principais pontos:

Uso de Retrofit para requisições HTTP

Interface simples em XML

Conversão realizada diretamente com os valores retornados da API

📸 Capturas de Tela

[aplicativo-cotacao-moedas.pdf](https://github.com/user-attachments/files/23777228/aplicativo-cotacao-moedas.pdf)

▶️ Como Usar

Abra o aplicativo no dispositivo ou emulador Android.

Selecione a moeda de origem e a de destino.

Digite o valor desejado.

Toque no botão para obter a cotação atualizada.

A conversão é feita automaticamente com os dados da API.

📚 Referências Utilizadas

Frankfurter API
https://www.frankfurter.app/docs/

Retrofit (Square)
https://square.github.io/retrofit/

Android Developer Documentation
https://developer.android.com/docs
