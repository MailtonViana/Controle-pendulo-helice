# Controle-pendulo-helice
Projeto desenvolvido na disciplina de Sistemas de Controle, onde o objetivo era controlar a posição através de um ângulo de entrada de um pêndulo com uma hélice na ponta.
Controle de Posição de um Sistema Pêndulo-Hélice
•	Objetivo Geral
Implementar um controlador PID embarcado num Arduino para o problema do controle da posição angular de um pêndulo atuado por uma hélice.

•	Resumo do funcionamento
O braço do pêndulo consiste de uma haste de comprimento L e massa m (massa da haste + a massa do motor), tendo uma de suas extremidades fixa, por meio de um pivô, a um ponto estabilizado no sistema de coordenadas x; y; z. 
Considera-se o pivô como a origem do sistema de coordenadas. O acoplamento haste-pivô é tal que a haste se movimenta livremente no plano x; y, descrevendo um ângulo θ. À extremidade livre da haste é fixado um motor DC acoplado a uma hélice de massa muito pequena, vamos considerar desprezível. O comprimento L do braço do pêndulo compreende a distância entre o eixo do motor e o ponto de conexão com o pivô.
A ideia é estabilizar o pêndulo com a hélice numa certa coordenada equivalente a uma altura h em relação ao chão, de modo que, ao mexer nele, mudando sua posição, automaticamente ele possa voltar para sua posição.
