Stabilizator de tensiune cu element de reglaj serie

Cu ajutorul programelor OrCAD, PSpice si PCBEditor am proiectat un stabilizator de tensiune cu element de reglaj serie respectand urmatoarele conditii:  
      -Tensiunea de la iesire reglabila in intervalul 6V - 12V   
      -Sarcina la iesire de 480 ohmi  
      -Deriva termica mai mica de 2mV/grad Celsius  
      -Protectia la suprasarcina prin limitarea temperaturii tranzistorului regulator serie la 120 grade Celsius si a curentului maxim la 0.5A  
      -Tensiunea de intrare in intervalul 21,6V - 24V  
      -Amplificarea in tensiune minima (in bucla deschisa) a amplificatorului de eroare minim 100    
      -Domeniul temperaturilor de functionare 0 - 60 grade Celsius    
      -Semnalizarea prezentei tensiunilor de intrare/iesire cu o dioda de tip LED  

De-a lungul proiectului am intampinat multe probleme de proiectare. Probabil cea mai des intalnita a fost puterea disipata pe rezistoare. Aceasta nu trebuia sa depaseasca 125 mW, dar pentru a fi sigur, am optat pentru o putere disipata maxima de aproximativ 100 mW. Pentru a rezolva aceasta problema am apelat la "spargerea" rezistoarelor in mai multe rezistoare de rezistenta egala. Astfel, puterea disipata pe acestea s-a incadrat in normele impuse.

O alta problema intampinata a fost plasarea ideala a componentelor: cele active ce disipa cea mai multa putere sa fie plasate in mijlocul PCB-ului, iar cele pasive pe marginea acestuia. Astfel au aparut alte probleme cum ar fi trasarea rutelor optime, fara unghiuri de 90 de grade, respectarea dimensiunii vias-urilor si a marker-ilor fiduciali. Toate aceste aspecte au dus la multiple reincercari de proiectare a PCB-ului, pana cand in final s-a ajuns la o forma aproximativ optima.








