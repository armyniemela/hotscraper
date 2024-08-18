# Hotscraper

1. Skreippaan Jupyter Notebookissa pd.read_html -koodipätkällä Bad weather -verkkosivulta kaksi taulukkoa <table>, jotka listaavat kuumimpia lämpötiloja
   - https://badbadweather.com/high-temp
2. Siivoilin taulukot Notebookissa ja tein niistä csvt
3. GIT hubiin repository, kamat sinne ja Action ajamaan koodin, joka hakee tiedon 2 x päivässä.
   *muista päivittää oikeat tiedostonimet sekä laitta cron-toiminto haluamaasi ajastukseen (tässä klo 12 ja 00)
