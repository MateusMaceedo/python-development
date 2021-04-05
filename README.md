<h1 align="center">
<img src="https://www.python.org/static/img/python-logo.png" width="290" height="82">
 <br>
 Python Development Data Science
</h1>

- [Programming Python](http://nbviewer.jupyter.org/github/phelps-sg/python-bigdata/blob/master/src/main/ipynb/intro-python.ipynb)
- [Numerical Computing](http://nbviewer.jupyter.org/github/phelps-sg/python-bigdata/blob/master/src/main/ipynb/numerical-slides.ipynb)
- [Relational Data](http://nbviewer.jupyter.org/github/phelps-sg/python-bigdata/blob/master/src/main/ipynb/relational-python.ipynb)
- [Analysing structured data using pandas](http://nbviewer.jupyter.org/github/phelps-sg/python-bigdata/blob/master/src/main/ipynb/pandas.ipynb)
- [Map-Reduce programming and Apache Spark](http://nbviewer.jupyter.org/github/phelps-sg/python-bigdata/blob/master/src/main/ipynb/spark-mapreduce.ipynb)
- [Column-oriented databases with HBase and HappyBase](http://nbviewer.jupyter.org/github/phelps-sg/python-bigdata/blob/master/src/main/ipynb/hbase-python-slides.ipynb)
- [Learn Python](https://learnxinyminutes.com/docs/python/)
- [DataSciene](https://www.datascienceacademy.com.br/course?courseid=python-fundamentos)
- [Solyd](https://solyd.com.br/treinamentos/python-basico/)
- [Udemy](https://www.udemy.com/course/intro_python/)
- [LearnCafe](https://www.learncafe.com/cursos/curso-de-programacao-em-python)
- [Coursera PT1](https://pt.coursera.org/learn/ciencia-computacao-python-conceitos)
- [Coursera PT2](https://pt.coursera.org/learn/ciencia-computacao-python-conceitos-2)
- [Repositório para divulgação de conteúdo DataScience](https://github.com/TeoCalvo/teomerefs)

### Pré-requisitos
- Python 3+
- Pip (gerenciador de pacotes do Python)
- Acesso à internet
- VSCode instalado

```
pip install nome_pacote
pip install virtualenv
python3-virtualenv
```

### Criando Ambiente Virtual
<img src="https://secureservercdn.net/198.71.233.96/36q.76e.myftpupload.com/wp-content/uploads/2021/03/5f6e374b5cd697c336eda16b_vmb8G9Wzdf76q0Ke_ikGnDoni_cNhrDjof8FGQP2_RAtS4r_7wh2Pz_o48TvThR5DofW0HDKrjH6AixfJm4VukdAhrSSbcH1VzeTAe_0VKm6TNzvcWkXrlZl8fq63Eb9hmzOoz9r.png" width="auto" height="auto" loading="auto">

O comando padrão da criação segue o modelo virtualenv [opções] nome_da_pasta. Faremos o nosso com o comando virtualenv -p python3 venv_zup. O “-p python3” significa que estou obrigando que o ambiente virtual seja criado utilizando a versão 3 do Python:

<img src="https://secureservercdn.net/198.71.233.96/36q.76e.myftpupload.com/wp-content/uploads/2021/03/5f6e374be591682d7fddbabb_7sAT8oSn6pHFidLo_jSnoyxnx1MI-varVe9hIPc3kcQYAEhXojn-kOTGa3q-7MQ01nm9_yYjFvhP3hnhcRR9qTVoeAa1uB-y2iFOYEF5nIcQxjoE0WVD-KGYsTUT0fIJjYZl3tTg.png" width="auto" height="auto" loading="auto">
### Ativando Ambiente Virtual

- Linux/Mac: source path_to_venv/bin/activate
- Windows: path_to_venv/Scripts/activate.bat

<img src="https://secureservercdn.net/198.71.233.96/36q.76e.myftpupload.com/wp-content/uploads/2021/03/5f6e374b4171d6788cbe11e2_6B9U8v3SPrwyNbDcWddKPGvdsNM2x-40ONkRTVzDLaHr-0_aPyWg2yKzwvYx_U8kKIBHEAycfQFrVpiA6sLmwMPrBhKaZTQ3xAyEVyYNKzamT2cRdywbzdFCxUjVSnsOB6EpuSt5.png" width="auto" height="auto" loading="auto">

## Abra seu VSCode na pasta raíz do projeto 
Esta deve ser a pasta criada anteriormente (não dentro do venv_zup).

Crie um arquivo chamado requirements.txt e coloque o pytest como dependência do projeto:

<img src="https://secureservercdn.net/198.71.233.96/36q.76e.myftpupload.com/wp-content/uploads/2021/03/5f6e374b4171d6609fbe11e1_OgHUDmSkujvqQxknrUCBzPuVI1MgFyqqf00VPsXHgspkZ7X414ssdJLSxE3XBN-woy7pPpunVYJoy96enxX2mcOUNfw81AS6-XfXoektC1C-CrlIbZBJeqmERO-GQgewi2c494FV.png" width="auto" height="auto" loading="auto">

Instale as dependências do projeto com o comando pip install -r requirements.txt. Todas as dependências do projeto devem estar listadas nesse arquivo de texto. É ele que vai nos orientar sobre o que precisamos instalar para executar nossos projetos.

<img src="https://secureservercdn.net/198.71.233.96/36q.76e.myftpupload.com/wp-content/uploads/2021/03/5f6e374be2822c701ab6a53b_Trvw9dcRv0ebsOHsQzUAeXgAn9hPT4PesNMVtap3hC05T1RU-F6rAGzJ3rsjU3ef3pp-phLMhr88SST6rUY0DTQsiS4Q0I-RAwIbXMjNxkpGNj8uok8IpHmhsIYtEsaNtwzqucjf.png" width="auto" height="auto" loading="auto">

## Crie dois arquivos de testes simples
Lembre-se que os arquivos de testes devem ter o nome das formas *_test.py ou test_*.py e as funções de teste devem ter o nome test_*.

<img src="https://secureservercdn.net/198.71.233.96/36q.76e.myftpupload.com/wp-content/uploads/2021/03/5f6e374b896916f22efa389c_lkhYYQ-9n_DMj4QNDIrCLuDAvWg3LWVGTZoqSMR2vLUCRkS0izv8m4AkuEOBJqKAAveSVtsNxL_-swWsm_xZtTymdnKJxuZ2pfe1lme1Z5H6AMAiI5ky8-W35fNmYfna_Bs-42vb.png" width="auto" height="auto" loading="auto">

<img src="https://secureservercdn.net/198.71.233.96/36q.76e.myftpupload.com/wp-content/uploads/2021/03/5f6e374c4171d672cfbe11e3_9cKk6gwJDGHf8k3_TJbwOgW7wiPQuJNF4DQWiE1hva5VA69CNfK2kFTinKIUGus5jIVcCE12F3KoufNUKkAT5FaZkN-UMDey1VTywP6VQ1bUA-ZLZvKwZDVHksc4lMDWuhZUDQIu.png" width="auto" height="auto" loading="auto">

Execute os testes com o comando pytest (na raíz do projeto) e veja se tudo está sendo executado sem erros:

<img src="https://secureservercdn.net/198.71.233.96/36q.76e.myftpupload.com/wp-content/uploads/2021/03/5f6e374cc0be4813af85833d_Ea4nUa7_IbZKHMwtyc5iy5OrbvhiFtyEerlzbr45GLDBi2tOywxSjJZ4PbcvPpciBg-ey3vYQVljyiYtuX1BOBmmEmUzt8elAdmGMshnkBKX09ngl-NiR0_cXrC63e7nfPsxaQYe.png" width="auto" height="auto" loading="auto">

Mova esses testes para um diretório chamado tests.


