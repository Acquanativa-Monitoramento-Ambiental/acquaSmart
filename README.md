# AcquaSmart

O AcquaSmart é o software da Acqua Nativa Monitoramento Ambiental para testar,
configurar e calibrar os sensores AcquaSensor (T, TD, TE, TO, TP e TDO) em
campo, pelo computador.

Com ele você pode:

- ver as leituras do sensor em tempo real e gravá-las em um arquivo CSV;
- consultar número de série, endereço Modbus, versões de hardware e firmware;
- alterar a configuração do sensor e calibrá-lo no local.

## Download

**[Baixe a versão mais recente](https://github.com/Acquanativa-Monitoramento-Ambiental/acquaSmart/releases/latest)**
— em *Assets*, clique em `AcquaSmart-vX.Y.Z.exe`.

É um único executável para Windows: não precisa de instalação nem de Python.
Basta baixar e abrir.

Na primeira execução o Windows pode mostrar o aviso **"O Windows protegeu o
computador"** (SmartScreen), porque o executável não é assinado digitalmente.
Clique em **Mais informações** e depois em **Executar assim mesmo**.

Versões anteriores, incluindo a 1.05, continuam disponíveis em
[Releases](https://github.com/Acquanativa-Monitoramento-Ambiental/acquaSmart/releases).

## Como utilizar

1. Conecte o sensor ao computador com um conversor USB–RS485 e verifique se o
   sensor está alimentado.
2. Abra o AcquaSmart, escolha a porta COM do conversor e clique em
   **Conectar**.
3. Se o sensor não responder, clique em **Diagnosticar**: o aplicativo verifica
   a comunicação e indica o que corrigir.

O manual do usuário em PDF acompanha cada versão, junto do executável, em
*Assets*. O manual da versão 1.05 está na release
[v1.05](https://github.com/Acquanativa-Monitoramento-Ambiental/acquaSmart/releases/tag/v1.05).

## Suporte

Dúvidas, problemas ou sugestões: **suporte@acquanativa.com.br**.

Ao pedir suporte, informe a versão do AcquaSmart. Ela aparece no rodapé da
janela, na primeira linha do log e na primeira linha de cada arquivo CSV.

## Licença

© Acqua Nativa Monitoramento Ambiental. Todos os direitos reservados.

O AcquaSmart é distribuído gratuitamente aos clientes da Acqua Nativa para uso
com os sensores AcquaSensor. Não é software livre: é proibido redistribuir,
modificar ou fazer engenharia reversa do executável sem autorização por
escrito.
