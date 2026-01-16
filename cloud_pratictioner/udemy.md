# EC2

Elastic Compute Cloud (IAAS) => Infrastruct as a service - virtual machines

## Categorias

- M* e T* -> uso geral
- C\* -> Otimizada para computaçao
- R*, U* e z1d-> Otimizadas para memoria
- R8, X\* e -> Otimizadas para memoria

# Modelos de aquisicao

1. Sob demanda, caro
1. saving plans, o mais enconta mas e necessario assinar um contrato de 1 a 3 anos
1. spot, pode chegar a 90% do preço do saving plans porem usa as instancias que a AWS nao usa mas quando ela for usar ela pega a sua maquina
1. host dedicados, muito caro
1. capacidade pro demanda, um pouco caro, vc define um horario e data que vc ira usar o recurso

obs: a AWS cobra pro segundo, com o limite minimo de 60 segundos

# Security groups

Os Security Groups atuam como um firewall virtual para as suas instâncias Amazon EC2 para controlar o tráfego de entrada e saída.

# EBS

Elastic Block Store (not storage), e basicamente o um servidor que oferece armazenamento para outros servidores via rede, eles
so podem ser associados a serviços que estan na mesma zona, oferece 2 tipos de disco

1. hdd (barato e lento)
2. ssd (rapido e caro)

ele se encontra dentro da categoria EC2

# AWS Well-Architected Framework
