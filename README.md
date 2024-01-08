# Treinamento do Modelo YOLOv5

Resultado:

![Captura de Tela - Exemplo](https://github.com/ZeroGalack/Treinamento-modelo-YOLOv5/assets/100045024/6351ca15-9c17-4c54-98b7-de08692d0335)

---

## Descrição

Este repositório é dedicado ao treinamento do modelo YOLOv5 para detecção de objetos. O YOLOv5 é um framework de visão computacional que permite treinar modelos eficientes para identificar e localizar objetos em imagens.

---

### Treinamento na Nuvem com Google Colab

O treinamento do modelo foi realizado na nuvem usando o Google Colab. Isso oferece uma plataforma poderosa e escalável para treinamento de modelos de aprendizado profundo sem a necessidade de recursos locais intensivos.

---

## Instruções de Uso

### Requisitos

1. **Instalação do YOLOv5:**
   Certifique-se de ter o YOLOv5 instalado em seu ambiente. Consulte a [documentação oficial do YOLOv5](https://github.com/ultralytics/yolov5) para instruções de instalação.

2. **Conjunto de Dados:**
   Prepare um conjunto de dados anotado para treinar o modelo. Siga as práticas recomendadas para anotação de dados compatíveis com o formato YOLO.

### Treinamento do Modelo

1. **Configuração do Arquivo YAML:**
   Modifique o arquivo de configuração YAML (`customdata.yaml`) com as configurações específicas para o seu conjunto de dados.

2. **Treinamento:**
   Execute o comando de treinamento utilizando o YOLOv5:

   ```bash
   python train.py --data path/to/customdata.yaml --weights yolov5s.pt --epochs 50
