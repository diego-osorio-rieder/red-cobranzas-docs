# Generación del archivo de documentacion desde el .yml

    npm install -g redoc-cli
    cd open-api
    redoc-cli bundle -o ..\practipago.html practipago.yml
    redoc-cli bundle -o ..\aquipago.html aquipago.yml
    redoc-cli bundle -o ..\pagoexpress.html pagoexpress.yml
    