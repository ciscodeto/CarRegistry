## Descrição
Aplicativo Android nativo em Kotlin para gerenciamento de dados de veículos. Consome API REST, salva dados localmente com Room e permite operações CRUD simples.

## Funcionalidades
- Consulta de montadoras e veículos via API
- Armazenamento local dos dados com Room
- Inserção, atualização exclusão manual de veículos
- Interface amigável com tratamento de erros

## Tecnologias
- Kotlin como linguagem de desenvolvimento
- Room para armazenamento em banco local
- Ktor para chamadas de API
- Koin para injeção de dependência
- Jetpack Compose para UI

## Como rodar
1. Clone o repositório
2. Abra no Android Studio
3. Crie na pasta ```app/``` um arquivo vazio nomeado exatamente como: ```local.properties```
4. Escreva no arquivo ```local.properties``` que deve estar vazio o texto a seguir: 
    - ```BASE_URL=```
    - **Importante: Agora, na frente do sinal de igual (=), você precisa colar o endereço completo da API que o aplicativo usará.**
    - Exemplo: Se o endereço for ```https://api.meusite.app```, a linha deve ficar assim:
    ```BASE_URL=https://api.meusite.app```
6. Execute em um emulador ou dispositivo

## APK
Você encontra o APK compilado na pasta `apk/`
