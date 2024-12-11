1) открой powershell:
```bash
  dotnet --version
```
если выдает ошибку или версия не 8, то лучше на всякий случай установить 8:
https://dotnet.microsoft.com/ru-ru/download/dotnet/8.0

2) Создаешь папку sisir, открываешь её в редакторе кода и запускаешь команды по отдельности:
```bash
git clone https://github.com/lsiiel/sisirProject.git
```
```bash
dotnet workload install maui
```
```bash
dotnet build
```
```bash
dotnet run --framework net8.0-maccatalyst
```
