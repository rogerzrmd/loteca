# Projeto Loteca
É um simulador de loteria, no qual o usuário digita 6 números, realizando um sorteio de outros 6 números.
No final, é verificado o número de acertos

# Tecnologias Utilizadas
- **HTML**: estrutura do site
- _CSS_: estilo do site
- *_JS_* funções do site
- ~~BooStrap~~: não foi utilizado


# Melhorias Possíveis
1. [X] Subir para GitHubPages
2. [ ] Alterar os Alerts
3. [ ] Utilizar o bootstrap
4. [ ] Deixar Responsivo

### Disponibilizado em:
[GitHubPage](https://rogerzrmd.github.io/loteca/)

### Prints da tela
| ID | Primeira tela | Segunda tela |
|----|---------------|--------------|
| 1  | Loteca Limpa  | Loteca Preenchida |
| 2  | ![tela loteca não preenchida](https://user-images.githubusercontent.com/100212322/161781919-4f28ad20-45e9-4212-8bb2-498e664817c6.png) | ![tela loteca preenchida](https://user-images.githubusercontent.com/100212322/161782394-ed15b23d-f390-4a77-b20c-f9b92519297a.png) |

#### Função Principal 
```
function sorteio(){
    var cont = 0
    numSort = []
    while(cont < 6){
        let num = Math.random() * 60
        num = Math.ceil(num)
        if(!numSort.includes(num)){
            numSort[cont] = num
            console.log(numSort)
            cont++
        }
    }
```

#### Comando GIT
Para iniciar o projeto
```
git init
```
