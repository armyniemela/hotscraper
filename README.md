# Hotscraper

1. Skreippaan Jupyter Notebookissa pd.read_html -koodipätkällä Bad weather -verkkosivulta kaksi taulukkoa <table>, jotka listaavat kuumimpia lämpötiloja
   - https://badbadweather.com/high-temp
2. Siivoilin taulukot Notebookissa ja tein niistä csvt
3. Tein githubiin repositoryn, vein oikean kansion kamat sinne, ja ajoin Action-toiminnolla ipyn-tiedoston, joka hakee tiedon 2 x päivässä (cron-toiminto).
   *muista päivittää oikeat tiedostonimet sekä laitta cron-toiminto haluamaasi ajastukseen (tässä klo 12 ja 00)
4. Tein datawrapperilla taulukot, joiden tieto viedään raw-linkin kautta githubista.
5. Index-verkkosivu, jonka koodiin lisätään datawrapper-koodi.
6. Hostaan verkkosivua omassa githubissa.
