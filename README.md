# shortner
-----> Building on the Heroku-20 stack
-----> Using buildpack: heroku/python
-----> Python app detected
-----> Using Python version specified in runtime.txt
 !     Python has released a security update! Please consider upgrading to python-3.7.12
       Learn More: https://devcenter.heroku.com/articles/python-runtimes
-----> Installing python-3.7.8
-----> Installing pip 21.3.1, setuptools 57.5.0 and wheel 0.37.0
-----> Installing SQLite3
-----> Installing requirements with pip
       Collecting pyrogram
         Downloading Pyrogram-1.4.7-py3-none-any.whl (3.0 MB)
       Collecting tgcrypto
         Downloading TgCrypto-1.2.3-cp37-cp37m-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (61 kB)
       Collecting aiohttp==3.7.4
         Downloading aiohttp-3.7.4-cp37-cp37m-manylinux2014_x86_64.whl (1.3 MB)
       Collecting requests
         Downloading requests-2.27.1-py2.py3-none-any.whl (63 kB)
       Collecting bs4
         Downloading bs4-0.0.1.tar.gz (1.1 kB)
         Preparing metadata (setup.py): started
         Preparing metadata (setup.py): finished with status 'done'
       Collecting pyshorteners
         Downloading pyshorteners-1.0.1.tar.gz (10.0 kB)
         Preparing metadata (setup.py): started
         Preparing metadata (setup.py): finished with status 'done'
       Collecting chardet<4.0,>=2.0
         Downloading chardet-3.0.4-py2.py3-none-any.whl (133 kB)
       Collecting async-timeout<4.0,>=3.0
         Downloading async_timeout-3.0.1-py3-none-any.whl (8.2 kB)
       Collecting attrs>=17.3.0
         Downloading attrs-21.4.0-py2.py3-none-any.whl (60 kB)
       Collecting multidict<7.0,>=4.5
         Downloading multidict-6.0.2-cp37-cp37m-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (94 kB)
       Collecting typing-extensions>=3.6.5
         Downloading typing_extensions-4.0.1-py3-none-any.whl (22 kB)
       Collecting yarl<2.0,>=1.0
         Downloading yarl-1.7.2-cp37-cp37m-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_12_x86_64.manylinux2010_x86_64.whl (271 kB)
       Collecting pysocks==1.7.1
         Downloading PySocks-1.7.1-py3-none-any.whl (16 kB)
       Collecting pyaes==1.6.1
         Downloading pyaes-1.6.1.tar.gz (28 kB)
         Preparing metadata (setup.py): started
         Preparing metadata (setup.py): finished with status 'done'
       Collecting certifi>=2017.4.17
         Downloading certifi-2021.10.8-py2.py3-none-any.whl (149 kB)
       Collecting urllib3<1.27,>=1.21.1
         Downloading urllib3-1.26.8-py2.py3-none-any.whl (138 kB)
       Collecting charset-normalizer~=2.0.0
         Downloading charset_normalizer-2.0.12-py3-none-any.whl (39 kB)
       Collecting idna<4,>=2.5
         Downloading idna-3.3-py3-none-any.whl (61 kB)
       Collecting beautifulsoup4
         Downloading beautifulsoup4-4.10.0-py3-none-any.whl (97 kB)
       Collecting soupsieve>1.2
         Downloading soupsieve-2.3.1-py3-none-any.whl (37 kB)
       Building wheels for collected packages: pyaes, bs4, pyshorteners
         Building wheel for pyaes (setup.py): started
         Building wheel for pyaes (setup.py): finished with status 'done'
         Created wheel for pyaes: filename=pyaes-1.6.1-py3-none-any.whl size=26362 sha256=4afb36d91c67d273c2a39ae48839d7ff6f06903edf1ff049d6a6f4a177d8b791
         Stored in directory: /tmp/pip-ephem-wheel-cache-nro8fekk/wheels/42/a3/7d/73d60820adb58d818179cdec3fc1be66f6f7453513a3ff0b05
         Building wheel for bs4 (setup.py): started
         Building wheel for bs4 (setup.py): finished with status 'done'
         Created wheel for bs4: filename=bs4-0.0.1-py3-none-any.whl size=1271 sha256=a1cd44d3eff524ce8ae38a176627835e4cf87f1e2b2fce97c02d7e4871a3545b
         Stored in directory: /tmp/pip-ephem-wheel-cache-nro8fekk/wheels/0a/9e/ba/20e5bbc1afef3a491f0b3bb74d508f99403aabe76eda2167ca
         Building wheel for pyshorteners (setup.py): started
         Building wheel for pyshorteners (setup.py): finished with status 'done'
         Created wheel for pyshorteners: filename=pyshorteners-1.0.1-py3-none-any.whl size=17496 sha256=168557f9f1eb45ba28ee93e72c1d85128b3d674d9442a82b0f0ddf63927e1de1
         Stored in directory: /tmp/pip-ephem-wheel-cache-nro8fekk/wheels/1e/c6/50/b06780af353f181fae16d55deb7b47f8aef30567e24a9ce456
       Successfully built pyaes bs4 pyshorteners
       Installing collected packages: urllib3, typing-extensions, soupsieve, multidict, idna, charset-normalizer, certifi, yarl, requests, pysocks, pyaes, chardet, beautifulsoup4, attrs, async-timeout, tgcrypto, pyshorteners, pyrogram, bs4, aiohttp
       Successfully installed aiohttp-3.7.4 async-timeout-3.0.1 attrs-21.4.0 beautifulsoup4-4.10.0 bs4-0.0.1 certifi-2021.10.8 chardet-3.0.4 charset-normalizer-2.0.12 idna-3.3 multidict-6.0.2 pyaes-1.6.1 pyrogram-1.4.7 pyshorteners-1.0.1 pysocks-1.7.1 requests-2.27.1 soupsieve-2.3.1 tgcrypto-1.2.3 typing-extensions-4.0.1 urllib3-1.26.8 yarl-1.7.2
-----> Discovering process types
       Procfile declares types -> worker
-----> Compressing...
       Done: 56.7M
-----> Launching...
       Released v4
       https://vhgfhn.herokuapp.com/ deployed to Heroku
