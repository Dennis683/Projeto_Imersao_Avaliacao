# Projeto_Imersão_Avaliação

O objetivo deste código é fornecer um sistema simples de recomendação de conteúdo educacional personalizado. Ele permite que os usuários façam consultas sobre tópicos de interesse educacional e recebam recomendações de materiais educacionais relevantes com base nessas consultas.

Os dados que estão sendo utilizados neste código são os seguintes:

Materiais Educacionais: Uma lista de documentos educacionais, cada um contendo um título e um conteúdo relacionado ao tema. Esses materiais educacionais são representados como um dicionário Python e organizados em uma lista chamada MATERIAIS_EDUCACIONAIS. Cada documento tem um título que descreve o assunto e um conteúdo que fornece informações sobre o tópico educacional.

Embeddings de Conteúdo: Para cada documento educacional na lista, são calculados embeddings de conteúdo usando um modelo pré-treinado. Esses embeddings representam as características semânticas e contextuais do texto de cada documento.

Consultas dos Usuários: Os usuários podem fazer consultas sobre tópicos educacionais específicos. Essas consultas são inseridas como entrada no sistema de recomendação.

Recomendação de Conteúdo Educacional: Com base na consulta do usuário, o sistema de recomendação compara os embeddings da consulta com os embeddings dos documentos educacionais e determina qual documento é mais relevante para a consulta. Em seguida, o conteúdo desse documento é recomendado como resposta à consulta do usuário.
