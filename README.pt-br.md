# 📊 Análises Espectroscópicas com Metodo_Espectroscopico.ipynb

> 🌐 Este repositório está disponível em Português.  
> Para uma versão em Inglês (English), consulte: [README.md](README.md)  
> O notebook também está disponível em Inglês. Consulte esta [`versão`](./Spectroscopic_Method.ipynb) no arquivo README em inglês!
> Este repositório está descrito como produção técnica no Currículo Lattes do [`autor`](http://lattes.cnpq.br/3150100365693703).

## 📘 Descrição

Este notebook é autoexplicativo e foi desenvolvido para ser analisado em conjunto com a monografia associada. O programa é aplicável exclusivamente a plasmas de gás nitrogênio (N₂), com foco no Segundo Sistema Positivo da molécula neutra (N₂) e no Primeiro Sistema Negativo do íon molecular (N₂⁺). Outras transições eletrônicas ou espécies não foram testadas.

## ▶️ Como Visualizar

Para visualizar o código e os resultados diretamente pelo GitHub, basta clicar no arquivo abaixo e usar o visualizador nativo do Jupyter:

🔗 [`Metodo_Espectroscopico.ipynb`](./Metodo_Espectroscopico.ipynb)

## 📁 Arquivos Necessários (caso desejar testar o programa)

Certifique-se de que os seguintes arquivos estejam no mesmo diretório do notebook para garantir o funcionamento correto durante a execução:

- `100mA.txt` — Arquivo de dados espectroscópicos, contendo intensidade vs. comprimento de onda (nm). Pode ser modificado por outros dados de espectros
- `RxTe.dat` — Arquivo contendo a o gráfico de Razão vs. Temperatura Eletrônica de André Ricard. **⚠️ Não modifique este arquivo.**

## ⚙️ Execução Local (opcional)

Se preferir rodar o notebook localmente:

1. Certifique-se de ter o Python 3.x instalado.
2. Instale as dependências com:

   ```bash
   pip install -r requirements.txt

3. Abra o notebook com:

    ```bash
    jupyter notebook Metodo_Espectroscopico.ipynb

Sinta-se à vontade para explorar, adaptar e utilizar este projeto como base para outros estudos espectroscópicos em descargas gasosas. ✨
