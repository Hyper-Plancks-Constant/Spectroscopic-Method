# 📊 Análises Espectroscópicas com Espectro_Totalmente_Oficial.ipynb

> 🌐 Este repositório está disponível em português.  
> Para uma versão em inglês, consulte: [README_en.md](README_en.md) *(em breve)*

## 📘 Descrição

Este notebook é autoexplicativo e foi desenvolvido para ser analisado em conjunto com a monografia associada. O programa é aplicável exclusivamente a plasmas de gás nitrogênio (N₂), com foco no Segundo Sistema Positivo da molécula neutra (N₂) e no Primeiro Sistema Negativo do íon molecular (N₂⁺). Outras transições eletrônicas ou espécies não foram testadas.

## ▶️ Como Visualizar

Para visualizar o código e os resultados diretamente pelo GitHub, basta clicar no arquivo abaixo e usar o visualizador nativo do Jupyter:

🔗 [`Espectro_Totalmente_Oficial.ipynb`](./Espectro_Totalmente_Oficial.ipynb)

## 📁 Arquivos Necessários (caso desejar testar o programa)

Certifique-se de que os seguintes arquivos estejam no mesmo diretório do notebook para garantir o funcionamento correto durante a execução:

- `100mA.txt` (Arquivo de dados espectroscópicos, contendo Intensidade x Comprimento de Onda em nm. Pode ser modificado por outros dados de espectros)
- `RxTe.dat` (Arquivo contendo a o gráfico de Razão x Temperatura Eletrônica de André Ricard. NUNCA MODIFIQUE ESSE ARQUIVO)

## ⚙️ Execução Local (opcional)

Se preferir rodar o notebook localmente:

1. Certifique-se de ter o Python 3.x instalado.
2. Instale as dependências com:

   ```bash
   pip install -r requirements.txt

3. Abra o notebook com:

    ```bash
    jupyter notebook Espectro_Totalmente_Oficial.ipynb

Sinta-se à vontade para explorar, adaptar e utilizar este projeto como base para outros estudos espectroscópicos em descargas gasosas. ✨
