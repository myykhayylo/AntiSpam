# AntiSpam ML Model
Il progetto si propone di implementare il modello Naive Bayes senza ricorrere a librerie esterne. In particolare, il modello di machine learning mira a classificare se un messaggio è considerato spam o ham.

<h2>Dettagli sul progetto</h2>
Il modello implementato si basa sulla formula di Bayes, tale formula ci dice che:
<br>
<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*GdSYgE8NxZw1XzK5KZ03lg.png"  width="400" height="180" />
<br>
dove P(A|B) indica la probabilità che l'evento A si verifichi sapendo che B si sia già verificato.
Utilizzando tale formula possiamo ricondurci a questo caso:
<br>
<img src="img/ProbSpamDatoParole.png" width="500" height="180" />
è possibile trovare la dimostrazione per cui tale proposizione sia vera nel file SpiegazioneProgetto.docx
<br>
<h3>Cosa ci dice questa proposizione?</h3>
Tale proposizione puo essere letta come, la probabilità che date certe parole (w<sub>1</sub>, w<sub>2</sub>, ... ,w<sub>n</sub>), tali siano Spam è direttamente proporzionale al prodotto tra la probabilità che il messaggio sia spam (P(Spam)) e la produttoria delle probabilità che una parola i-esima  w<sub>i</sub> sia Spam (P(w<sub>i</sub>|Spam))
<br>
<br>
Il progetto si conclude mostrando un esempio del come il modello funziona e calcolandone l'accuratezza.  

