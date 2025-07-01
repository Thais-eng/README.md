# Genes en Movimiento: La Historia Oculta de Canidae Revelada por CYTB

# Thais Tasiguano

# ¿CUÁL ES EL PROPÓSITO DE TU PROYECTO? 

El propósito de este proyecto es analizar la relación evolutiva entre especies domésticas de la familia Canidae (Canis lupus familiaris)
y sus parientes salvajes (Canis lupus, Canis latrans, Vulpes vulpes, Lycalopex culpaeus), 
mediante el análisis del gen mitocondrial (CYTB) el cual codifica la proteína citocromo b,
una parte esencial del complejo III en la cadena de transporte de electrones de la mitocondria. 

 ![ ](https://upload.wikimedia.org/wikipedia/commons/thumb/7/78/1l0l_opm.png/250px-1l0l_opm.png)

El gen CYTB se encuentra en el ADN mitocondrial de animales,plantas, hongos y protistas,etc.
Es fundamental para la producción de energía en las células.
Y es muy utilizado en estudios filogenéticos y análisis de evolución de especies.
Algo similar a lo que comprobrobaremos durante el desarrollo del proyecto.

# REQUISITOS PARA EL ANÁLISIS BIOINFORMÁTICO 

1. Conjunto de especies representativas del grupo Canidae.
2. NCBI GenBank:Para buscar las secuencias del gen mitocondrial cytochrome b.
3. BLAST: Nos permite verificar que las secuencias de ADN que se descargaron corresponden al gen CYTB y su especie.
4. MAFFT: Alinea las secuncias en FASTA.
5. IQ-TREE: Construye el árbol filogenético.
6. FigTree: Útil para visualizar y editar el árbol filogenético. 
7. Git + GitHub: Lo usamos como control de versiones y alojamiento del proyecto. 

![ ](https://www.muyinteresante.com/wp-content/uploads/sites/5/2024/05/25/6651af599f2a8.jpeg)

# CÓMO USAR EL PROGRAMA
1. Descargar las secuencias de los nombres de la especie (las que se hayan elejido) + “cytochrome b” en NCBI GenBank.
2. Descargamos en formato FASTA y  las guardamos en un arhivo.
3. Pegamos la  secuencia FASTA al BLAST para comprobar si el gen mitoncondrial corresponde al organismo que elegimos. 
4. Subimos nuestro archivo a MAFF y lo alineamos (guardamos con otro nombre).
5. Cargamos el module load iqtree/2.2.2.6 y ejecutamos el gen con iqtree2 -s <archivo_alineado_del_gen> -m MFP -bb 1000 -nt AUTO
6. Abrimos el documento (.treefile) que se genere y lo observamos en FigTree.
7. Comparamos y observamos a detalle todo el arbol y la influencia del gen mitocondrial en cada una de las especies.
8. Subimos los resultados al GitHub si es necesario con : git add,git commit,git push.

![ ](https://t4.ftcdn.net/jpg/09/29/92/81/360_F_929928124_KBVWfkmjAkLfc54PfFPfvea7jJb1F23D.jpg)


