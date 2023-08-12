# Medwait
Um sistema de senhas de hospital que funciona de verdade.

## Problemas
Após uma experiencia horrível em um hospital na zona leste de São Paulo, onde fiquei 8 horas esperando sem conseguir ser atendido por conta do sistema "novo" de senhas de atendimento que o hospital tinha implementado, provavelmente em rede estadual, pois o sistema acompanhava o logo do Governo do Estado. Infelizmente, o sistema é altamente falho por uma série de fatores:

- Os pacientes não sabem tirar as próprias senhas (por culpa do sistema)
  - As nomenclaturas de senhas por categoria (pediatria, clinico geral, idosos, samu, etc...) não são bem definidos e por conta disso,voce pode facilmente se confundir e tirar uma senha errada.
- O fluxo de atendimento não é claro, inclusive nas cores que indicam o grau de prioridade no atendimento:
  - Vermelho: Urgente
  - Laranja:  Alto
  - Amarelo:  Alerta
  - Verde:    Simples
  - Azul: (inútil, pessoas nao vão ao médico quanto nao estão sentindo nada, mesmo assim, esse status existia)
- Não é possível saber uma previsão ou até mesmo sua prioriadade numa possível fila de atendimento, nem sequer o paciente tem noção do fluxo inteiro.

## Como esses desafios serão resolvidos
Além de listar os problemas acima, resolvi criar algo que funcione de verdade, que faça com que os pacientes tenham a clara noção do fluxo de início ao fim do seu atendimento, sabendo na triagem qual a prioridade do seu atendimento.

Como fluxo, o MedWait deverá fornecer ao hospital um atendimento rápido para casos de prioridades menores, um especializado para casos maiores e uma exeçao para casos extraordinários (como SAMU).Dessa forma, um atendimento que leva hoje 5 horas (ou como foi comigo 8 horas e sem um médico) com um fluxo focado levaria no máximo 1 hora para casos simples no pior cenário (hospital cheio) e no máximo 1:30h para casos urgentes também no pior cenário.
