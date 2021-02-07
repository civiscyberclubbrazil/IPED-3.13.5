# IPED-3.13.5
Pericia  Forense Digital  ( PFD)
- Detecção de itens 7zip cifrados que omitem nomes dos subitens
- Habilita ignoreHardLinks por padrão em sistemas de arquivo HFS+
- Expõe novamente opção textSplitSize no AdvancedConfig.txt
Correções:
- Travamento eventual no processamento durante geração de thumbs de
vídeos (3.13.3)
- Falha no carregamento de cookie de marcadores em casos somente
leitura (3.13.1 - PCF Wladimir)
- Não funcionamento da opção robustImageReading no Linux (3.13.1)
- Falso alerta de &quot;imagem não encontrada&quot; ao abrir casos com discos
físicos no Windows (3.13)
- Conversão externa de PDF p/ imagem via PDFBox não incluia imagens
jbig2 (3.13.4)
- Conflito em CustomSignatures.xml havia deixado de abortar
processamento (3.13)
- NullPointer que abortava processamento ao ligar robustImageReading
em profiles blind (3.13)
- Marcadores automáticos incluíam itens pequenos com hash muito comum
(3.11)
- IgnoreHardLinks ignorava indexação de fragmentos de itens gigantes
(3.10)
