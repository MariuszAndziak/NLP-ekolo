## Wstęp do projektu analizy językowej budżetów partycypacyjnych 
Dane z katalogu 'inputs' pochodzą od: https://github.com/maryanoo/NLP-ekolo

Realizacja w ramach projektu NLP grupy Warszawsko-Międzymiastowo-Międzynarodowej
https://github.com/DataWorkshop-Foundation/WMM-NLP-project

## 00_ideas_and_issues.ipynb
Wstępny notatnik obrazujący potencjalne możliwości analizy.
* Początkowa analiza tematów za pomocą UMAP i HDBSCAN

## 02_bertopic_colab.ipynb
Użycie Bertopic i wyodrębnienie tematów z nazw budżetów. 
* Ograniczenie ilości tematów do 20
<img src="images/clustering.png">
<img src="images/word_scores.png">

## 03_lda.ipynb
Użycie LDA jako alternatywnej metody pozyskania tematów.
<img src="images/lda.png">

## 04_bonus_top2vec_vis.ipynb
Zastosowanie modelu Top2Vec
* Wytrenowanie modelu
* Wizualizacja tematów
* Użycie embeddingów, aby znaleźć podobieństwa między tematami


## 05_visualisation_map.ipynb
Utworzenie mapy z wizualną reprezentacją tematów
* Budżety partycypacyjne miały informacje z jakich miast pochodzą, co umożliwiło połączenie tego z utworzonymi wcześniej tematami i zwizualizowanie jakie regiony kraju posiadają poszczególne rodzaje budżetów
<img src="images/Animation.webp">
