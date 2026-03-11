Pseudocódigo de BFS 

BFS(Grafo, Inicio)
    crear conjunto Visitados
    crear cola Cola
    agregar Inicio a Visitados
    encolar Inicio en Cola
    mientras Cola no esté vacía hacer
        NodoActual ← desencolar de Cola
        mostrar NodoActual
        para cada Vecino en Grafo[NodoActual] hacer
            si Vecino no está en Visitados entonces
                agregar Vecino a Visitados
                encolar Vecino en Cola
            fin si
        fin para
    fin mientras
Fin BFS
