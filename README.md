# site-translate
Tradução de páginas de site em tempo real

### Finalidade
Este script visa fazer a tradução do seu site com apenas um clique do usuário, sem a necessidade de replicar várias vezes o mesmo conteúdo para cada idioma que se deseja exibir a página, sem limite de quantidade de idiomas!

---
### Filosofia
FUNCIONAR, sem dogmatismos, apegos ideológicos, culturais ou filosóficos de qualquer natureza.

Ah! sem trauma e sem teoria! ;)

---
### Como funciona?
Os botões com os idiomas chamam a função idioma() do javaScript previamente carregado pela página. O script faz algumas verificações e lê o dicionário dic.json e busca nesse dicionário o código html de cada elemento da página, no idioma atual.
Uma vez encontrado o trecho de código do elemento html dentro do dicionário, ele substitui o código pelo novo idioma, passado por parâmetro para a funcão idioma().

---
### Não entedi! Pode explicar mais detalhadamente?
Claro que sim!
Vamos analisar o código e seu funcionamento, passo a passo...

(discorrer)

---
### Instalação
- Copiar as pastas /js e /dic para a raiz do site que se deseja traduzir;
- Criar os botões para os idiomas desejados nas páginas onde se quer a tradução em tempo real;
- Abastecer o dicionário **/dic/dic.json** com os trechos de códigos que se deseja traduzir.
---

E seja feliz!
---

---
### Referências

---
