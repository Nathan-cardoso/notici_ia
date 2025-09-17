# Notici_IA

Este projeto tem como objetivo apresentar uma análise sobre notícias de tecnologia no Brasil, a partir de chamadas de API do OpenRouter. O modelo integrado ao projeto foi o **deepseek v3.1 (free)**, responsável por gerar resumos de notícias públicas do Brasil, utilizando como base de dados o **Klagge**.  

## Estrutura do Projeto

O repositório contém uma pasta chamada <a href="https://github.com/Nathan-cardoso/notici_ia/tree/main/dataset">dataset</a>, onde está localizado o conjunto de dados utilizado neste projeto. Além disso, o arquivo <a href="https://github.com/Nathan-cardoso/analise-arboviroses-rn/blob/main/requirements.txt">requirements.txt</a> contém todas as dependências necessárias para a execução do projeto.

## Como executar esse projeto

Para rodar este projeto, recomenda-se utilizar um ambiente virtual (*venv*). Abaixo seguem as instruções para **Linux** e **Windows**:  

### 1. Clonar o repositório  

```bash
git clone https://github.com/Nathan-cardoso/notici_ia.git
cd notici_ia
```

### Linux

```bash

# Criar a venv
python3 -m venv venv

# Ativar a venv
source venv/bin/activate
```

---

### Windows
```bash
# Criar a venv
python -m venv venv

# Ativar a venv
venv\Scripts\activate
```
---

Agora com o venv ativado (provavelmente, irá aparecer o nome venv ao lado do seu terminal de linha de comandos)

execute o seguinte passo:

```bash
# Irá instalar todas as dependências do requirements. OBS: essa ação pode demorar alguns minutos
pip install -r requirements.txt

```
## Resumo gerado pela IA

**Resumo das Notícias (Baseado no Dataframe Fornecido):**

O período analisado retrata um setor de tecnologia em ebulição, marcado por altos e baixos, inovações e escândalos. Grandes empresas como **Apple, Amazon, Google, Facebook e Samsung** dominam as manchetes. A **Apple** vive momentos voláteis, com quedas e recuperações nas ações, anúncio de novos produtos como o iOS 13 e problemas técnicos para resolver. A **Amazon** consolida seu poderio, tornando-se a empresa mais valiosa do mundo, enquanto seu fundador, Jeff Bezos, enfrenta questões pessoais e de segurança.

O **Facebook** e seu CEO, Mark Zuckerberg, estão constantemente sob pressão devido a uma série de crises: vazamentos de dados massivos (como o caso Cambridge Analytica), falhas de segurança graves, investigações regulatórias e a propagação de desinformação em sua plataforma. A empresa anuncia medidas para combater fake news, mas sofre com quedas de reputação e até mesmo uma pane global que derrubou seus aplicativos.

A segurança cibernética é um tema urgente e recorrente. **Vazamentos de dados** em grande escala, golpes aplicados via WhatsApp e outros apps, e vulnerabilidades críticas descobertas em softiais são frequentes. A **WhatsApp**, também do Facebook, é palco de golpes e anuncia restrições no encaminhamento de mensagens para combater a desinformação.

A **guerra comercial e tecnológica entre EUA e China** tem a Huawei como protagonista, enfrentando restrições e acusações de espionagem. Outros temas em destaque incluem o avanço do **5G**, a popularidade de aplicativos de mobilidade urbana como **Uber** e **99**, a febre de apps como **FaceApp** e **Zoom**, e a crescente regulação governamental sobre o setor. A **CES**, maior feira de tecnologia do mundo, também é um evento de destaque no período.

**Insights:**

Analisando o conjunto de notícias, fica evidente que o período foi definido por dois eixos principais: a **inovação disruptiva** e a **crise de confiança**. Enquanto as empresas avançam em tecnologias como IA, IoT e pagamentos digitais, elas simultaneamente lutam para conter danos colaterais de sua própria escala e influência. A segurança e a privacidade do usuário deixaram de ser questões técnicas secundárias e se tornaram o centro do debate público, impulsionando ações de reguladores em todo o mundo. O dataframe sugere um ponto de inflexão onde a sociedade começou a demandar accountability e responsabilidade ética das gigantes tech, um movimento que deve moldar o futuro do setor.
