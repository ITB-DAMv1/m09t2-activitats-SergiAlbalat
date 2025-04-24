[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/LXcrfC_Y)

## Repositori Activitats

[Repositori](https://github.com/SergiAlbalat/M09T2Activitats)

## Exercici 1:
### 1. Process:
   
   #### Es una classe que pot interactuar amb processos del sistema operatiu, alguns dels seus metodes són:
   - Start()
   - Kill()
   - GetProcesses()
   - GetCurrentProcess()
### 2. Stopwatch:

   #### Es una classe per poder medir temps d'execució, alguns dels seus metodes són:
   - Start()
   - Stop()
   - ElapsedMilliseconds()
   - Reset()
### 3. Trace:

  #### Es una classe per poder depuració de forma més senzilla i eficient, alguns dels seus metodes són:
  - TraceInformation(string message)
  - TraceWarning(string message)
  - TraceError(string message)
  - Listeners()

## Exercici 3(Explicació):

Els navegadors moderns tenen una arquitectura multiproces, multifil que permet que nomes es crein processos nous al obrir pesatnyes, aixo provoca que apareguin nous fils

## Exercici 4:

| Thread | Task |
|:--------------------------|----------------------------:|
|Start(): Iniciar un nou fil|Task.Run(): Iniciar una Tasca|
|Sleep(int): Suspendre un fil durant un temps especific|Delay(int): Equivalent a sleep però te un millor control per evitar el bloqueig del fil|
|Join(): Bloqueja el MasterThread fins que el fil acaba|Wait(): Similar a Join però per tasques|
|Priority: Dona prioritat al fil|ConfigureAwait(bool): Cambia com es tractada la tasca en l'ordre d'execució|

## Exercici 5:

### A)

S'imprimeixen amb ordre aleatori perque segueixen un ordre de prioritat que el sistema operatiu decideix.


