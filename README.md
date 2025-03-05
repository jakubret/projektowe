# Rozpoznawanie Części Twarzy 🧑‍💻🔍

## Opis projektu  
Projekt koncentruje się na analizie i rozpoznawaniu części twarzy osób, które mają zasłoniętą dolną połowę twarzy. W ramach badań przeprowadziliśmy przegląd istniejących algorytmów oraz testowaliśmy różne podejścia do reprezentacji cech twarzy.  

## Główne założenia  
- **Analiza osadzonych reprezentacji twarzy (embeddingów)** – porównanie i testowanie różnych metod ekstrakcji cech.  
- **Przegląd istniejących algorytmów** – m.in. MTCNN, FaceNet, VGG-Face, OpenFace.  
- **Implementacja i testy** – wykorzystanie modelu **FaceNet** do ekstrakcji embeddingów i ich analizy.  
- **Ocena skuteczności** – testowanie różnych podejść do rozpoznawania przy częściowym zakryciu twarzy.
- **Baza danych** - stworzyliśmy bazę zdjęć używająć MaskTheFace w celu zasłonięcia części twarzy

## Technologie  
- **Python** – główny język programowania  
- **TensorFlow / Keras** – implementacja FaceNet  
- **OpenCV** – wstępna obróbka obrazów  
- **NumPy / Pandas** – analiza danych  

## Jak uruchomić?  
1. **Klonowanie repozytorium:**  
   ```bash
   git clone https://github.com/uzytkownik/projektowe.git
   cd projektowe
