Main
int intentos = 5;
bool adivinado = false;
int numeroSecreto = random.Next(1,101);
int intentoJugador;
escribir en consola "Adivina un numero"
numeroSecreto = Random(0,101)
while (intentos > 0 && !adivinado)
       Leer intentoJugador
       if(intentoJugador > numeroSecreto && intentoJugador ≠ numeroSecreto)
          imprimir "Numero alto"
          --intentos
       Finif
       if (intentoJugador < numeroSecreto && intentoJugador ≠ numeroSecreto)
          imprimir "Numero bajo"
          --intentos
       Finif
       if (intentoJugador = numeroSecreto)
          imprimir "Felicidades, lo lograste"
          adivinado = TRUE
       Finif
fin while

        FinMain