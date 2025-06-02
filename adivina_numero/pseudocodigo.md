Main

int intentos = 7 //guardar intentos del usuario
bool adivinando = false //para saber si ya adivino el numero
int numeroSecreto = random.Next(1, 101) //aquí almaceno num aleatorio
int jugador //aquí guardo el num dado por el jugador

escribir en consola "Adivina un numero"
numeroSecreto = Random(0,101)

while(intentos > 0 && !adivinando)
  leer jugador
  if(jugador > numeroSecreto && jugador =/ numeroSecreto)
  imprimir "Demasiado alto"
  --intentos
  fin if
  if(jugador < numeroSecreto && jugador =/ numeroSecreto)
  imprimir "Demasiado bajo"
  --intentos
fin if
  if (jugador = numeroSecreto)
  imprimir "Felicidades, lo lograste"
  adivinando = true
fin if
fin while

FinMain