# Notes

Aplicatie android realizata pe versiunea de Android Oreo 8.1 ( API 27 ).
Aplicatia are ca scop crearea , editarea , stergerea si salvarea notitelor.
Folosim un ListView pentru a afisa toate notitele , fie existente sau create iar in momentul in care selectam o notita din lista , se va deschide o noua fereastra in care ni se permite editarea si salvarea modificarilor in momentul in care inchidem notita respectiva.
Pentru stergerea unei notite din lista , se va folosi termenul de "LongClick" in urma caruia va aparea un mesaj prin care ne intreaba daca suntem siguri sau nu sa stergem notita.
Pentru stocare am folosit obiecte de tipul "SharedPreferences" ce vor stoca notitele create , editate sau sterse , atat in timpul utilizarii aplicatiei cat si dupa inchiderea acesteia iar la repornire vom avea salvat ultima activitate in aplicatie.
