Instalando virtual enviroment
    - Python 3.8
    - Pip
        - Verificar se o gerenciador de pacote do python está instalado:
            $ pip -V
        - Caso não esteja instalado:
            $ sudo apt-get install python3-pip
    - Virtual environment
        - Instalando
            $ sudo apt-get install -y python3-virtualenv
            ou
            $ sudo pip3 install virtualenv

        - Criar venv
            $ virtualenv venv
       
        Ativação de desativação
            $ source venv/bin/activate
            $ desactivate

        No Windows:
            $ python -m venv venv
            $ .\venv\Scripts\Activate.ps1

        Requirements.txt
            - https://github.com/miguelgrinberg/REST-tutorial/blob/master/requirements.txt

            Instalando as dependências
                - pip install -r requirements.txt
