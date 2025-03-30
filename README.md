# Compose Multiplatform

Wizard: https://kmp.jetbrains.com/?_gl=1*1vczkqk*_gcl_au*MTU0NTA2MzEzMy4xNzM4NzEzMzM3*FPAU*MTU0NTA2MzEzMy4xNzM4NzEzMzM3*_ga*MTQ0MTkyNDgzNi4xNzIzNTEyNjU0*_ga_9J976DJZ68*MTc0MzI0MzE0MC42LjEuMTc0MzI0MzM3NC42MC4wLjA.<br>
<br>
DOC1: https://www.jetbrains.com/help/kotlin-multiplatform-dev/compose-multiplatform-create-first-app.html#examine-the-project-structure<br>
<br>

## Resumo

Instale o ambiente de acordo com as necessidades<br><br>
Crie o projeto utilizando o wizard, baixe e abra no Android Studio<br><br>
O projeto possui 2 modulos: composeApp - compartilha a lógica entre android, ios, web, etc.; iosApp - se tiver ios<br><br>

![image](https://github.com/user-attachments/assets/cae3c3af-841f-46ab-a170-f077327e3855)<br>
<br>

### Executar no Desktop

Abra Run | Edit Configurations <br><br>
Clique em + e selecione Gradle no final da lista <br><br>
No campo Tasks and arguments, coloque este comando: <br>
    composeApp:run<br>
<br>
### Executar Versão Web

Reproduza os mesmo passos do desktop, mas inclua este comando:<br>
    wasmJsBrowserRun -t --quiet<br>

    
