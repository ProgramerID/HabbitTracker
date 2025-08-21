# README
# Habit Tracker

Aplicativo simples para acompanhar hábitos diários como leitura, estudo, beber água e treino.

Cada hábito concluído rende pontos e faz o usuário subir de nível, tornando o acompanhamento mais divertido.

## Uso (linha de comando)

```bash
python habit_tracker.py
```

Escolha uma opção do menu para marcar hábitos, ver o status do dia ou consultar seus pontos e nível.

## Interface móvel (iOS/Android)

O arquivo `mobile_app.py` utiliza [BeeWare Toga](https://beeware.org/) para fornecer uma interface amigável que pode ser empacotada para iOS ou Android.

Para testar no desktop:

```bash
python mobile_app.py
```

Para gerar um aplicativo móvel, instale o `briefcase` e siga a documentação do BeeWare para criar e executar o app no iPhone ou em dispositivos Android.

## Testes

```bash
pytest
```