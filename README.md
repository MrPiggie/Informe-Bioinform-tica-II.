# Informe Bioinformática II.
Luciano Frez

# **Parte I**

**¿Qué función cumple el gen SRY?**

    Cumple funciones de unión de DNA, calmodulina vinculante, Actividad del factor de transcripción, ARN polimerasa II potenciador   distal   secuencia específica de unión y de Factor de transcripción vinculante.

**¿Cuántos genes ortólogos están anotados en esa base de datos?**

    Hay 26 genes ortólogos anotados en la base de datos.

# **Parte II**

**¿Qué es el EMBL-EBI?**

    En el Instituto Europeo de Bioinformática (EMBL-EBI). entregan a la  comunidad científica datos biológicos públicos del mundo a través de una gama de servicios y herramientas, realizan investigaciones básicas y ofrecen formación profesional en bioinformática. **(1)** 

**¿Cuántos tipos de alienamiento múltiple se pueden realizar en EMBL-EBI?**

      Tiene 7 tipos de secuanciadores de alineamiento múltiple, tales como: Clustal Omega, Kalign, MAFFT, MUSCLE, Sequence Alignments(también pude bisualizar alineamientos), T-Coffee y UniProt Align.

**¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas?**
        
        El programa que ellos ofrecen que funciona mejor para secuencias de proteínas es el MUSCLE, el cual consigue una mejor exactitud media y una mejor velocidad que ClustalW2 o T-Coffee

**¿Qué otros tipo de herramientas ofrece EMBL-EBI?**

    EMBL-EBI ofrece otros tipos de herramientas para buscar: estructuras moleculares, DNA back.translation, secuaencias similares, CpG island and isochore detection, Pairwise sequence alignment(para alineamiento local y global), Protein property calculation, Protein hydropathy calculation entre otros.

**¿Cuál es el costo de abrir un gap?**

    El costo de abrir un GAP es de 1.53.

**¿Cuál es el costo de extender un gap?**

    El costo de extender un GAP es de 0.123.

**¿Cuál es la longitud total del alineamiento?**

    La longitud total del alineamiento es de 1923 T 8%

**¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos?**

    La especie cuyo gen SRY está más relacionado con el gen SRY de los humanos es el Pan_troglodytes

**¿Cuál es el más lejano?**

    La especie cuyo gen SRY está más lejano con el gen SRY de los humanos es el Pteropus_alecto

**¿Cuál es la especie cuyo gen SRY es más cercana a la del burro?**

    La especie cuyo gen SRY es más cercana a la del burro es la Equus_przewalskii

**¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye?**

    Si el valor de penalización por abrir gaps aumenta, el programa colocará una menor cantidad de gaps, pero de mayor longitud cada uno. Y si disminuye la penalización, el programa colocará una mayor cantidad de gaps de un tamaño menor](extensión de gaps) para así lograr que las secuencias puedan ser comparables respecto al largo de estas.

**¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye?**

    Si el valor de penalización por extender gaps aumenta, el programa utilizará gaps de mayor longitud para no extenderlos y así impedir la penalización de abrir uno nuevo. Por el contrario, si el valor disminuye, el programa hará uso de la facultad para extender gaps, colocando gaps de menor longitud.
    
*Prueba aumentando el costo de abrir gaps cambiando el valor de 1.53 a 2.0*

**¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento?** 

    El efecto de aumentar el costo de abrir un gap(1.53 a 2.00) en la longitud del alineamiento fue nulo. Esto es probablemente a que los dominios que conforman la proteína homóloga estén conservados evolutivamente. Para el valor mínimo de extender un gap(0,1), el resultado fue que la longitud total del alineamiento disminuyó de 1932 a 1907. Esto es porque los gaps que se abrieron son de menor longitud.
    
*prueba lo mismo pero esta vez disminuyendo al mínimo el costo de extender un gap. Describe cómo cambia el alineamiento*

# **Parte III**
   
![imagen 1](https://github.com/MrPiggie/Informe-Bioinform-tica-II./blob/master/primers.fasta.png?raw=true)

**Imagen I:** Primers para las secuencias de Chlorocebus sabaeus, Homo sapiens, Pan troglodytes y Macaca Mulatta. 

# **Bibliografía:**

(1) http://www.ebi.ac.uk/about
