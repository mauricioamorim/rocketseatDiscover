# Distâncias absolutas <lenght>

São fixas e não alteram seu valor.

Unidade     Nome                Equivalência
cm          Centímetros         1cm = 96px/2.54
in          Inches (polegadas)  1in = 2.54cm = 96px
px          Pixels              1px = 1/96th of 1in

* o mais comum e mais utilizado é o **px**
* não recomendado usar cm


# Distâncias relativas

São relativas a algum outro valor, pode ser o elemento pai, root, ou o tamanho da tela.

* Benefício: Maior adaptação aos doferentes tipos de tela

Unidade     Relativo a
em          Tamanho de font do pai.
rem         Tamanho da font do elemento raiz (root/html)
vw          1% da viewport width (relação horizontal da janela e não do elementos html)
vh          1% da viewport height.(relação vertical da janela e não do elementos html)
