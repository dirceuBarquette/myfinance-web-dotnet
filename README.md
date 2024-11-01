# myfinance-web-dotnet

Projeto da disciplina Práticas de Implementação e Evolução de Software - PUC-MG

Preparação do ambiente Linux para uso do .NET
- pacote dotnet-sdk-8.0 disponível para distribuição OpenSuse Tumbleweed
- instalação via zypper
- houve necessidade de resolver dependência com instalação avulsa do pacote libopenssl1_0_0-1.0.2k-1.1.x86_64.rpm pois estava indisponível nos repositórios em uso

Pós instalação do .Net
- instalação por linha de comando do framework MVC ASP.NET

```
dotnet new mvc --name myfinance-web-dotnet
```
Obs. Caso o diretório do projeto já exista, o comando acima deve ser executado 1 nível acima do mesmo sem prejuízo do mesmo.

Sobre o uso do VS Code
- instalar extensão recomendada
- depois:

```
dotnet build
```


```
dotnet run
```
