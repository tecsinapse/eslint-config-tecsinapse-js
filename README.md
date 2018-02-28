Projeto para padronizar a configuração do ESLint utilizada na TecSinapse para projetos JavaScript

# Exceções

Usar para console.log de pontos realmente importantes de ficarem no servidor
```javascript
// eslint-disable-next-line no-console
``` 
Usar em casos que realmente não faz sentido ter um caso padrão para o switch/case
```javascript
// eslint-disable-next-line default-case
```
Usar em pontos onde realmente não temos framework visual para suportar uma implementação simples
```javascript
// eslint-disable-next-line no-alert
```
Usar em pontos onde realmente os dados ficam apenas no cliente e são informações simples que possuem ciclo de vida maior do que o template
```javascript
// eslint-disable-next-line meteor/no-session
``` 