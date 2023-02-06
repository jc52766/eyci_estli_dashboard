Daily eyci and estli downloaded from MLA website:http://statistics.mla.com.au/Report/List<br><br>
create virtual env and install requirements e.g.:<br>
python -m venv venv<br>
source venv/bin/activate<br>
pip install -r requirements.txt<br><br>
To serve app locally:<br>
panel serve --show eyci_estli.ipynb<br>
To deploy to app engine:<br>
gcloud app deploy .\app.yaml
