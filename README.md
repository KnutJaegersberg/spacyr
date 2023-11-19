# spacyr
a hacked spacyr version to work without anaconda

Point it to your spacy install 

python -m venv /home/knut/spacyr 

pip install -U 'spacy[cuda12x]'



  python -m spacy download en_core_web_trf

You also want to tell spacy to use the gpu by default, i.e. by adding prefer_gpu() in the init.py as shown in the file here in the repo. 

  library(spacyr)



  spacy_initialize(model = "en_core_web_trf", virtualenv = "/home/knut/spacyr/")
