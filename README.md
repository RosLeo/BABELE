# Spoken-Language-Recognition-without-Audio
Spoken Language Recognition without Audio. It's my computer vision project for the exam, together with my colleague Rosaria Leone. Our dataset consisted of 960 videos in the training set, 160 in the test set, and 160 in the validation set. The dataset contains videos in 8 languages: Italian, English, German, Spanish, Dutch, Russian, Japanese and French. Our goal was to use a recurrent neural network combined with the "Feature Level Fusion" technique to obtain a video classification.

Di seguito illustrerò il significato di ogni singolo script presente nell repository:

Spiegazione di ciò che implementa ogni singolo script:

* Conv_SIMS_MOSEI: all'interno di questo script è presente l'implementazione della rete neurale utile ad addestrare il set di dati chiamato SIMS_MOSEI
* ConvLstm2d: questo script contiene l'implementazione della rete usata per addestrare il set di dati BABELE
* ConvLstm2d_GS: la rete neurale implementata è sempre applicata sul set di dati BABELE, con la differenza che le immagini di input sono non a colori ma gray scale
* csv_predizioni_errate: contiene il codice per generare i csv contenenti le previsioni corrette e l'etichetta che, erroneamente, gli è stata associata
* Feature_Level_Fusion_classificazioni: in esso è racchiuso il codice dal quale otteniamo le accuratezze finali dando in input alla batteria 








