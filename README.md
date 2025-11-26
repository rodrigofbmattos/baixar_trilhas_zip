# baixar_trilhas_zip
Aplicação que varre automaticamente uma estrutura hierárquica de pastas, identifica arquivos .txt dentro de cada pasta contendo links do Google Drive, e baixa o arquivo ZIP de cada pasta ou baixa pastas completas para dentro das pastas onde cada arquivo .txt foi encontrado.
Caso o link dentro de cada arquivo .txt seja repetido, não baixa novamente.
Esta aplicação usa as bibliotecas extras: **gdown**, **requests** e **tqdm**.

O **gdown** é uma biblioteca Python que serve para baixar arquivos do Google Drive de forma simples, especialmente quando o link é do tipo que o _requests_ ou _wget_ não conseguem baixar diretamente por causa das proteções de download do Google Drive.

Para instalar o pacote **gdown**, use o comando: `pip install gdown`.

O **requests** é uma das bibliotecas mais populares do Python para fazer requisições HTTP de forma simples e intuitiva. Ela permite que seu código se comunique com APIs, websites, servidores e qualquer serviço que use HTTP/HTTPS.

Para instalar o pacote **requests**, use o comando: `pip install requests`.

O **tqdm** é uma biblioteca que serve para exibir barras de progresso elegantes, rápidas e simples em loops no Python.

Para instalar o pacote **tqdm**, use o comando: `pip install tqdm`.
