# Subnetting
Subnetting è il processo di suddivisione di una rete IP in sotto-reti più piccole chiamate subnet. 

La suddivisione di una rete IP in subnet consente di assegnare porzioni di indirizzi IP a gruppi di dispositivi collegati alla stessa sottorete dove ogni subnet avrà il proprio intervallo di indirizzi IP univoco, ciò consente di limitare il traffico di rete e migliorare l'efficienza delle comunicazioni all'interno delle subnet.

L'indirizzo IP di una rete viene composto da due parti: l'indirizzo di rete e l'indirizzo di host, si usa il concetto di subnetting se è possibile modificare la lunghezza del prefisso di rete (netmask) per creare sotto-reti più piccole.
Per effettuare il subnetting tra le reti ho seguito questi passaggi:

Scelto il numero di subnet necessarie, sapendo il numero di reti che sono da creare e identificare la quantità di indirizzi IP necessari per ciascuna subnet.

Ho scelto la classe di indirizzo IP, quindi se utilizzare un indirizzo IP di classe A, B o C.

Scegliere una subnet mask, determinare la subnet mask appropriata in base al numero di subnet e agli indirizzi IP richiesti per ciascuna subnet: La subnet mask determina il numero di bit utilizzati per l'indirizzo di rete e l'indirizzo di host.

Calcolare il numero di bit per l'indirizzo di rete, quanti bit di host verranno utilizzati per ogni subnet e calcolare il numero di bit necessari per l'indirizzo di rete.

Calcolare il numero di indirizzi IP per subnet, utilizzando i bit riservati all'indirizzo di host e calcolare il numero di indirizzi IP disponibili per ciascuna subnet.

Assegna gli indirizzi IP alle subnet: Utilizzando gli indirizzi IP disponibili e i blocchi di indirizzi IP assegnati a ciascuna subnet, assegna gli indirizzi IP a ciascuna subnet.
Nell’ esercizio di subnetting abbiamo due sottoreti differenti della stessa dimensione con lo scopo di riuscire a fare comunicare tutti i computer tra di loro.
Inizialmente i PC delle due reti non si raggiungevano con ping perchè nella configurazione dei computer bisognava andare a inserire nel gateway dei pc, l’indirizzo ip dello switch al quale erano collegati.

