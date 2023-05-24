# Projekt Analizy Sentymentu
Ten projekt polega na budowaniu modelu analizy sentymentu przy użyciu tweetów na temat bieżących wydarzeń. Model przewiduje, czy tweet ma pozytywny, negatywny, czy neutralny sentyment.

# Projekt podzielony jest na cztery etapy:

# Etap 1: Zbieranie Danych
Ten etap obejmuje zbieranie danych i ich przetwarzanie. Korzystamy z gotowego zestawu danych, który zawiera tekst tweetów i odpowiadające im etykiety sentymentu. Przetwarzanie danych obejmuje czyszczenie tekstu i przekształcanie go do formatu odpowiedniego dla modeli uczenia maszynowego.

# Etap 2: Klasyczne Uczenie Maszynowe
Tutaj używamy tradycyjnych modeli ML, takich jak Naive Bayes, SVM i Random Forest do analizy sentymentu. Modele są trenowane i oceniane na podstawie ich dokładności, macierzy pomyłek i wyniku ROC-AUC.

# Etap 3: Model Neuronowy
Na tym etapie projektu projektujemy i trenujemy model oparty na dwukierunkowej sieci LSTM. Model korzysta z warstw osadzeń do efektywnej reprezentacji tekstu. Wydajność modelu jest monitorowana za pomocą zestawu walidacyjnego, a najlepszy model jest zapisywany na przyszłość.

# Etap 4: Model Języka
Na koniec wykorzystujemy model oparty na Transformerach, BERT, do analizy sentymentu. Model ten korzysta z wytrenowanego modelu BERT i dostosowuje go do naszego zestawu tweetów.

# Jak Korzystać?
Upewnij się, że zainstalowane są niezbędne zależności, w tym Python, TensorFlow, Keras, sklearn, pandas, re i transformers.

Aby uruchomić projekt umieść plik nlp_s18718_s15441 oraz Book3.csv w googlecloab, następnie po prostu uruchom skrypt. Końcowym wynikiem będzie dokładność, macierz pomyłek i wyniki ROC-AUC dla wytrenowanych modeli.
