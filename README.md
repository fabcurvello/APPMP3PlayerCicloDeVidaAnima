# App MP3 Player com Ciclo de Vida (Anima)

> Repositório didático: exercício prático de Android nativo com **Java**, desenvolvido e aplicado em sala de aula pelo Prof. Fabricio Curvello.

## Sobre o projeto

Player de música simples que usa os métodos do **ciclo de vida da Activity** para pausar e retomar a música automaticamente.

## Contexto acadêmico

Exercício aplicado em sala de aula em turma de desenvolvimento mobile do grupo **Ânima Educação**. A Ânima Educação é um conglomerado de instituições de ensino superior brasileiras, do qual fazem parte o Centro Universitário IBMR (Rio de Janeiro) e a UNA (Minas Gerais).

## O que o app faz

- Botão **Play/Pause** que toca ou pausa uma música guardada no próprio app (`res/raw`).
- Quando o app sai da tela (`onStop`), a música é pausada.
- Quando o usuário volta (`onStart`), a música é retomada se estava tocando antes.
- O `MediaPlayer` é liberado em `onDestroy` para não desperdiçar recursos.

## Conceitos trabalhados em aula

- **Ciclo de vida da Activity** aplicado a um caso real
- Reprodução de áudio com `MediaPlayer`
- Recursos de áudio em `res/raw`
- Controle de estado com variável booleana
- Liberação de recursos (`release()`)

## Tecnologias

- **Java**
- **Android SDK** (Android Studio)
- **Gradle**
- `MediaPlayer`
- `minSdk 28` / `compileSdk 34`

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/fabcurvello/APPMP3PlayerCicloDeVidaAnima.git
   ```
2. Abra a pasta no **Android Studio** e aguarde a sincronização do Gradle.
3. Execute em um emulador ou dispositivo físico com Android compatível com a API 28 ou superior.

## Veja também

Outros repositórios de aula com o mesmo tema:

- [AppMP3PlayerCicloDeVidaAnimaUNA](https://github.com/fabcurvello/AppMP3PlayerCicloDeVidaAnimaUNA)
- [AppCiclodeVidaAnimaUna](https://github.com/fabcurvello/AppCiclodeVidaAnimaUna)
- [AppCicloDeVidaAnima](https://github.com/fabcurvello/AppCicloDeVidaAnima)

## Autor

**Fabricio Curvello**: professor de desenvolvimento de software no SENAI-RJ (desde 1997) e em faculdades do grupo Ânima Educação (IBMR e UNA).

- GitHub: [github.com/fabcurvello](https://github.com/fabcurvello)
- LinkedIn: [linkedin.com/in/fabriciocurvello](https://www.linkedin.com/in/fabriciocurvello)
- YouTube: [@fabriciocurvello](https://www.youtube.com/@fabriciocurvello)
