abstract arch intro 3

Partiamo dal vedere l'archittettura sequenziale, veremo come funzioelementi di ottimizzazione di essa. òoi vedremo la forma a livello più basso di parallelismo (istruction e harware level parallelism) per poi vedere le principali architetture parallelism

von neumann arch p5
caching p10
instuction levele parallelism p29
hardware multith p31


# Hardware multitreading:
due tipi:
- simultaneous multithreading (SMT): è un'implementazione del fine-graned multithreading dove thread differenti possono usare più unità processuali allo stesso tempo.
- hypoertreading: è l'implementazione intel del sMT:
  - ogni processore fisico di core è visto al sitema operativocome due processori logici
  - ogni processore "logico" mantiene un set completo dello stato edll'architetture ( quinidi di tuttti? i tipi di regitro)
  - intel dice che si ha uno speedup del 15-30%

Nel edttaglio l'hyper treading: p33


# Architetture parallelismo
la tassonomia di flynn p36
Le architetture possibili sono:
- sisd (von noeuman)
- misd 
- simd
- mimd (caso raro): multiple unità esecutive che possono eseguire multiple sequenze di istruzione e generalmente che operano su dati riservati tra le varei unità esecutive. Possono essere sia a memoria condivisa che distribuita


poi abbiamo delle architetture ibride: p48

vantaggi e vantaggi della shared e distributed memory p51
ruel of thum p50
