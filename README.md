# Criptografia Pós-Quântica (PQC), Criptoagilidade & Governança de IA

Este repositório reúne experimentos práticos, scripts de medição de desempenho e notas de pesquisa na interseção entre **Criptografia Pós-Quântica (PQC)**, **Criptoagilidade (*Crypto-Agility*)** e **Governança de Inteligência Artificial**.

## Objetivos da Pesquisa
* **Avaliação de Algoritmos PQC:** Medir tempo de execução, tamanho de chaves/assinaturas e sobrecarga de rede nos padrões definidos pelo **NIST** (*ML-KEM / Kyber*, *ML-DSA / Dilithium*), comparando-os com algoritmos clássicos (RSA/ECDSA).
* **Criptoagilidade e Gestão de Riscos:** Estruturar modelos de inventário criptográfico (*CBOM — Cryptography Bill of Materials*) e roteiros de transição segura para infraestruturas críticas, conectando práticas consolidadas de Governança de TI e Segurança da Informação (**ISO/IEC 27001** e **ISO 31000**) à era pós-quântica.
* **Governança e Segurança de IA:** Investigar o uso de técnicas de Aprendizado de Máquina para descoberta automatizada de dependências criptográficas vulneráveis e aplicar frameworks de governança (**ISO/IEC 42001** e **NIST AI RMF**) na proteção de dados e modelos de IA contra ameaças quânticas futuras (*Harvest Now, Decrypt Later*).

## Estrutura do Repositório
* `benchmark_pqc_simulacao.py`: Script inicial em Python para análise comparativa de sobrecarga de bytes e processamento entre criptografia clássica e pós-quântica.
* `/docs`: Notas técnicas sobre padronização NIST, arquitetura de criptoagilidade e governança de riscos em IA.

## Tecnologias e Padrões de Referência
* **Linguagens & Ferramentas:** Python 3.x, `liboqs-python` (Open Quantum Safe), `cryptography`, `pandas`
* **Normas & Frameworks:** NIST PQC Standards, ISO/IEC 27001, ISO 31000, ISO/IEC 42001, NIST AI RMF

---
*Repositório mantido para pesquisa científica aplicada em Segurança Cibernética, Criptoagilidade e Governança de IA.*
