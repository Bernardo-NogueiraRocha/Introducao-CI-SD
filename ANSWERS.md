1) Toda vez que há um push para a branch master, ele executa os trabalhos (jobs) descritos na pipeline.
2) O Runner é a aplicação que baixa o código e executa um trabalho (job) descrito na pipeline, geralmente é um servidor ou uma máquina virtual que hospeda a aplicação.
3) Em um você corre o risco de incompatibilidade de sistemas operacionais e no outro se tem garantia de execução por conta da containerização (Docker).
4) Por conta da reprodutibilidade e isolamento do sistema operacional, evitando o "funciona na minha máquina, mas não não no runner do github actions".
5) 