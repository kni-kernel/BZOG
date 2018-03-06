# README - konwencje #

## Ogólne


## Graficy

* Do nazywania plików/obiektów graficznych używamy **sensownych** nazw angielskich (a nie *zegarek*, *cube* czy *ufok*)
* Pliki .blend (bądź inne graficzne) wrzucamy do `/3D stuff/<odpowiedni folder>`
* Grafiki 3D eksportujemy do plików .fbx, które wrzucamy do `/Unity project/Assets/Fbx/<odpowiedni folder>`
* **Po eksporcie grafiki 3D do .fbx, należy sprawdzić w Unity, czy wszystko zaimportowało się poprawnie (w szczególności animacje oraz tekstury - to drugie jest dość problematyczne i wymaga nałożenia z poziomu Unity)**
* Jeśli mamy model z nałożonymi teksturami, należy go wyeksportować do prefaba i zapisać w `/Unity project/Assets/Prefabs`

## Programiści

* Unity 5
* Visual Studio 2015
* Nasz wewnętrzny [code style guide](https://bitbucket.org/oculuskernelcrew/kernel-vr/wiki/Code%20style%20guide)
* **W kodzie który commitujemy, nie zostawiamy debug logów (chyba, że jest na to dobry powód)**

Warto zajrzeć na nasze [wiki](wiki/Home) - jeśli macie jakieś ciekawe źródła, możecie coś dodać