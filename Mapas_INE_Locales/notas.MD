#Para hacer unzip de las files
##find -name '*.zip' -exec sh -c 'unzip -d "${1%.*}" "$1"' _ {} \;
###Con esto debería hacer unzip en caso de que se necesiten reemplazar con algun mapa más reciente
