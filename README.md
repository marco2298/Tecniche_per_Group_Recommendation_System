# Strategie per Group Recommendation System
Ho applicato diverse strategie per determinare raccomandazioni di gruppo in ambito cinematografico, è stato coinvolto un gruppo di 5 persone. Ho eseguito un confronto tra i risultati ottenuti utilizzando sia il dataset normalizzato che quello non normalizzato.
Le strategie prese in esame sono:

**Average**

**Average Without Misery**

**Least Misery**

**Most Pleasure**

**Utilitarian Strategy**

**Borda Count**

**Copeland rule**

**Approval Voting**

**DictatorShip**

**Fairness Strategy**

**Plurality Voting**

# OnlineStudy
Per valutare quale lista di film abbia prodotto il risultato migliore è stato effettuato uno studio online, chiedendo espliciamente a degli amici di valutare dei film. A questo punto attraverso la cosine similarity, per ogni partecipato è stato assegnato un userId presente nel dataset di partenza che abbia i gusti più simili possibili. Successivamente sono state applicate le 12 strategie sul gruppo scelto di id e chiesto ai 5 partecipanti di valutare quale elenco di titoli fossero più predisposti a seguitre.

# Dataset
Per il progetto ho utilizzato il dataSet da 100k di Movielens: https://grouplens.org/datasets/movielens/latest/

# Install Projct
git clone https://github.com/marco2298/Tecniche_per_Group_Recommendation_System/edit/main/README.md . Ho utilizzato google colab per eseguire il codice.

