# Devo comprare un regalo da Amazon per Silvia

Ho una lista di idee regalo

- **SE NON** ho ancora elementi in lista
  - FINE
- **ALTIMENTI**
  - Prendo un oggetto dalla lista
    - **SE NON** ha consegna prime
      - Depenno dalla lista e torno al primo _SE NON_
    - **ALTRIMENTI**
      - **SE** è fuori budget
        - Depenno dalla lista e torno al primo _SE NON_
      - **ALTRIMENTI**
        - **SE NON** è un libro classico
          - Depenno dalla lista e torno al primo _SE NON_
        - **ALTRIMENTI**
          - Torno a FINE
