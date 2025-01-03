# drone-security-patrol
Sistema de Patrulha de Segurança com Drones projetado para automatizar a vigilância utilizando drones equipados com detecção de objetos baseada em IA
# Sistema de Patrulha de Segurança com Drones

## Introdução
O Sistema de Patrulha de Segurança com Drones é uma solução inovadora projetada para automatizar a vigilância utilizando drones equipados com detecção de objetos baseada em IA. Aproveitando drones DJI, detecção de objetos com YOLO e sistemas de alerta em tempo real, este projeto visa aumentar a segurança em áreas industriais, fazendas e grandes propriedades. O sistema permite que drones patrulhem rotas predefinidas, detectem atividades suspeitas e notifiquem as equipes de segurança instantaneamente. Ele reduz custos operacionais, melhora a eficiência e oferece uma forma mais inteligente de proteger seus bens.

---

## Funcionalidades
- **Patrulha Automatizada**: Drones navegam autonomamente por pontos predefinidos.
- **Detecção de Objetos com IA**: Detecta e identifica objetos em tempo real usando YOLO.
- **Alertas em Tempo Real**: Envia notificações com imagens quando ameaças são detectadas.
- **Solução Escalável**: Projetado para integrar vários drones e cobrir grandes áreas.

---

## FAQ

### Qual é o objetivo deste projeto?
O objetivo é fornecer uma forma eficiente e econômica de aumentar a segurança de propriedades automatizando patrulhas e detecção de ameaças com drones e IA.

### Quais drones são suportados?
Atualmente, o projeto é projetado para drones DJI usando um SDK hipotético. Você pode adaptar o código para outras plataformas de drones modificando o módulo `DroneController`.

### Como funciona a detecção de objetos?
O sistema utiliza o YOLO (You Only Look Once), um modelo popular de aprendizado profundo para detecção de objetos em tempo real. Objetos detectados são destacados em imagens e registrados.

### Posso usar este projeto para monitoramento de vídeo ao vivo?
Sim, o código pode ser estendido para incluir transmissão de vídeo ao vivo e painéis de monitoramento.

### Como os alertas são enviados?
Alertas são enviados via uma API HTTP para o sistema de notificação de sua preferência (ex.: SMS, e-mail ou aplicativos personalizados). O módulo `AlertSystem` gerencia essa funcionalidade.

### Como posso modificar as rotas de patrulha?
As rotas são definidas como pontos GPS no arquivo `main.py`. Você pode adicionar ou modificar os pontos conforme suas necessidades.

### Este projeto está pronto para produção?
Este é um protótipo e pode exigir testes adicionais e personalização para uso em produção. Certifique-se de seguir protocolos de segurança e regulamentações locais para drones.

### Este sistema é autônomo ou precisa de controle manual?
O sistema é projetado para ser autônomo, ou seja, os drones patrulham rotas predefinidas automaticamente, detectam objetos ou atividades suspeitas com IA e enviam alertas em tempo real sem intervenção constante. No entanto, alguns momentos requerem supervisão humana:
- **Configuração inicial**: Para definir as rotas de patrulha e posicionar o drone.
- **Manutenção**: Para monitorar a bateria, sensores e conectividade.
- **Eventos excepcionais**: Caso o drone encontre obstáculos ou perca a conexão, pode ser necessário controle manual.
Além disso, o sistema pode ser adaptado para incluir um modo de controle manual em situações de emergência ou monitoramento em tempo real.

### Posso contribuir para este projeto?
Com certeza! Sinta-se à vontade para fazer um fork do repositório, sugerir melhorias ou enviar pull requests para tornar este sistema ainda melhor.

---

Para mais detalhes, consulte o arquivo [README](README.md) ou entre em contato com os contribuidores do projeto.
