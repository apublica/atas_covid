## Metodologia utilizada na reportagem [Campeões de ausências e omissões: o papel de cada ministério nas atas secretas](https://apublica.org/2023/02/campeoes-de-ausencias-e-omissoes-o-papel-de-cada-ministerio-nas-atas-secretas/)

O texto do arquivo em PDF com as 233 atas foi extraído com um código em Python, e limpo para facilitar a visualização de padrões no texto. O resultado foi colocado em uma [planilha](https://github.com/apublica/atas_covid/blob/main/ATAS_DOC.xlsx);

A partir dos textos nas células, foram estruturadas as seguintes informações:
- Número da reunião;
- Data;
- Horário de início;
- Horário de término;
- Memória.

Na coluna “Memória”, buscamos por expressões específicas sobre a participação de uma determinada pasta, como a sigla do órgão seguido de um informe, registro de ausência de considerações ou falta.

Os arquivos contendo as [atas](https://apublica.org/wp-content/uploads/2023/02/Atas-das-reunioes-do-Comite-de-Crise-da-Covid-19-CCOP.pdf), dados e [código](https://github.com/apublica/atas_covid/blob/main/codigo.ipynb) utilizados nesta reportagem podem ser vistos no GitHub da Agência Pública.
