Main

int intentos = 3 //para ver los tres intentos
string jugador  //para saber lo que escribe el usuario
string compu //para saber lo que escribe la compu
bool ronda = false //para saber si gano la ronda
int rondasCompu //para saber las rondas ganadas por la compu
int rondasJugador //para saber las rondas ganadas por el jugador

imprimir "Elige piedra, papel o tijeras: "
compu = Random(Piedra, Papel, Tijeras)

while(intentos > 0 )
  leer jugador
if(jugador = Piedra && compu = Papel)
  imprimir "La compu gana esta ronda"
  --intentos
fin if

fin while

FinMain