Daily eyci and estli downloaded from MLA website:

http://statistics.mla.com.au/Report/List

create virtual env and install requirements e.g.:

python -m venv venv

source venv/bin/activate

pip install -r requirements.txt

To serve app:

panel serve --show eyci_estli.ipynb
