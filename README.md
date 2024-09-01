# TFG-Deep-learning-per-la-detecci-i-classificació-d-anomalies-en-imatges-toràciques
Aquest repositori conté el codi desenvolupat per al Treball de Final de Grau (TFG) de detecció d'anomalies en imatges mèdiques. El codi està organitzat en quatre seccions principals:

1)EDA + YOLO: Inclou l'Anàlisi Exploratori de Dades (EDA) i la implementació inicial de YOLO, juntament amb tècniques de data augmentation i weighted random sampler per equilibrar les dades.
2) Classificador sol: Conté un model de classificació binària per a imatges amb o sense troballes.
3)Classificador + YOLO: Presenta un enfocament combinat on el classificador filtra les imatges abans d'aplicar YOLO només a les imatges amb troballes.
4)Ensemble: Implementa un ensemble de models YOLO (YOLOv8n, YOLOv8s, YOLOv8m) per millorar la detecció d’anomalies.

Requeriments d'Instal·lació: 
1) Descarregar el codi: Descarrega els fitxers de codi del repositori.
2) Crear un compte a Kaggle: Registra't a Kaggle si encara no tens un compte.
3) Crear una notebook a Kaggle: Crea una nova notebook des del teu compte a Kaggle.
4) Carregar els fitxers de codi: Puja un dels fitxers descarregats a la notebook creada.
5) Executar el Codi: Fes clic a "Run All" per executar tot el codi.
